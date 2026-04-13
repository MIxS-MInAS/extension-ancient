# Term: preservation state of sampled organism/host at/immediately after death (host_preserv_state) 


_Description of the state of the sampled (ancient) organism/host as originally  preserved in the burial environment at the time of or immediately following death. This can be both natural or artificial, such as mummification or burning for funerary purposes._



URI: [MIXS:999999917](https://w3id.org/mixs/999999917)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use host_preserv_state.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |

-->



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
* Expected_value: Description of the preservation of the sampled (ancient) organism/host at time/immediately after death.



## LinkML Source

<details>
```yaml
name: host_preserv_state
annotations:
  Expected_value:
    tag: Expected_value
    value: Description of the preservation of the sampled (ancient) organism/host
      at time/immediately after death.
description: Description of the state of the sampled (ancient) organism/host as originally  preserved
  in the burial environment at the time of or immediately following death. This can
  be both natural or artificial, such as mummification or burning for funerary purposes.
title: preservation state of sampled organism/host at/immediately after death
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
slot_uri: MIXS:999999917
alias: host_preserv_state
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: false

```
</details>