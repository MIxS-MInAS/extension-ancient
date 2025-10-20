# Term: preservational treatment (preservational_treatment) 


_Description of any treatment applied to samples for the purpose of  maximising collection preservation that may influence downstream  nucleic acid recovery or library construction, such as storage fluid or  reconstructive glue_



URI: [MIXS:999999914](https://w3id.org/mixs/999999914)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use preservational_treatment.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: *






## Examples

| Value |
| --- |
| stored in formalin |





## LinkML Source

<details>
```yaml
name: preservational_treatment
description: Description of any treatment applied to samples for the purpose of  maximising
  collection preservation that may influence downstream  nucleic acid recovery or
  library construction, such as storage fluid or  reconstructive glue
title: preservational treatment
examples:
- value: stored in formalin
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- ancient
string_serialization: '{text}'
slot_uri: MIXS:999999914
alias: preservational_treatment
domain_of:
- Ancient
range: string
multivalued: true

```
</details>