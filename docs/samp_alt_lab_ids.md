# Term: alternative sample IDs (samp_alt_lab_ids) 


_An alternative sample or material IDs related to the sample not already covered by terms samp_name and source_mat_id, including from associated other non-genetic analyses of the same sample (e.g. museum IDs, internal lab sample ID from sampling such a bone drilling). Can be specified multiple times for different ID contexts._



URI: [MIXS:999999924](https://w3id.org/mixs/999999924)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use samp_alt_lab_ids.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: *






## Examples

| Value |
| --- |
| ABC_24 |
| Grave 6 |
| Museum ID: NHM_AR_123, Drilling ID: DRL_001, Extraction ID: ABC_24 |





## LinkML Source

<details>
```yaml
name: samp_alt_lab_ids
description: An alternative sample or material IDs related to the sample not already
  covered by terms samp_name and source_mat_id, including from associated other non-genetic
  analyses of the same sample (e.g. museum IDs, internal lab sample ID from sampling
  such a bone drilling). Can be specified multiple times for different ID contexts.
title: alternative sample IDs
examples:
- value: ABC_24
- value: Grave 6
- value: 'Museum ID: NHM_AR_123, Drilling ID: DRL_001, Extraction ID: ABC_24'
in_subset:
- investigation
from_schema: https://w3id.org/mixs
rank: 1000
string_serialization: '{text}'
slot_uri: MIXS:999999924
alias: samp_alt_lab_ids
domain_of:
- Ancient
range: string
multivalued: true

```
</details>