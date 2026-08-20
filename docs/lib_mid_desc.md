# Term: description of library multiplex identifiers or indexing configuration (lib_mid_desc) 


_Index/barcode/primer configuration used during library building for sequencing. This includes information such as the number, type and location of indexes, the index/primer kit/list, or if 'inline' barcodes or UMIs were ligated directly onto the template molecules._



URI: [MIXS:0001388](https://w3id.org/mixs/0001388)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use lib_mid_desc.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



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
name: lib_mid_desc
annotations:
  Expected_value:
    tag: Expected_value
    value: Description of the indexing configuration of the library
description: Index/barcode/primer configuration used during library building for sequencing.
  This includes information such as the number, type and location of indexes, the
  index/primer kit/list, or if 'inline' barcodes or UMIs were ligated directly onto
  the template molecules.
title: description of library multiplex identifiers or indexing configuration
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
slot_uri: MIXS:0001388
domain_of:
- Ancient
range: string
required: false
recommended: true
multivalued: true

```
</details>