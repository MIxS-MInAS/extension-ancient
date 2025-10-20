# Term: sample age inference methods (samp_age_range_inference_methods) 


_The method used to infer the sample age. This corresponds to a fixed list of most commonly used dating methods, such as radiocarbon dating, optically stimulated infrared luminescence, associated absolute dating (e.g. directly dated bone in same context), contextual dating (e.g. stratigraphic inference, or coin), historical records, other etc.). If the method is not in the list, please provide a description in samp_age_range_inference_description._



URI: [MIXS:999999922](https://w3id.org/mixs/999999922)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use samp_age_range_inference_methods.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [SampAgeInferMethod](SampAgeInferMethod.md)
* Cardinality: * _recommended_






## Examples

| Value |
| --- |
| radiocarbon dating |
| optically stimulated infrared luminescence |
| contextual dating |
| historical records |





## LinkML Source

<details>
```yaml
name: samp_age_range_inference_methods
description: The method used to infer the sample age. This corresponds to a fixed
  list of most commonly used dating methods, such as radiocarbon dating, optically
  stimulated infrared luminescence, associated absolute dating (e.g. directly dated
  bone in same context), contextual dating (e.g. stratigraphic inference, or coin),
  historical records, other etc.). If the method is not in the list, please provide
  a description in samp_age_range_inference_description.
title: sample age inference methods
examples:
- value: radiocarbon dating
- value: optically stimulated infrared luminescence
- value: contextual dating
- value: historical records
in_subset:
- investigation
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:999999922
alias: samp_age_range_inference_methods
domain_of:
- Ancient
range: SampAgeInferMethod
required: false
recommended: true
multivalued: true

```
</details>