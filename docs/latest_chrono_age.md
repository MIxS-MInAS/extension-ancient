# Term: Latest Chronometric Age (latest_chrono_age) 


_The minimum/latest/youngest possible age of a specimen as determined by a dating method. If multiple dating measurements available, use the most latest/youngest date to provide widest range of age possibilities. The specific age unit should be specified by the term latest_chrono_sys. More information on specific dates (e.g. radiocarbon lab codes) can be specified in the term chrono_age_remarks._



URI: [MIXS:999999924](https://w3id.org/mixs/999999924)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use latest_chrono_age.

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
name: latest_chrono_age
annotations:
  Expected_value:
    tag: Expected_value
    value: age value corresponding to unit
description: The minimum/latest/youngest possible age of a specimen as determined
  by a dating method. If multiple dating measurements available, use the most latest/youngest
  date to provide widest range of age possibilities. The specific age unit should
  be specified by the term latest_chrono_sys. More information on specific dates (e.g.
  radiocarbon lab codes) can be specified in the term chrono_age_remarks.
title: Latest Chronometric Age
examples:
- value: '100000'
- value: '1700'
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
broad_mappings:
- chrono:latestChronometricAge
rank: 1000
slot_uri: MIXS:999999924
alias: latest_chrono_age
domain_of:
- Ancient
range: integer
required: true
recommended: true
multivalued: false

```
</details>