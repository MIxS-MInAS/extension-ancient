# Term: Genomic capture probe source taxonomy IDs (capt_probe_src_taxid) 


_NCBI taxon ID(s) of all organisms included in the baits of a whole organelle or whole genome-level capture panel. There should be an (ideally) species level taxonomic ID entry for each organism that had sequences included in the design. If whole genera were targeted, you can instead use a single genus level taxonomic ID or that of any relevant higher taxonomic unit._



URI: [MIXS:999999943](https://w3id.org/mixs/999999943)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use capt_probe_src_taxid.

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
| 9606 |
| 632 |
| 9789 |




### Annotations
* Expected_value: Taxonomic IDs corresponding to organism(s) included in target enrichment (a.k.a. capture) probe design



## LinkML Source

<details>
```yaml
name: capt_probe_src_taxid
annotations:
  Expected_value:
    tag: Expected_value
    value: Taxonomic IDs corresponding to organism(s) included in target enrichment
      (a.k.a. capture) probe design
description: NCBI taxon ID(s) of all organisms included in the baits of a whole organelle
  or whole genome-level capture panel. There should be an (ideally) species level
  taxonomic ID entry for each organism that had sequences included in the design.
  If whole genera were targeted, you can instead use a single genus level taxonomic
  ID or that of any relevant higher taxonomic unit.
title: Genomic capture probe source taxonomy IDs
examples:
- value: '9606'
- value: '632'
- value: '9789'
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- sequencing
- library
- enrichment
- capture
slot_uri: MIXS:999999943
alias: capt_probe_src_taxid
domain_of:
- Ancient
range: integer
required: false
recommended: false
multivalued: true

```
</details>