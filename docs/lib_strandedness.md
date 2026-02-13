# Term: nucleic acid strandedness in library creation (lib_strandedness) 


_The strandedness of the original template nucleic acid molecules used for constructing the sequencing library_



URI: [MIXS:999999930](https://w3id.org/mixs/999999930)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use lib_strandedness.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [LibStrand](LibStrand.md)
* Cardinality: * _recommended_






## Examples

| Value |
| --- |
| single |
| double |




### Annotations
* Expected_value: nucleic acid library strandedness



## LinkML Source

<details>
```yaml
name: lib_strandedness
annotations:
  Expected_value:
    tag: Expected_value
    value: nucleic acid library strandedness
description: The strandedness of the original template nucleic acid molecules used
  for constructing the sequencing library
title: nucleic acid strandedness in library creation
examples:
- value: single
- value: double
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- library
- preparation
slot_uri: MIXS:999999930
alias: lib_strandedness
domain_of:
- Ancient
range: LibStrand
required: false
recommended: true
multivalued: true

```
</details>