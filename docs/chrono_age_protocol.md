# Term: Chronometric Age Protocol (chrono_age_protocol) 


_A description of or reference to the methods used to determine the earliest_chrono_age and latest_chrono_age._



URI: [MIXS:999999926](https://w3id.org/mixs/999999926)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use chrono_age_protocol.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [ChronoAgeProtocolEnum](ChronoAgeProtocolEnum.md)
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
name: chrono_age_protocol
description: A description of or reference to the methods used to determine the earliest_chrono_age
  and latest_chrono_age.
title: Chronometric Age Protocol
examples:
- value: radiocarbon dating
- value: optically stimulated infrared luminescence
- value: contextual dating
- value: historical records
in_subset:
- investigation
from_schema: https://w3id.org/mixs
broad_mappings:
- chrono:chronometricAgeProtocol
rank: 1000
slot_uri: MIXS:999999926
alias: chrono_age_protocol
domain_of:
- Ancient
range: ChronoAgeProtocolEnum
required: false
recommended: true
multivalued: true

```
</details>