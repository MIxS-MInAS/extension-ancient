# Term: Institution storing or archiving the source material (source_mat_curat_insti) 


_Name of the institutions, archives, or repositories that typically store or archive the specimen or object that was sampled for nucleic acid extraction. Typically will be the 'owning institution'. Multiple responsible or relevant institutions can be specified, for the purpose of requesting access to the original source material._



URI: [MIXS:999999901](https://w3id.org/mixs/999999901)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use source_mat_curat_insti.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: * _recommended_






## Examples

| Value |
| --- |
| Natural History Museum London |
| Denkmalpflege Baden-Württemberg, University of Tübingen |
| Herbarium, Royal Botanic Gardens, Kew |




### Annotations
* Expected_value: name of typical storage or archiving institution



## LinkML Source

<details>
```yaml
name: source_mat_curat_insti
annotations:
  Expected_value:
    tag: Expected_value
    value: name of typical storage or archiving institution
description: Name of the institutions, archives, or repositories that typically store
  or archive the specimen or object that was sampled for nucleic acid extraction.
  Typically will be the 'owning institution'. Multiple responsible or relevant institutions
  can be specified, for the purpose of requesting access to the original source material.
title: Institution storing or archiving the source material
examples:
- value: Natural History Museum London
- value: Denkmalpflege Baden-Württemberg, University of Tübingen
- value: Herbarium, Royal Botanic Gardens, Kew
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- storage
slot_uri: MIXS:999999901
alias: source_mat_curat_insti
domain_of:
- Ancient
range: string
required: false
recommended: true
multivalued: true

```
</details>