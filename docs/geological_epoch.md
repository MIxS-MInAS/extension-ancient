# Term: geological epoch (geological_epoch) 


_The geological epoch approximating to the period within which the specimen or sample existed. Where possible use terms from ontologies. NOTE: This term is for geological timescales. For more precise or anthropogenic defined periods, use `Cultural Era`._



URI: [MIXS:999999921](https://w3id.org/mixs/999999921)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use geological_epoch.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [GeolEpochEnum](GeolEpochEnum.md)
* Cardinality: 0..1






## Examples

| Value |
| --- |
| Pleistocene |
| Upper Cretaceous |
| Pliocene |




### Annotations
* Expected_value: ontology term; text



## LinkML Source

<details>
```yaml
name: geological_epoch
annotations:
  Expected_value:
    tag: Expected_value
    value: ontology term; text
description: 'The geological epoch approximating to the period within which the specimen
  or sample existed. Where possible use terms from ontologies. NOTE: This term is
  for geological timescales. For more precise or anthropogenic defined periods, use
  `Cultural Era`.'
title: geological epoch
examples:
- value: Pleistocene
- value: Upper Cretaceous
- value: Pliocene
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- ancient
- age
slot_uri: MIXS:999999921
alias: geological_epoch
domain_of:
- Ancient
range: GeolEpochEnum
required: false
recommended: false
multivalued: false

```
</details>