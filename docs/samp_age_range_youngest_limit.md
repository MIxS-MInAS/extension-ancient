# Term: sample age range youngest limit (samp_age_range_youngest_limit) 


_The youngest possible age of the sample in years, with the specific year unit defined in samp_age_range_youngest_unit. Youngest refers to the time closest to present day. Sample age refers to a period of time in the past, such as when an organism was living and then died, not the biological age. If a sample has only a single age value use this value in both samp_age_range_oldest_limit and samp_age_range_youngest_limit. Specify a date that is as specific to the sample as possible (e.g. prefer direct dates over rough relative estimates). If the sample age is unknown, give a broad range in a reasonable timeframe and justify in samp_age_range_inference_description._



URI: [MIXS:999999918](https://w3id.org/mixs/999999918)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use samp_age_range_youngest_limit.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [Integer](Integer.md)
* Cardinality: 1 _recommended_






## Examples

| Value |
| --- |
| 100000 |
| 1700 |




### Annotations
* Expected_value: age value corresponding to unit



## LinkML Source

<details>
```yaml
name: samp_age_range_youngest_limit
annotations:
  Expected_value:
    tag: Expected_value
    value: age value corresponding to unit
description: The youngest possible age of the sample in years, with the specific year
  unit defined in samp_age_range_youngest_unit. Youngest refers to the time closest
  to present day. Sample age refers to a period of time in the past, such as when
  an organism was living and then died, not the biological age. If a sample has only
  a single age value use this value in both samp_age_range_oldest_limit and samp_age_range_youngest_limit.
  Specify a date that is as specific to the sample as possible (e.g. prefer direct
  dates over rough relative estimates). If the sample age is unknown, give a broad
  range in a reasonable timeframe and justify in samp_age_range_inference_description.
title: sample age range youngest limit
examples:
- value: '100000'
- value: '1700'
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:999999918
alias: samp_age_range_youngest_limit
domain_of:
- Ancient
range: integer
required: true
recommended: true

```
</details>