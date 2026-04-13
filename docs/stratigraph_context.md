# Term: stratigraphic context (stratigraph_context) 


_Associated stratigraphic context(s) that the sample was retrieved from, usually from an archaeological or palaeontological excavation. Description(s) or identifier(s) of stratigraphic units or layer names within and/or relative to the site (e.g., stratigraphic unit ID, archaeological feature ID, layer name or a description, grid location)._



URI: [MIXS:999999907](https://w3id.org/mixs/999999907)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use stratigraph_context.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [String](String.md)
* Cardinality: *






## Examples

| Value |
| --- |
| Layer 5 |
| Layer UE |
| Horizon IIc, Quadrant 77 |
| HF_23447_77_410_IIc |
| KrSp C2/2011/B5 |
| US10 |
| YSL |
| Subunit 1 |
| Black Mousterian (BM) |




### Annotations
* Expected_value: Stratigraphic context that the sample was retrieved from



## LinkML Source

<details>
```yaml
name: stratigraph_context
annotations:
  Expected_value:
    tag: Expected_value
    value: Stratigraphic context that the sample was retrieved from
description: Associated stratigraphic context(s) that the sample was retrieved from,
  usually from an archaeological or palaeontological excavation. Description(s) or
  identifier(s) of stratigraphic units or layer names within and/or relative to the
  site (e.g., stratigraphic unit ID, archaeological feature ID, layer name or a description,
  grid location).
title: stratigraphic context
examples:
- value: Layer 5
- value: Layer UE
- value: Horizon IIc, Quadrant 77
- value: HF_23447_77_410_IIc
- value: KrSp C2/2011/B5
- value: US10
- value: YSL
- value: Subunit 1
- value: Black Mousterian (BM)
in_subset:
- environment
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- identifiers
- excavation
slot_uri: MIXS:999999907
alias: stratigraph_context
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: true

```
</details>