# Term: negative control status (neg_cont_status) 


_Specify whether the sample is a negative control or not._



URI: [MIXS:999999911](https://w3id.org/mixs/999999911)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use neg_cont_status.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [Boolean](Boolean.md)
* Cardinality: 0..1






## Examples

| Value |
| --- |
| true |





## LinkML Source

<details>
```yaml
name: neg_cont_status
description: Specify whether the sample is a negative control or not.
title: negative control status
examples:
- value: 'true'
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- control
slot_uri: MIXS:999999911
alias: neg_cont_status
domain_of:
- Ancient
range: boolean

```
</details>