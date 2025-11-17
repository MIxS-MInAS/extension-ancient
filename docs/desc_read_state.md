# Term: description of read state (desc_read_state) 


_Description of the state of the reads in the sequencing data file. Describe any in silico processing or modification of the sequencing reads away from the original state as received from the sequencer. This should include details such as adapter-, barcode-, and/or quality- trimming, or any filtering such as for read length or of off-target reads._



URI: [MIXS:999999933](https://w3id.org/mixs/999999933)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use desc_read_state.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: 0..1 _recommended_






## Examples

| Value |
| --- |
| Adapter trimmed, quality filtered, and host reads removed through mapping for ethical reasons. |
| Adapters removed by Trimmomatic (v0.39), and off-target reads removed after mapping to the HG19 Human reference with bwa aln (v0.7.19). |
| Demultiplexed with bcl2fastq, inline barcodes removed, and reads quality filtered with fastp (v1.0.0). |




### Annotations
* Expected_value: description of any modifications to data away from original raw files



## LinkML Source

<details>
```yaml
name: desc_read_state
annotations:
  Expected_value:
    tag: Expected_value
    value: description of any modifications to data away from original raw files
description: Description of the state of the reads in the sequencing data file. Describe
  any in silico processing or modification of the sequencing reads away from the original
  state as received from the sequencer. This should include details such as adapter-,
  barcode-, and/or quality- trimming, or any filtering such as for read length or
  of off-target reads.
title: description of read state
examples:
- value: Adapter trimmed, quality filtered, and host reads removed through mapping
    for ethical reasons.
- value: Adapters removed by Trimmomatic (v0.39), and off-target reads removed after
    mapping to the HG19 Human reference with bwa aln (v0.7.19).
- value: Demultiplexed with bcl2fastq, inline barcodes removed, and reads quality
    filtered with fastp (v1.0.0).
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- data analysis
- data
slot_uri: MIXS:999999933
alias: desc_read_state
domain_of:
- Ancient
range: string
required: false
recommended: true
multivalued: false

```
</details>