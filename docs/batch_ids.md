# Term: batch identifiers (batch_ids) 


_Identifiers for any form of batch or 'group' that the samples is associated with, examples including: individual/skeleton ID, sediment core IDs, extract batch, library batch, sequencing run etc..  These IDs should always act as 'umbrella' IDs that allow association with entries processed together, to allow for downstream analyses of batch effects. Ideally, the information should indicate or specify what type of batch the ID is describing._



URI: [MIXS:999999929](https://w3id.org/mixs/999999929)



<!-- no inheritance hierarchy -->


<!--



## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include Combinations (of checklists and extensions) that use batch_ids.

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
| EXTB1;LIBB2;SeqRun1 |
| Extraction batch: 1 |
| 20260501-A2 (extraction);20202607-B2 (library) |
| ExtrMG;LibMG;SeqMG |
| Core: North-East Greenland 73G |




### Annotations
* Expected_value: list any batch_ids the sample, nucleic acids, or library was associated with during processing and sequencing



## LinkML Source

<details>
```yaml
name: batch_ids
annotations:
  Expected_value:
    tag: Expected_value
    value: list any batch_ids the sample, nucleic acids, or library was associated
      with during processing and sequencing
description: 'Identifiers for any form of batch or ''group'' that the samples is associated
  with, examples including: individual/skeleton ID, sediment core IDs, extract batch,
  library batch, sequencing run etc..  These IDs should always act as ''umbrella''
  IDs that allow association with entries processed together, to allow for downstream
  analyses of batch effects. Ideally, the information should indicate or specify what
  type of batch the ID is describing.'
title: batch identifiers
examples:
- value: EXTB1;LIBB2;SeqRun1
- value: 'Extraction batch: 1'
- value: 20260501-A2 (extraction);20202607-B2 (library)
- value: ExtrMG;LibMG;SeqMG
- value: 'Core: North-East Greenland 73G'
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- identifiers
slot_uri: MIXS:999999929
alias: batch_ids
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: true

```
</details>