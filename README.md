# extension-ancient

A MIxS extension proposal for 'ancient DNA' samples.

## Repository Structure

The repo is layed out as follows:

- `feedback/`
  - `<date>-<eventid>`: contains collated tables from community feedback sessions
- `proposals/`
  - `<upcoming version>`: contains consensus term update proposals for inclusion in the next version of the standard
- `src/`
  - `yaml/`: contains the structured YAML files of the latest release of the extension
  - `json/`: contains the structured JSON files of the latest release the extension

## Technical notes

Use the YAML (in as far as possible similar format as MIxS LinkML structure) as the source of truth.

To generate the JSON version, install linkml

```bash
pip install linkml
```

And run the following command, assuming root of repo:

```bash
gen-json-schema src/yaml/ancient.yml > src/json/ancient.json
```

<!--

## Yaml mergeing

2031 yq -s '.[0] \* .[1]' /home/james/git/mixs-minas/mixs/src/mixs/schema/mixs.yaml ancient.yml > test.yml
2032 less test.yml
2033 cat test.yml | grep ancient
2034 cat test.yml | grep cultural_era
2035 cat test.yml | grep -n cultural_era
2036 cat test.yml | grep -n ancient
2037 less test.yml
2038 less -n test.yml
2039 less --help
2040 less -n test.yml
2041 gen-summary test.yml
2042 history
-->
