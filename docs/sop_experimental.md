# Term: experimental standard operating procedure (sop_experimental) 


_Provide a DOI or URL to refer to the paper where the field report, nucleic acid extraction,  library construction, and other procedures are explained in more detail, e.g. the paper reporting the data._



URI: [MIXS:999999934](https://w3id.org/mixs/999999934)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use sop_experimental.

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
| doi:10.1093/nar/gkr771 |





## LinkML Source

<details>
```yaml
name: sop_experimental
description: Provide a DOI or URL to refer to the paper where the field report, nucleic
  acid extraction,  library construction, and other procedures are explained in more
  detail, e.g. the paper reporting the data.
title: experimental standard operating procedure
examples:
- value: doi:10.1093/nar/gkr771
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:999999934
alias: sop_experimental
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