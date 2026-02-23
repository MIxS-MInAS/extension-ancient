# Term: library name (library_name) 


_Any ID or name used for referring to a nucleic acid sequencing library associated with the sample._



URI: [MIXS:999999933](https://w3id.org/mixs/999999933)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use library_name.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: * _recommended_






## Examples

| Value |
| --- |
| JK1234 |
| JFC001.A0101 |
| A003-1-SG1 |




### Annotations
* Expected_value: name of sequencing library



## LinkML Source

<details>
```yaml
name: library_name
annotations:
  Expected_value:
    tag: Expected_value
    value: name of sequencing library
description: Any ID or name used for referring to a nucleic acid sequencing library
  associated with the sample.
title: library name
examples:
- value: JK1234
- value: JFC001.A0101
- value: A003-1-SG1
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- sequencing
slot_uri: MIXS:999999933
alias: library_name
domain_of:
- Ancient
range: string
required: false
recommended: true
multivalued: true

```
</details>