# Term: library polymerase (lib_polymerase) 


_The polymerase enzyme used for building nucleic acid libraries._



URI: [MIXS:999999909](https://w3id.org/mixs/999999909)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use lib_polymerase.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: 0..1 _recommended_






## Examples

| Value |
| --- |
| Agilent PfuTurbo Cx HotStart |
| KAPA HiFi HotStart |
| AmpliTaq Gold DNA Polymerase |




### Annotations
* Expected_value: name of polymerase used during library construction



## LinkML Source

<details>
```yaml
name: lib_polymerase
annotations:
  Expected_value:
    tag: Expected_value
    value: name of polymerase used during library construction
description: The polymerase enzyme used for building nucleic acid libraries.
title: library polymerase
examples:
- value: Agilent PfuTurbo Cx HotStart
- value: KAPA HiFi HotStart
- value: AmpliTaq Gold DNA Polymerase
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- polymerase
- library
- preparation
string_serialization: '{text}'
slot_uri: MIXS:999999909
alias: lib_polymerase
domain_of:
- Ancient
range: string
required: false
recommended: true

```
</details>