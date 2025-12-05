# Term: permit authority (permit_authority) 


_Name of the authorit(ies) or institution(s) that granted sampling and analysis (e.g. human remains) and/or export permission (e.g. animal remains), as well any form of ethical approval (whether from institutional research ethics boards such as REB or IRBs, or indigenous or native community associations), if available._



URI: [MIXS:999999905](https://w3id.org/mixs/999999905)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use permit_authority.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: * _recommended_






## Examples

| Value |
| --- |
| University of Copenhagen |
| Federal Foreign Office (Germany) |




### Annotations
* Expected_value: Name of authority providing permission or ethical approval.



## LinkML Source

<details>
```yaml
name: permit_authority
annotations:
  Expected_value:
    tag: Expected_value
    value: Name of authority providing permission or ethical approval.
description: Name of the authorit(ies) or institution(s) that granted sampling and
  analysis (e.g. human remains) and/or export permission (e.g. animal remains), as
  well any form of ethical approval (whether from institutional research ethics boards
  such as REB or IRBs, or indigenous or native community associations), if available.
title: permit authority
examples:
- value: University of Copenhagen
- value: Federal Foreign Office (Germany)
in_subset:
- investigation
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- ethics
- location
slot_uri: MIXS:999999905
alias: permit_authority
domain_of:
- Ancient
range: string
required: false
recommended: true
multivalued: true

```
</details>