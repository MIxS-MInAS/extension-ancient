# Term: library generation technique (lib_gener_technique) 


_The technique used to generate the library, i.e., amplicon, enriched, or shotgun. An amplicon library is a library that has been amplified to target a single specific region of a genome (e.g. a specific gene). An enriched library is a library that has had a particular genome or multiple genomic regions/positions 'captured' or enriched typically via baits/probes. A shotgun library has undergone no type of targeted amplification/enrichment for a particular genomic region or genome, i.e., random sequencing of any nucleic acid molecule contained in a genomic library._



URI: [MIXS:999999939](https://w3id.org/mixs/999999939)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use lib_gener_technique.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [LibTypeEnum](LibTypeEnum.md)
* Cardinality: 0..1 _recommended_






## Examples

| Value |
| --- |
| shotgun |
| amplicon |
| enriched |





## LinkML Source

<details>
```yaml
name: lib_gener_technique
description: The technique used to generate the library, i.e., amplicon, enriched,
  or shotgun. An amplicon library is a library that has been amplified to target a
  single specific region of a genome (e.g. a specific gene). An enriched library is
  a library that has had a particular genome or multiple genomic regions/positions
  'captured' or enriched typically via baits/probes. A shotgun library has undergone
  no type of targeted amplification/enrichment for a particular genomic region or
  genome, i.e., random sequencing of any nucleic acid molecule contained in a genomic
  library.
title: library generation technique
examples:
- value: shotgun
- value: amplicon
- value: enriched
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- library
- preparation
slot_uri: MIXS:999999939
alias: lib_gener_technique
domain_of:
- Ancient
range: LibTypeEnum
required: false
recommended: true

```
</details>