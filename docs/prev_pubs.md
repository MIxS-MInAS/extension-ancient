# Term: previous publications (prev_pubs) 


_Any previous publications that report non-nucleic acid data from the same sample or ultimate source of the sample_



URI: [MIXS:0001370](https://w3id.org/mixs/0001370)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use prev_pubs.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [String](String.md)
* Cardinality: *

* Structured pattern: `^{PMID}|{DOI}|{URL}$`

* Regex pattern: `^^PMID:\d+$|^doi:10.\d{2,9}/.*$|^https?:\/\/(?:www\.)?[-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b(?:[-a-zA-Z0-9()@:%_\+.~#?&\/=]*)$$`






## Examples

| Value |
| --- |
| doi:10.1016/j.jas.2015.02.0181 |





## LinkML Source

<details>
```yaml
name: prev_pubs
description: Any previous publications that report non-nucleic acid data from the
  same sample or ultimate source of the sample
title: previous publications
examples:
- value: doi:10.1016/j.jas.2015.02.0181
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:0001370
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: true
pattern: ^^PMID:\d+$|^doi:10.\d{2,9}/.*$|^https?:\/\/(?:www\.)?[-a-zA-Z0-9@:%._\+~#=]{1,256}\.[a-zA-Z0-9()]{1,6}\b(?:[-a-zA-Z0-9()@:%_\+.~#?&\/=]*)$$
structured_pattern:
  syntax: ^{PMID}|{DOI}|{URL}$
  interpolated: true
  partial_match: true

```
</details>