# Term: biocultural label (biocultural_label) 


_Relevant biocultural labels defined by the local contexts project (https://localcontexts.org/label/bc-provenance/) that describe in what ways this data can be reused, as permitted by any associated native or indigenous peoples or communities._



URI: [MIXS:999999914](https://w3id.org/mixs/999999914)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use biocultural_label.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [BioCulturalLabelEnum](BioCulturalLabelEnum.md)
* Cardinality: * _recommended_






## Examples

| Value |
| --- |
| BC R |
| BC MC |
| BC MC;BC CV |




### Annotations
* Expected_value: Relevant biocultural label from https://localcontexts.org/labels/biocultural-labels/



## LinkML Source

<details>
```yaml
name: biocultural_label
annotations:
  Expected_value:
    tag: Expected_value
    value: Relevant biocultural label from https://localcontexts.org/labels/biocultural-labels/
description: Relevant biocultural labels defined by the local contexts project (https://localcontexts.org/label/bc-provenance/)
  that describe in what ways this data can be reused, as permitted by any associated
  native or indigenous peoples or communities.
title: biocultural label
examples:
- value: BC R
- value: BC MC
- value: BC MC;BC CV
in_subset:
- ethics
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- ethics
slot_uri: MIXS:999999914
alias: biocultural_label
domain_of:
- Ancient
range: BioCulturalLabelEnum
required: false
recommended: true
multivalued: true

```
</details>