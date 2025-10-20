# Term: Name of site or location where sample originated (site_name) 


_Designated name of the archaeological or ecological site, ancient settlement, or location etc. where the sample was originally collected. Can be a non-geographical name, such as a field-specific name or code, the official name of an excavation, or a colloquial name that is used in academic literature. Typically names that would not be found on official maps. Can also include different transliterations or languages used in the literature._



URI: [MIXS:999999933](https://w3id.org/mixs/999999933)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use site_name.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: *






## Examples

| Value |
| --- |
| Valley of the Kings |
| Krakow Spadzista B |
| Coopers Cave |
| Cutler Fossil Site |
| Kap København Formation |




### Annotations
* Expected_value: Name of site or location where sample was originated



## LinkML Source

<details>
```yaml
name: site_name
annotations:
  Expected_value:
    tag: Expected_value
    value: Name of site or location where sample was originated
description: Designated name of the archaeological or ecological site, ancient settlement,
  or location etc. where the sample was originally collected. Can be a non-geographical
  name, such as a field-specific name or code, the official name of an excavation,
  or a colloquial name that is used in academic literature. Typically names that would
  not be found on official maps. Can also include different transliterations or languages
  used in the literature.
title: Name of site or location where sample originated
examples:
- value: Valley of the Kings
- value: Krakow Spadzista B
- value: Coopers Cave
- value: Cutler Fossil Site
- value: Kap København Formation
in_subset:
- environment
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- environment
- sample
slot_uri: MIXS:999999933
alias: site_name
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: true

```
</details>