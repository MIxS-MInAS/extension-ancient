# Term: geological epoch (geological_epoch) 


_The geological epoch approximating to the period within which the specimen or sample existed. Where possible use terms from ontologies._



URI: [MIXS:999999902](https://w3id.org/mixs/999999902)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use geological_epoch.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
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
description: The geological epoch approximating to the period within which the specimen
  or sample existed. Where possible use terms from ontologies.
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
string_serialization: '{termLabel} [{termID}]|{text}'
slot_uri: MIXS:999999902
alias: geological_epoch
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: false

```
</details>