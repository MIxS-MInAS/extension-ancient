# extension-ancient

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
3. Update existing terms and add new terms in/to the `src/mixs/schema/ancient.yaml` file on the two branches, as per the aggregated feedback under `proposals/`
  - Important: try to make one commit for each new term, and each term update (all changes to all entries for a given term in one), this will allow us further automate release notes
4. Coordination team cross-reviews the two PRs and merge in
5. Generate additional JSON and TSV files based on instructions on technical notes
  - The YAML -> JSON conversion will include LinkML schema validation, so additional correction PRs made be required at this point!
6. Make a release with the following format
  - Tag: vX.X.X
  - Title: vX.X.X
  - Generate release notes
  - Set as latest
7. Go to the MInAS repo and make an updated mega-yaml plus release following instructions there

## Technical notes

Use the YAML (in as far as possible similar format as MIxS LinkML structure) as the source of truth.

### JSON Conversion

To generate the JSON version, install LinkML

```bash
pip install linkml
```

And run the following command, assuming root of repo:

```bash
gen-json-schema src/mixs/schema/ancient.yml > src/mixs/schema/ancient.json
```

### MIxS TSV Style Conversion

To convert to the original MIxS TSV style, we can use [a script](https://github.com/GenomicsStandardsConsortium/mixs/blob/dd1a08f82637e80657f00b4551547a9b4b62c0d3/src/scripts/linkml2class_tsvs.py) developed by @TurboMam.

This script has been copied and modified very slightly to include the `python3` shebang, and is placed under `scripts` until properly packaged for the MIxS project.

To use this script, you only need `python3` and no other dependencies (it seems).

In the root of this directory run:

```bash
./scripts/linkml2class_tsvs.py --schema-file src/mixs/schema/ancient.yml --output-dir projects/class-model-tsvs/
```
