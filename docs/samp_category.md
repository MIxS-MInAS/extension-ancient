# Term: sample category (samp_category) 


_The type/category of a sample. "Sample" includes biological and technical replicates._



URI: [MIXS:999999930](https://w3id.org/mixs/999999930)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use samp_category.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [SampCategoryEnum](SampCategoryEnum.md)
* Cardinality: 1 _recommended_






## Examples

| Value |
| --- |
| sample |
| negative control |
| positive control |





## LinkML Source

<details>
```yaml
name: samp_category
description: The type/category of a sample. "Sample" includes biological and technical
  replicates.
title: sample category
examples:
- value: sample
- value: negative control
- value: positive control
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- control
slot_uri: MIXS:999999930
alias: samp_category
domain_of:
- Ancient
range: SampCategoryEnum
required: true
recommended: true

```
</details>