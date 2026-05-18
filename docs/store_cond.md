# Term: storage conditions (store_cond) 


_Explain how and for how long the sample was stored before DNA extraction (for example, fresh/frozen/other). Include factors that may influence nucleic acid recovery or library construction. For example, specify temperature, humidity, presence of microbial overgrowth etc.._



URI: [MIXS:0000327](https://w3id.org/mixs/0000327)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use store_cond.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [String](String.md)
* Cardinality: 0..1

* Structured pattern: `^{storage_condition_type};{duration}$`






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
name: store_cond
description: Explain how and for how long the sample was stored before DNA extraction
  (for example, fresh/frozen/other). Include factors that may influence nucleic acid
  recovery or library construction. For example, specify temperature, humidity, presence
  of microbial overgrowth etc..
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
keywords:
- condition
- storage
slot_uri: MIXS:0000327
alias: store_cond
domain_of:
- Ancient
range: string
structured_pattern:
  syntax: ^{storage_condition_type};{duration}$

```
</details>