# Term: Data filtering applied (data_filt_applied) 


_Specify whether associated data was filtered prior to upload, such as host reads removal._



URI: [MIXS:999999933](https://w3id.org/mixs/999999933)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use data_filt_applied.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [Boolean](Boolean.md)
* Cardinality: 0..1 _recommended_






## Examples

| Value |
| --- |
| no |
| yes |




### Annotations
* Expected_value: Whether associated data was filtered



## LinkML Source

<details>
```yaml
name: data_filt_applied
annotations:
  Expected_value:
    tag: Expected_value
    value: Whether associated data was filtered
description: Specify whether associated data was filtered prior to upload, such as
  host reads removal.
title: Data filtering applied
examples:
- value: 'no'
- value: 'yes'
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- data analysis
slot_uri: MIXS:999999933
alias: data_filt_applied
domain_of:
- Ancient
range: boolean
required: false
recommended: true
multivalued: false

```
</details>