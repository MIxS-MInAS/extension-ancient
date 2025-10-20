# Term: broad-scale past environmental context (past_env_broad) 


_Report information about the general ancient broad environmental system that the sample or specimen existed or lived within, as it was at the time of deposition or burial (e.g. in the desert or a forest). This should not describe the environment as it is today (e.g. farmland), but specifically the state as it was in the past (i.e. the palaeo- or (pre)historical ecosystem). Compared to `env_broad_scale` which is taken from direct observation, the information about the past environment will normally be derived from inference from archaeological, palaeontological, geological, or other scientific methods. We recommend using subclasses of EnvO s biome class:  http://purl.obolibrary.org/obo/ENVO_00000428. EnvO documentation about how to use the field for present day equivalents: https://github.com/EnvironmentOntology/envo/wiki/Using-ENVO-with-MIxS"_



URI: [MIXS:0099999](https://w3id.org/mixs/0099999)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use past_env_broad.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: 0..1 _recommended_

* Structured pattern: `^{termLabel} \[{termID}\]$`

* Regex pattern: `^([^\s-]{1,2}|[^\s-]+.+[^\s-]+) \[[a-zA-Z]{2,}:[a-zA-Z0-9]\d+\]$`






## Examples

| Value |
| --- |
| dessert biome [ENVO:01000247] |





## LinkML Source

<details>
```yaml
name: past_env_broad
description: 'Report information about the general ancient broad environmental system
  that the sample or specimen existed or lived within, as it was at the time of deposition
  or burial (e.g. in the desert or a forest). This should not describe the environment
  as it is today (e.g. farmland), but specifically the state as it was in the past
  (i.e. the palaeo- or (pre)historical ecosystem). Compared to `env_broad_scale` which
  is taken from direct observation, the information about the past environment will
  normally be derived from inference from archaeological, palaeontological, geological,
  or other scientific methods. We recommend using subclasses of EnvO s biome class:  http://purl.obolibrary.org/obo/ENVO_00000428.
  EnvO documentation about how to use the field for present day equivalents: https://github.com/EnvironmentOntology/envo/wiki/Using-ENVO-with-MIxS"'
title: broad-scale past environmental context
examples:
- value: dessert biome [ENVO:01000247]
in_subset:
- environment
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- context
- environmental
- ancient
slot_uri: MIXS:0099999
alias: past_env_broad
domain_of:
- Ancient
range: string
required: false
recommended: true
pattern: ^([^\s-]{1,2}|[^\s-]+.+[^\s-]+) \[[a-zA-Z]{2,}:[a-zA-Z0-9]\d+\]$
structured_pattern:
  syntax: ^{termLabel} \[{termID}\]$
  interpolated: true
  partial_match: true

```
</details>