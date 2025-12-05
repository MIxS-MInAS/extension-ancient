# Term: host_body_preservation_state 


_Description of the state of the sampled (ancient) organism/host as originally preserved in the burial environment or in the context museomics (eg. taxidermied or pinned), e.g. if the the sample was artificially or naturally (fully/partially) mummified at the time of death._



URI: [MIXS:999999929](https://w3id.org/mixs/999999929)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use host_body_preservation_state.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: 0..1






## Examples

| Value |
| --- |
| complete artificial mummification. |
| natural partial mummification. |
| fully skeletonised. |




### Annotations
* Expected_value: Description of the preservation of the sampled (ancient) organism/host.



## LinkML Source

<details>
```yaml
name: host_body_preservation_state
annotations:
  Expected_value:
    tag: Expected_value
    value: Description of the preservation of the sampled (ancient) organism/host.
description: Description of the state of the sampled (ancient) organism/host as originally
  preserved in the burial environment or in the context museomics (eg. taxidermied
  or pinned), e.g. if the the sample was artificially or naturally (fully/partially)
  mummified at the time of death.
examples:
- value: complete artificial mummification.
- value: natural partial mummification.
- value: fully skeletonised.
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- ancient
string_serialization: '{text}'
slot_uri: MIXS:999999929
alias: host_body_preservation_state
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: false

```
</details>