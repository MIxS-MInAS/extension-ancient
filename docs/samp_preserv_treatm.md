# Term: preservational treatment (samp_preserv_treatm) 


_Description of any treatment applied directly to samples for the specific purpose of  maximising longevity of sample preservation in archives and/or collections by curators  that may influence downstream nucleic acid recovery or library construction, such as storage fluid or  reconstructive glue._



URI: [MIXS:999999919](https://w3id.org/mixs/999999919)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use samp_preserv_treatm.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



## Properties

* Range: [String](String.md)
* Cardinality: *






## Examples

| Value |
| --- |
| stored in formalin |
| reconstructive glue applied |
| alcohol preserved |





## LinkML Source

<details>
```yaml
name: samp_preserv_treatm
description: Description of any treatment applied directly to samples for the specific
  purpose of  maximising longevity of sample preservation in archives and/or collections
  by curators  that may influence downstream nucleic acid recovery or library construction,
  such as storage fluid or  reconstructive glue.
title: preservational treatment
examples:
- value: stored in formalin
- value: reconstructive glue applied
- value: alcohol preserved
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- ancient
string_serialization: '{text}'
slot_uri: MIXS:999999919
alias: samp_preserv_treatm
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: true

```
</details>