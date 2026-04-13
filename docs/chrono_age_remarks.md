# Term: Chronometric Age Remarks (chrono_age_remarks) 


_Notes or comments about the  earliest_chrono_age and latest_chrono_age. For more detail use Chronometric Age Protocol to point to original publication describing method. Useful to specify confidence and/or accuracy of reported date._



URI: [MIXS:999999927](https://w3id.org/mixs/999999927)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use chrono_age_remarks.

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
| a coin found in the burial was from the 3rd century was found in the mouth of the skeleton |
| age taken from previous publication Doe et al. 2019 |
| radiocarbon age ID: OxA-12345 |





## LinkML Source

<details>
```yaml
name: chrono_age_remarks
description: Notes or comments about the  earliest_chrono_age and latest_chrono_age.
  For more detail use Chronometric Age Protocol to point to original publication describing
  method. Useful to specify confidence and/or accuracy of reported date.
title: Chronometric Age Remarks
examples:
- value: radiocarbon dating, calibrated with OxCal v4.3 with 95% confidence interval
- value: based on proxy dating from other bone samples of stratigraphic layer
- value: a coin found in the burial was from the 3rd century was found in the mouth
    of the skeleton
- value: age taken from previous publication Doe et al. 2019
- value: 'radiocarbon age ID: OxA-12345'
in_subset:
- investigation
from_schema: https://w3id.org/mixs
close_mappings:
- chrono:chronometricAgeRemarks
rank: 1000
slot_uri: MIXS:999999927
alias: chrono_age_remarks
domain_of:
- Ancient
range: string
required: false
recommended: true
multivalued: false

```
</details>