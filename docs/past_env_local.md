# Term: local past environmental context (past_env_local) 


_Report information about the smaller-scale environmental system of the local vicinity of the sample or specimen at the time of deposition or burial (e.g. in hillside, burial mound, or midden). This should not describe the environment as it is today (e.g. carpark), but specifically the entity or entities surrounding the sample that may have significant causal influences as it was in the past. Compared to `env_local_scale` which is taken from direct observation, the information about the past environment will normally be derived from inference from archaeological, palaeontological, geological, or other scientific methods. We recommend using EnvO terms which are of smaller than your entry for past_env_broad. Terms, such as anatomical sites, from other OBO Library ontologies which interoperate with EnvO (e.g. UBERON) are accepted in this field. EnvO documentation about how to use the field for present day equivalents: https://github.com/EnvironmentOntology/envo/wiki/Using-ENVO-with-MIxS"_



URI: [MIXS:0000999](https://w3id.org/mixs/0000999)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use past_env_local.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: 0..1 _recommended_






## Examples

| Value |
| --- |
| hillside [ENVO:01000333] |




### Annotations
* Expected_value: Report information about smaller environmental entities having causal influences upon the sample or specimen at/during the time of burial



## LinkML Source

<details>
```yaml
name: past_env_local
annotations:
  Expected_value:
    tag: Expected_value
    value: Report information about smaller environmental entities having causal influences
      upon the sample or specimen at/during the time of burial
description: 'Report information about the smaller-scale environmental system of the
  local vicinity of the sample or specimen at the time of deposition or burial (e.g.
  in hillside, burial mound, or midden). This should not describe the environment
  as it is today (e.g. carpark), but specifically the entity or entities surrounding
  the sample that may have significant causal influences as it was in the past. Compared
  to `env_local_scale` which is taken from direct observation, the information about
  the past environment will normally be derived from inference from archaeological,
  palaeontological, geological, or other scientific methods. We recommend using EnvO
  terms which are of smaller than your entry for past_env_broad. Terms, such as anatomical
  sites, from other OBO Library ontologies which interoperate with EnvO (e.g. UBERON)
  are accepted in this field. EnvO documentation about how to use the field for present
  day equivalents: https://github.com/EnvironmentOntology/envo/wiki/Using-ENVO-with-MIxS"'
title: local past environmental context
examples:
- value: hillside [ENVO:01000333]
in_subset:
- environment
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- context
- environmental
- ancient
string_serialization: '{termLabel} [{termID}]'
slot_uri: MIXS:0000999
alias: past_env_local
domain_of:
- Ancient
range: string
required: false
recommended: true

```
</details>