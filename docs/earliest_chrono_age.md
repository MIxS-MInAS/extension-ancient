# Term: Earliest Chronometric Age (earliest_chrono_age) 


_The maximum/earliest/oldest possible age of a specimen as determined by a dating method. If multiple dating measurements available, use the most earliest/oldest date to provide widest range of age possibilities. The specific age unit should be specified by the term earliest_chrono_sys. More information on specific dates (e.g. radiocarbon lab codes) can be specified in the term chrono_age_remarks._



URI: [MIXS:999999922](https://w3id.org/mixs/999999922)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use earliest_chrono_age.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [Integer](Integer.md)
* Cardinality: 1 _recommended_






## Examples

| Value |
| --- |
| 120000 |
| 1900 |




### Annotations
* Expected_value: age value corresponding to unit



## LinkML Source

<details>
```yaml
name: earliest_chrono_age
annotations:
  Expected_value:
    tag: Expected_value
    value: age value corresponding to unit
description: The maximum/earliest/oldest possible age of a specimen as determined
  by a dating method. If multiple dating measurements available, use the most earliest/oldest
  date to provide widest range of age possibilities. The specific age unit should
  be specified by the term earliest_chrono_sys. More information on specific dates
  (e.g. radiocarbon lab codes) can be specified in the term chrono_age_remarks.
title: Earliest Chronometric Age
examples:
- value: '120000'
- value: '1900'
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
broad_mappings:
- chrono:earliestChronometricAge
rank: 1000
slot_uri: MIXS:999999922
alias: earliest_chrono_age
domain_of:
- Ancient
range: integer
required: true
recommended: true
multivalued: false

```
</details>