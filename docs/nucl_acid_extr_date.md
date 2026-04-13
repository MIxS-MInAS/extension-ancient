# Term: date of extraction of nucleic acids from sample (nucl_acid_extr_date) 


_The date when the nucleic acid extraction was started from the sample material. In case no exact time is available, the date can be right truncated i.e. all of these are valid times: 2008-01-23T19:23:10+00:00; 2008-01-23T19:23:10; 2008-01-23; 2008-01; 2008; Except: 2008-01; 2008 all are ISO8601 compliant_



URI: [MIXS:999999933](https://w3id.org/mixs/999999933)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use nucl_acid_extr_date.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [Datetime](Datetime.md)
* Cardinality: 0..1






## Examples

| Value |
| --- |
| 2023-12-01 |





## LinkML Source

<details>
```yaml
name: nucl_acid_extr_date
description: 'The date when the nucleic acid extraction was started from the sample
  material. In case no exact time is available, the date can be right truncated i.e.
  all of these are valid times: 2008-01-23T19:23:10+00:00; 2008-01-23T19:23:10; 2008-01-23;
  2008-01; 2008; Except: 2008-01; 2008 all are ISO8601 compliant'
title: date of extraction of nucleic acids from sample
examples:
- value: '2023-12-01'
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:999999933
alias: nucl_acid_extr_date
domain_of:
- Ancient
range: datetime
required: false
recommended: false

```
</details>