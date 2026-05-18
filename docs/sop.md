# Term: relevant standard operating procedures (sop) 


_Standard operating procedures used to generate genomes, metagenomes or environmental sequences_



URI: [MIXS:0000090](https://w3id.org/mixs/0000090)



<!-- no inheritance hierarchy -->


<!--



## Properties

* Range: [String](String.md)
* Cardinality: *

* Structured pattern: `^({PMID}|{DOI}|{URL})$`






## Examples

| Value |
| --- |
| http://press.igsb.anl.gov/earthmicrobiome/protocols-and-standards/its/ |




### Annotations
* Expected_value: reference to SOP



## LinkML Source

<details>
```yaml
name: sop
annotations:
  Expected_value:
    tag: Expected_value
    value: reference to SOP
description: Standard operating procedures used to generate genomes, metagenomes or
  environmental sequences
title: relevant standard operating procedures
examples:
- value: http://press.igsb.anl.gov/earthmicrobiome/protocols-and-standards/its/
in_subset:
- sequencing
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- procedures
slot_uri: MIXS:0000090
alias: sop
domain_of:
- MimsMisip
- MigsBa
- MigsEu
- MigsOrg
- MigsPl
- MigsVi
- Mimag
- MimarksC
- MimarksS
- Mims
- Misag
- Miuvig
- Agriculture
range: string
multivalued: true
structured_pattern:
  syntax: ^({PMID}|{DOI}|{URL})$
  interpolated: true

```
</details>