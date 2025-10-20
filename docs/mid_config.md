# Term: multiplex identifiers or indexing configuration of libraries (mid_config) 


_Index/barcode/primer configuration used during library building for sequencing. This includes information such as the number, type and location of indexes, the index/primer kit/list, or if 'inline' barcodes or UMIs were ligated directly onto the template molecules._



URI: [MIXS:999999933](https://w3id.org/mixs/999999933)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use mid_config.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: * _recommended_






## Examples

| Value |
| --- |
| dual index with single internal barcode. |
| UDI index sequences. |




### Annotations
* Expected_value: Description of the indexing configuration of the library



## LinkML Source

<details>
```yaml
name: mid_config
annotations:
  Expected_value:
    tag: Expected_value
    value: Description of the indexing configuration of the library
description: Index/barcode/primer configuration used during library building for sequencing.
  This includes information such as the number, type and location of indexes, the
  index/primer kit/list, or if 'inline' barcodes or UMIs were ligated directly onto
  the template molecules.
title: multiplex identifiers or indexing configuration of libraries
examples:
- value: dual index with single internal barcode.
- value: UDI index sequences.
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- library
- preparation
string_serialization: '{text}'
slot_uri: MIXS:999999933
alias: mid_config
domain_of:
- Ancient
range: string
required: false
recommended: true
multivalued: true

```
</details>