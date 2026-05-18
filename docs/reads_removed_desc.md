# Term: description of reads removal (reads_removed_desc) 


_Specify whether associated data was filtered in some form prior to upload, such as host reads removal. Detailed description of the the data filtering that was carried out should be described in term 'preprocessing of sequencing reads description'._



URI: [MIXS:999999946](https://w3id.org/mixs/999999946)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use reads_removed_desc.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [Boolean](Boolean.md)
* Cardinality: 0..1 _recommended_






## Examples

| Value |
| --- |
| no |
| yes |




### Annotations
* Expected_value: Whether any sequencing reads were removed from the data files after sequencing



## LinkML Source

<details>
```yaml
name: reads_removed_desc
annotations:
  Expected_value:
    tag: Expected_value
    value: Whether any sequencing reads were removed from the data files after sequencing
description: Specify whether associated data was filtered in some form prior to upload,
  such as host reads removal. Detailed description of the the data filtering that
  was carried out should be described in term 'preprocessing of sequencing reads description'.
title: description of reads removal
examples:
- value: 'no'
- value: 'yes'
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- data analysis
slot_uri: MIXS:999999946
alias: reads_removed_desc
domain_of:
- Ancient
range: boolean
required: false
recommended: true
multivalued: false

```
</details>