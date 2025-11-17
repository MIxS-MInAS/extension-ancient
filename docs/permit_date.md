# Term: date of permit approval (permit_date) 


_Date on which a permit was granted. The date can be right truncated i.e. all of these are valid times: 2008-01-23; 2008-01; 2008; Except: 2008-01; 2008 all are ISO8601 compliant._



URI: [MIXS:9999999906](https://w3id.org/mixs/9999999906)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use permit_date.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [Datetime](Datetime.md)
* Cardinality: 0..1 _recommended_






## Examples

| Value |
| --- |
| 2023-12-01 |





## LinkML Source

<details>
```yaml
name: permit_date
description: 'Date on which a permit was granted. The date can be right truncated
  i.e. all of these are valid times: 2008-01-23; 2008-01; 2008; Except: 2008-01; 2008
  all are ISO8601 compliant.'
title: date of permit approval
examples:
- value: '2023-12-01'
in_subset:
- investigation
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:9999999906
alias: permit_date
domain_of:
- Ancient
range: datetime
required: false
recommended: true

```
</details>