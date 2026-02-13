# Term: permit or approval ID (permit_id) 


_A permit ID, code, or any form of identify provided by any authority (ethical, local, legal, academic etc.) associated with the approval of the analysis of this particular sample, if available._



URI: [MIXS:999999906](https://w3id.org/mixs/999999906)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use permit_id.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: * _recommended_






## Examples

| Value |
| --- |
| DE-123-JK |





## LinkML Source

<details>
```yaml
name: permit_id
description: A permit ID, code, or any form of identify provided by any authority
  (ethical, local, legal, academic etc.) associated with the approval of the analysis
  of this particular sample, if available.
title: permit or approval ID
examples:
- value: DE-123-JK
in_subset:
- investigation
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- ethics
slot_uri: MIXS:999999906
alias: permit_id
domain_of:
- Ancient
range: string
required: false
recommended: true
multivalued: true

```
</details>