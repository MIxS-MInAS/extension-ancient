# Term: Damage treatment type (damage_treatment) 


_Indication of whether characteristic ancient DNA damage has been  altered or removed from a DNA extract in a laboratory_



URI: [MIXS:999999903](https://w3id.org/mixs/999999903)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use damage_treatment.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [DamageTreatmentEnum](DamageTreatmentEnum.md)
* Cardinality: 1..*






## Examples

| Value |
| --- |
| none |
| partial-removal |




### Annotations
* Expected_value: enumeration



## LinkML Source

<details>
```yaml
name: damage_treatment
annotations:
  Expected_value:
    tag: Expected_value
    value: enumeration
description: Indication of whether characteristic ancient DNA damage has been  altered
  or removed from a DNA extract in a laboratory
title: Damage treatment type
examples:
- value: none
- value: partial-removal
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- ancient
slot_uri: MIXS:999999903
alias: damage_treatment
domain_of:
- Ancient
range: DamageTreatmentEnum
required: true
multivalued: true

```
</details>