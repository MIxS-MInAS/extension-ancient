# Term: enrichment probe design description (genomic_capture_probe_desc) 


_Description of target enrichment probe designs used (e.g., species included, sequences, type, company). This can include custom kits (please provide a general description and DOI if available) or commercially available kit (provide ID and company)._



URI: [MIXS:999999931](https://w3id.org/mixs/999999931)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use genomic_capture_probe_desc.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: *






## Examples

| Value |
| --- |
| Custom probe design (70 bp biotinylated RNA probes) covering 500 full E. Coli genomes; company TE-Science |
| Commercial RNA baits kit ABC001-EC from company TE-Science, purchased 2020 |




### Annotations
* Expected_value: Description of probe set used for target enrichment/library selection (a.k.a. capture)



## LinkML Source

<details>
```yaml
name: genomic_capture_probe_desc
annotations:
  Expected_value:
    tag: Expected_value
    value: Description of probe set used for target enrichment/library selection (a.k.a.
      capture)
description: Description of target enrichment probe designs used (e.g., species included,
  sequences, type, company). This can include custom kits (please provide a general
  description and DOI if available) or commercially available kit (provide ID and
  company).
title: enrichment probe design description
examples:
- value: Custom probe design (70 bp biotinylated RNA probes) covering 500 full E.
    Coli genomes; company TE-Science
- value: Commercial RNA baits kit ABC001-EC from company TE-Science, purchased 2020
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- library
- enrichment
string_serialization: '{text}'
slot_uri: MIXS:999999931
alias: genomic_capture_probe_desc
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: true

```
</details>