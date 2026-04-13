# Term: negative control status (neg_cont_status) 


_Specify whether the sample is a negative control or not._



URI: [MIXS:999999930](https://w3id.org/mixs/999999930)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use neg_cont_status.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [Boolean](Boolean.md)
* Cardinality: 1 _recommended_






## Examples

| Value |
| --- |
| true |
| false |





## LinkML Source

<details>
```yaml
name: neg_cont_status
description: Specify whether the sample is a negative control or not.
title: negative control status
examples:
- value: 'true'
- value: 'false'
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- control
slot_uri: MIXS:999999930
alias: neg_cont_status
domain_of:
- Ancient
range: boolean
required: true
recommended: true

```
</details>