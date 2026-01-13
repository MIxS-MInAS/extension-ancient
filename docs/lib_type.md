# Term: library type (lib_type) 


_The type of library created, i.e., amplicon, enriched, or shotgun. An amplicon library is a library that has been amplified to target a single specific region of a genome (e.g. a specific gene).  An enriched library is a library has had a particular genome, or multiple genomic regions/positions 'captured' or enriched typically via baits/probes. A shotgun library has undergone no type of targeted amplification/enrichment for a particular genomic region or genome, i.e., random sequencing of any nucleic acid molecule contained in a genomic library._



URI: [MIXS:999999910](https://w3id.org/mixs/999999910)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use lib_type.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




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
name: lib_type
description: The type of library created, i.e., amplicon, enriched, or shotgun. An
  amplicon library is a library that has been amplified to target a single specific
  region of a genome (e.g. a specific gene).  An enriched library is a library has
  had a particular genome, or multiple genomic regions/positions 'captured' or enriched
  typically via baits/probes. A shotgun library has undergone no type of targeted
  amplification/enrichment for a particular genomic region or genome, i.e., random
  sequencing of any nucleic acid molecule contained in a genomic library.
title: library type
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
slot_uri: MIXS:999999910
alias: lib_type
domain_of:
- Ancient
range: LibTypeEnum
required: false
recommended: true

```
</details>