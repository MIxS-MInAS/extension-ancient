# Term: date of retrieval from depositional context (recovery_date) 


_Date of excavation or retrieval from burial or depositional context, if known. In case no exact time is available, the date can be right truncated i.e. all of these are valid times: 2008-01-23T19:23:10+00:00; 2008-01-23T19:23:10; 2008-01-23; 2008-01; 2008; Except: 2008-01; 2008 all are ISO8601 compliant. If excavations were done during a longer period, report its midpoint at a month or year level._



URI: [MIXS:9999999916](https://w3id.org/mixs/9999999916)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use recovery_date.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [Datetime](Datetime.md)
* Cardinality: 0..1 _recommended_






## Examples

| Value |
| --- |
| 2023 |




### Annotations
* Preferred_unit: year



## LinkML Source

<details>
```yaml
name: recovery_date
annotations:
  Preferred_unit:
    tag: Preferred_unit
    value: year
description: 'Date of excavation or retrieval from burial or depositional context,
  if known. In case no exact time is available, the date can be right truncated i.e.
  all of these are valid times: 2008-01-23T19:23:10+00:00; 2008-01-23T19:23:10; 2008-01-23;
  2008-01; 2008; Except: 2008-01; 2008 all are ISO8601 compliant. If excavations were
  done during a longer period, report its midpoint at a month or year level.'
title: date of retrieval from depositional context
examples:
- value: '2023'
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:9999999916
alias: recovery_date
domain_of:
- Ancient
range: datetime
required: false
recommended: true

```
</details>