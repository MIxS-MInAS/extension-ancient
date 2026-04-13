# Term: sample depth in column (column_sample_depth) 


_Distance relative to the top or beginning of the sediment core or stratigraphic sequence (defined by the term 'depth') from which the sample was taken. This is not necessarily the same as the depth from floor level or Mean Sea Level (MSL) (which should be defined using the term: depth), as a core could start part way below the surface. Can also be a range if the depth of the sample is not precisely measured._



URI: [MIXS:999999908](https://w3id.org/mixs/999999908)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use column_sample_depth.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [String](String.md)
* Cardinality: 0..1

* Structured pattern: `^{scientific_float}( *- *{scientific_float})? *{text}$`






## Examples

| Value |
| --- |
| 34 cm |
| 23 - 56 cm |
| 100 in |




### Annotations
* Expected_value: depth of the sample in the column of a stratigraphy or sediment core



## LinkML Source

<details>
```yaml
name: column_sample_depth
annotations:
  Expected_value:
    tag: Expected_value
    value: depth of the sample in the column of a stratigraphy or sediment core
description: 'Distance relative to the top or beginning of the sediment core or stratigraphic
  sequence (defined by the term ''depth'') from which the sample was taken. This is
  not necessarily the same as the depth from floor level or Mean Sea Level (MSL) (which
  should be defined using the term: depth), as a core could start part way below the
  surface. Can also be a range if the depth of the sample is not precisely measured.'
title: sample depth in column
examples:
- value: 34 cm
- value: 23 - 56 cm
- value: 100 in
in_subset:
- environment
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- environment
- core
- sediment
slot_uri: MIXS:999999908
alias: column_sample_depth
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: false
structured_pattern:
  syntax: ^{scientific_float}( *- *{scientific_float})? *{text}$
  interpolated: true
  partial_match: true

```
</details>