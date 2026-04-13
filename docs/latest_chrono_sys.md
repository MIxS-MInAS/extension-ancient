# Term: Latest Chronometric Age Reference System (latest_chrono_sys) 


_The reference system associated with the latest_chrono_age._



URI: [MIXS:999999925](https://w3id.org/mixs/999999925)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use latest_chrono_sys.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [ChronoAgeSysEnum](ChronoAgeSysEnum.md)
* Cardinality: 1 _recommended_






## Examples

| Value |
| --- |
| cal BP |
| CE |
| Ma |
| ka |





## LinkML Source

<details>
```yaml
name: latest_chrono_sys
description: The reference system associated with the latest_chrono_age.
title: Latest Chronometric Age Reference System
examples:
- value: cal BP
- value: CE
- value: Ma
- value: ka
in_subset:
- investigation
from_schema: https://w3id.org/mixs
broad_mappings:
- chrono:latestChronometricAgeReferenceSystem
rank: 1000
slot_uri: MIXS:999999925
alias: latest_chrono_sys
domain_of:
- Ancient
range: ChronoAgeSysEnum
required: true
recommended: true
multivalued: false

```
</details>