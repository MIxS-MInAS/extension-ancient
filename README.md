# extension-ancient

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16135943.svg)](https://doi.org/10.5281/zenodo.16135943)

A MIxS extension proposal for 'ancient DNA' samples.

## Repository Structure

The repo is laid out as follows:

- `feedback/`
  - `<date>-<eventid>`: contains collated tables from community feedback sessions
- `proposals/`
  - `<upcoming version>`: contains consensus term update proposals for inclusion in the next version of the standard
- `project/`:
  - `class-model-tsvs/`: contains MIxS <= v5 style TSVs for the extension for more-human readable inspection
- `scripts/`: contains various helper scripts for processing JSON, YAML, and feedback data where necessary
- `src/`
  - `mixs/`: contains the structured YAML and JSON files of the latest release of the extension

## Update workflows

1. Gather all feedback from feedback sessions (`feedback/`) and development workshops (`proposals/<upcoming_version>`) in the forms of JSONs
2. Coordination team makes two branch and associated PRs:
   - `<upcoming version>-termupdates`
   - `<upcoming version>-newterms`
3. Update existing terms and add new terms in/to the `src/mixs/schema/ancient.yaml` file on the two branches
   - Updates as per the aggregated feedback under `proposals/`, but can be evaluated or 'vetoed' for technical reasons
   - Important: try to make one commit for each new term and term update, with a descriptive message as to the change.
   - For each term, all changes to (description, examples, etc.) should be in one commit and described in the commit message (this will allow us further automate release notes)
4. Coordination team cross-reviews the two PRs and merge in
5. Run validation (TO BE AUTOMATED)
   - `linkml lint --config linkml-lint-config.yml src/mixs/schema/ancient.yml`: to ensure there are no _errors_ or important missing information about or misformatting of each term (slot)
   - `linkml validate -s <schema>.yaml --target-class Ancient <test_data>.csv`: checks that the schema can be used against an actual metadata test file [NOT YET IMPLEMENTED]
6. In a new PR, generate additional JSON and TSV files based on instructions on technical notes (containing all changes/new terms)
   - `gen-csv src/mixs/schema/ancient.yml > src/mixs/schema/ancient.csv`: checks that the schema can be converted to a basic CSV format
   - `gen-json-schema src/mixs/schema/ancient.yml > src/mixs/schema/ancient.json` checks that the schema can be converted to a basic JSON format
   - The YAML -> JSON conversion will include additioanl LinkML schema validation, so additional correction PRs made be required at this point!
7. Generate the 'old style' MIxS checklist
   - `./scripts/linkml2class_tsvs.py --schema-file src/mixs/schema/ancient.yml --output-dir projects/class-model-tsvs/`
8. Make a [GitHub release](https://github.com/MIxS-MInAS/extension-ancient/releases) with the following format:
   - Tag: vX.X.X
   - Title: vX.X.X
   - Generate release notes based on a cleaned up `git log --oneline` that has the git hash and the informative commit message
   - Set as latest
9. Go to the MInAS repo and make an updated mega-yaml plus release following instructions there

## Technical notes

Use the YAML (in as far as possible similar format as MIxS LinkML structure) as the source of truth.

### MIxS TSV Style Conversion

To convert to the original MIxS TSV style, we can use [a script](https://github.com/GenomicsStandardsConsortium/mixs/blob/a7df14c160ebab176bbc5ac212b869371270d464/src/scripts/linkml2class_tsvs.py) developed by @TurboMam.

This script has been copied and modified very slightly to include the `python3` shebang, and is placed under `scripts` until properly packaged for the MIxS project.

To use this script, you only need `python3` and no other dependencies (it seems).

In the root of this directory run:

```bash
./scripts/linkml2class_tsvs.py --schema-file src/mixs/schema/ancient.yml --output-dir projects/class-model-tsvs/
```

### Latest tag

We use a GitHub action to generate a special 'latest' tag that points to the commit of the latest release.
This allows a more 'user friendly' URL for downloading a specific file, rather than making users have to download a release tarball and extract a specific file.
