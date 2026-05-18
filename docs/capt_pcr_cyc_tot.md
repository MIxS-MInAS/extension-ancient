# Term: post capture PCR reamplication cycles total (capt_pcr_cyc_tot) 


_Amplification cycles after capture enrichment total. Provide additional information about PCR conditions in pcr_cond_



URI: [MIXS:999999942](https://w3id.org/mixs/999999942)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use capt_pcr_cyc_tot.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [Integer](Integer.md)
* Cardinality: *






## Examples

| Value |
| --- |
| 12 |





## LinkML Source

<details>
```yaml
name: capt_pcr_cyc_tot
description: Amplification cycles after capture enrichment total. Provide additional
  information about PCR conditions in pcr_cond
title: post capture PCR reamplication cycles total
examples:
- value: '12'
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:999999942
alias: capt_pcr_cyc_tot
domain_of:
- Ancient
range: integer
required: false
recommended: false
multivalued: true

```
</details>