# Term: number of reamplification cycles (num_reamp_cycles) 


_Number of amplification cycles after library indexing PCR. If capture data, this refers to amplifications prior to the capture experiments._



URI: [MIXS:999999913](https://w3id.org/mixs/999999913)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use num_reamp_cycles.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [Integer](Integer.md)
* Cardinality: 0..1






## Examples

| Value |
| --- |
| 12 |





## LinkML Source

<details>
```yaml
name: num_reamp_cycles
description: Number of amplification cycles after library indexing PCR. If capture
  data, this refers to amplifications prior to the capture experiments.
title: number of reamplification cycles
examples:
- value: '12'
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:999999913
alias: num_reamp_cycles
domain_of:
- Ancient
range: integer

```
</details>