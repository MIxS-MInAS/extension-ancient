# Term: sample age range youngest unit (samp_age_range_youngest_unit) 


_The unit of the youngest age in the sample age range._



URI: [MIXS:999999919](https://w3id.org/mixs/999999919)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use samp_age_range_youngest_unit.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [SampAgeUnit](SampAgeUnit.md)
* Cardinality: 1..* _recommended_






## Examples

| Value |
| --- |
| cal BP |
| CE |
| Ma |





## LinkML Source

<details>
```yaml
name: samp_age_range_youngest_unit
description: The unit of the youngest age in the sample age range.
title: sample age range youngest unit
examples:
- value: cal BP
- value: CE
- value: Ma
in_subset:
- investigation
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:999999919
alias: samp_age_range_youngest_unit
domain_of:
- Ancient
range: SampAgeUnit
required: true
recommended: true
multivalued: true

```
</details>