# Term: sample age inference description (samp_age_range_inference_description) 


_Additional general information about the inference method used to infer the sample age that can be useful for understanding how the sample age was estimated. This can be things such as whether radiocarbon age estimated on AMS or conventional radiocarbon dating, or which calibration confidence interval was used. It can also be used to describe what artefacts were used to age the stratigraphic layer of historical contexts. Include any relevant additional citations to the dating method here._



URI: [MIXS:999999923](https://w3id.org/mixs/999999923)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use samp_age_range_inference_description.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: 0..1 _recommended_






## Examples

| Value |
| --- |
| radiocarbon dating, calibrated with OxCal v4.3 with 95% confidence interval |
| based on proxy dating from other bone samples of stratigraphic layer |
| a coin found in the burial was from the 3rd century |
| age taken from previous publication Doe et al. 2019 |
| radiocarbon age ID: OxA-12345 |





## LinkML Source

<details>
```yaml
name: samp_age_range_inference_description
description: Additional general information about the inference method used to infer
  the sample age that can be useful for understanding how the sample age was estimated.
  This can be things such as whether radiocarbon age estimated on AMS or conventional
  radiocarbon dating, or which calibration confidence interval was used. It can also
  be used to describe what artefacts were used to age the stratigraphic layer of historical
  contexts. Include any relevant additional citations to the dating method here.
title: sample age inference description
examples:
- value: radiocarbon dating, calibrated with OxCal v4.3 with 95% confidence interval
- value: based on proxy dating from other bone samples of stratigraphic layer
- value: a coin found in the burial was from the 3rd century
- value: age taken from previous publication Doe et al. 2019
- value: 'radiocarbon age ID: OxA-12345'
in_subset:
- investigation
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:999999923
alias: samp_age_range_inference_description
domain_of:
- Ancient
range: string
required: false
recommended: true
multivalued: false

```
</details>