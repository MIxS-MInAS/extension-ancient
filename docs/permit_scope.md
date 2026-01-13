# Term: permit scope (permit_scope) 


_Description of the original scope and permissions of the research on the genetic material, as was approved by a legal, ethical, or relevant authority (e.g. bacteria only, DNA only, bacteria and human, no host read analysis allowed). Note this description is only informative, and will not necessarily automatically apply restrictions to associated data to other researchers._



URI: [MIXS:999999928](https://w3id.org/mixs/999999928)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use permit_scope.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: * _recommended_






## Examples

| Value |
| --- |
| Defined scope only includes the study of bacterial sequences and any human sequence is not covered under the agreement. |




### Annotations
* Expected_value: Description of the scope of ethical permissions for data use.



## LinkML Source

<details>
```yaml
name: permit_scope
annotations:
  Expected_value:
    tag: Expected_value
    value: Description of the scope of ethical permissions for data use.
description: Description of the original scope and permissions of the research on
  the genetic material, as was approved by a legal, ethical, or relevant authority
  (e.g. bacteria only, DNA only, bacteria and human, no host read analysis allowed).
  Note this description is only informative, and will not necessarily automatically
  apply restrictions to associated data to other researchers.
title: permit scope
examples:
- value: Defined scope only includes the study of bacterial sequences and any human
    sequence is not covered under the agreement.
in_subset:
- ethics
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- ethics
string_serialization: '{text}'
slot_uri: MIXS:999999928
alias: permit_scope
domain_of:
- Ancient
range: string
required: false
recommended: true
multivalued: true

```
</details>