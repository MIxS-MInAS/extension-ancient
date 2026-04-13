# Term: Name of site or location where sample originated (orig_site_name) 


_Designated name of the archaeological or ecological site, ancient settlement, or location etc. where the sample was originally collected. Can be a non-geographical name, such as a field-specific name or code, the official name of an excavation, or a colloquial name that is used in academic literature. Typically names that would not be found on official maps. If the site name is unclear please use the name of the closest location or region as best as possible. Can also include different transliterations or languages used in the literature._



URI: [MIXS:999999901](https://w3id.org/mixs/999999901)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use orig_site_name.

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
| Valley of the Kings |
| Krakow Spadzista B |
| Coopers Cave |
| Cutler Fossil Site |
| Kap København Formation |
| Northern Italy, Lombardy, exact location unknown |




### Annotations
* Expected_value: Name of site or location where sample was originated



## LinkML Source

<details>
```yaml
name: orig_site_name
annotations:
  Expected_value:
    tag: Expected_value
    value: Name of site or location where sample was originated
description: Designated name of the archaeological or ecological site, ancient settlement,
  or location etc. where the sample was originally collected. Can be a non-geographical
  name, such as a field-specific name or code, the official name of an excavation,
  or a colloquial name that is used in academic literature. Typically names that would
  not be found on official maps. If the site name is unclear please use the name of
  the closest location or region as best as possible. Can also include different transliterations
  or languages used in the literature.
title: Name of site or location where sample originated
examples:
- value: Valley of the Kings
- value: Krakow Spadzista B
- value: Coopers Cave
- value: Cutler Fossil Site
- value: Kap København Formation
- value: Northern Italy, Lombardy, exact location unknown
in_subset:
- environment
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- environment
- sample
slot_uri: MIXS:999999901
alias: orig_site_name
domain_of:
- Ancient
range: string
required: false
recommended: true
multivalued: true

```
</details>