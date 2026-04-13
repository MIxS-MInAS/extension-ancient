# Enum: LibTypeEnum 




_Options for types of DNA that have been targeted for DNA library construction._



URI: [LibTypeEnum](LibTypeEnum.md)

## Permissible Values

| Value | Description |
| --- | --- |
| amplicon | A library that has been enriched for a single specific region of a genome (e |
| enriched | A library that has been enriched for DNA from typically large portions to the... |
| shotgun | An unselected library that has undergone no type of targeted amplification/en... |




## Terms

| Name | Description |
| ---  | --- |
| [lib_type](lib_type.md) | The type of library created, i |










## LinkML Source

<details>
```yaml
name: LibTypeEnum
description: Options for types of DNA that have been targeted for DNA library construction.
from_schema: https://w3id.org/mixs
rank: 1000
permissible_values:
  amplicon:
    text: amplicon
    description: A library that has been enriched for a single specific region of
      a genome (e.g. a specific gene) through targeted amplification.
  enriched:
    text: enriched
    description: A library that has been enriched for DNA from typically large portions
      to the entirety of a genome, through array or in-solution 'capture' with genome
      array baits/probes.
  shotgun:
    text: shotgun
    description: An unselected library that has undergone no type of targeted amplification/enrichment
      for a particular genomic region or genome, i.e., random sequencing of any nucleic
      acid molecule contained in a genomic library.

```
</details>
