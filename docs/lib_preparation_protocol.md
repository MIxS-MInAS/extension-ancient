# Term: library preparation protocols (lib_preparation_protocol) 


_Citation(s) for the nucleic acid library preparation protocol._



URI: [MIXS:999999907](https://w3id.org/mixs/999999907)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use lib_preparation_protocol.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: *

* Structured pattern: `^{PMID}|{DOI}|{URL}$`

* Regex pattern: `^^PMID:\d+$|^doi:10.\d{2,9}/.*$|^https?:\/\/(?:www\.)?[-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b(?:[-a-zA-Z0-9()@:%_\+.~#?&\/=]*)$$`






## Examples

| Value |
| --- |
| doi:10.1093/nar/gkr771 |





## LinkML Source

<details>
```yaml
name: lib_preparation_protocol
description: Citation(s) for the nucleic acid library preparation protocol.
title: library preparation protocols
examples:
- value: doi:10.1093/nar/gkr771
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:999999907
alias: lib_preparation_protocol
domain_of:
- Ancient
range: string
multivalued: true
pattern: ^^PMID:\d+$|^doi:10.\d{2,9}/.*$|^https?:\/\/(?:www\.)?[-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b(?:[-a-zA-Z0-9()@:%_\+.~#?&\/=]*)$$
structured_pattern:
  syntax: ^{PMID}|{DOI}|{URL}$
  interpolated: true
  partial_match: true

```
</details>