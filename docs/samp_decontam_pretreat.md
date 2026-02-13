# Term: sample decontamination pretreatment (samp_decontam_pretreat) 


_Method(s) employed for surface decontamination of samples of external  modern nucleic acids; Treatment used on the samples. Depends on the sample type.  More relevant for bones than environmental samples. E.g. buffers, EDTA, etc._



URI: [MIXS:999999917](https://w3id.org/mixs/999999917)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use samp_decontam_pretreat.

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
| doi:10.1016/j.jas.2015.02.0181 |





## LinkML Source

<details>
```yaml
name: samp_decontam_pretreat
description: Method(s) employed for surface decontamination of samples of external  modern
  nucleic acids; Treatment used on the samples. Depends on the sample type.  More
  relevant for bones than environmental samples. E.g. buffers, EDTA, etc.
title: sample decontamination pretreatment
examples:
- value: doi:10.1016/j.jas.2015.02.0181
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:999999917
alias: samp_decontam_pretreat
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