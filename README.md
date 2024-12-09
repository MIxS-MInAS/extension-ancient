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
3. Update existing terms and add new terms in/to the `src/mixs/schema/ancient.yaml` file on the two branches
   - Updates as per the aggregated feedback under `proposals/`, but can be evaluated or 'vetoed' for technical reasons
   - Important: try to make one commit for each new term and term update, with a descriptive message as to the change.
   - For each term, all changes to (description, examples, etc.) should be in one commit and described in the commit message (this will allow us further automate release notes)
4. Coordination team cross-reviews the two PRs and merge in
5. In a new PR, generate additional JSON and TSV files based on instructions on technical notes (containing all changes/new terms)
   - The YAML -> JSON conversion will include LinkML schema validation, so additional correction PRs made be required at this point!
6. Make a release with the following format
   - Tag: vX.X.X
   - Title: vX.X.X
   - Generate release notes based on a cleaned up `git log --oneline` that has the git hash and the informative commit message
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

### Latest tag

We use a GitHub action to generate a special 'latest' tag that points to the commit of the latest release.
This allows a more 'user friendly' URL for downloading a specific file, rather than making users have to download a release tarball and extract a specific file.

## Validation

The following validation steps will (eventually) be carried out on each PR

- `linkml lint <schema>.yaml`: to ensure there are no missing information about or misformatting of each term (slot)
- `gen-csv`: checks that the schema can be converted to a basic CSV format
- `gen-json`: checks that the schema can be converted to a basic JSON format
- `linkml validate -s <schema>.yaml --target-class Ancient <test_data>.csv`: checks that the schema can be used against an actual metadata test file

## Viewing interface generation (DataHarmonizer)

- [Install DataHarmonizer](https://github.com/cidgoh/DataHarmonizer?tab=readme-ov-file#prerequisites)
  - Clone the repo
  - Configure `corepack` so `yarn` works properly
  - Run `yarn` to install dependencies
- Make new schema entry
  - Delete the contents of `/web/templates/`
  - Make a directory `/web/templates/[schema name]/` for your new schema
  - In the directory create `export.json` just containing `export default {};`
  - Save a `schema.yaml` file in the directory, which is our schema, with an additional [`dh_interface` class](https://github.com/cidgoh/DataHarmonizer?tab=readme-ov-file#making-templates)
  - Generate the DataHarmonizer compatible JSON with `python ../../../script/linkml.py -i schema.yaml`
  - Modify the `/web/templates/menu.json` so all `display: false` equals `display: true`
- Run `yarn build:web` to generate a standalone file (Stored in `/web/dist`)
