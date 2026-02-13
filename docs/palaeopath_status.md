# Term: palaeopathology status (palaeopath_status) 


_Describe briefly any relevant palaeopathological or health-related observations of the remains of the individual under study._



URI: [MIXS:999999926](https://w3id.org/mixs/999999926)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use palaeopath_status.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: 0..1






## Examples

| Value |
| --- |
| Osteoporosis. |
| Parasites found in pelvic area. |
| Caries on right upper molar. |




### Annotations
* Expected_value: description of health related observation on ancient remains



## LinkML Source

<details>
```yaml
name: palaeopath_status
annotations:
  Expected_value:
    tag: Expected_value
    value: description of health related observation on ancient remains
description: Describe briefly any relevant palaeopathological or health-related observations
  of the remains of the individual under study.
title: palaeopathology status
examples:
- value: Osteoporosis.
- value: Parasites found in pelvic area.
- value: Caries on right upper molar.
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- palaeopathology
- host health
- ancient
string_serialization: '{text}'
slot_uri: MIXS:999999926
alias: palaeopath_status
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: false

```
</details>