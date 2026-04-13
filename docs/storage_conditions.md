# Term: storage conditions (storage_conditions) 


_General surrounding environmental conditions where the material was stored in long-term collection storage prior sampling for nucleic acid analysis  that may influence nucleic acid recovery or library construction. For example, specify temperature, humidity, presence of microbial overgrowth etc.._



URI: [MIXS:999999918](https://w3id.org/mixs/999999918)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use storage_conditions.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [String](String.md)
* Cardinality: 0..1






## Examples

| Value |
| --- |
| climate-controlled |
| Mould growth in storage box observed |
| Stored at -20oC until 2025-05-15 |
| Stored in the museum from 1924 to 2021 |





## LinkML Source

<details>
```yaml
name: storage_conditions
description: General surrounding environmental conditions where the material was stored
  in long-term collection storage prior sampling for nucleic acid analysis  that may
  influence nucleic acid recovery or library construction. For example, specify temperature,
  humidity, presence of microbial overgrowth etc..
title: storage conditions
examples:
- value: climate-controlled
- value: Mould growth in storage box observed
- value: Stored at -20oC until 2025-05-15
- value: Stored in the museum from 1924 to 2021
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
string_serialization: '{text}'
slot_uri: MIXS:999999918
alias: storage_conditions
domain_of:
- Ancient
range: string
required: false
recommended: false

```
</details>