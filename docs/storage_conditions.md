# Term: storage conditions (storage_conditions) 


_General conditions in which the material (before sampling for nucleic acid analysis) was stored in long-term collection storage, that may influenced nucleic acid recovery or library construction. For example, specify temperature, humidity, presence of microbial overgrowth etc.._



URI: [MIXS:999999925](https://w3id.org/mixs/999999925)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use storage_conditions.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: 0..1






## Examples

| Value |
| --- |
| climate-controlled |
| Stored in the museum from recovery_date to collection_date |
| Stored at -20oC until nuc_acid_extraction_date |





## LinkML Source

<details>
```yaml
name: storage_conditions
description: General conditions in which the material (before sampling for nucleic
  acid analysis) was stored in long-term collection storage, that may influenced nucleic
  acid recovery or library construction. For example, specify temperature, humidity,
  presence of microbial overgrowth etc..
title: storage conditions
examples:
- value: climate-controlled
- value: Stored in the museum from recovery_date to collection_date
- value: Stored at -20oC until nuc_acid_extraction_date
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
string_serialization: '{text}'
slot_uri: MIXS:999999925
alias: storage_conditions
domain_of:
- Ancient
range: string

```
</details>