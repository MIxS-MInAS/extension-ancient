# Enum: LibStrandEnum 




_Options for the strandedness of the input 'template' DNA molecules used for DNA library construction._



URI: [MIXS:LibStrandEnum](https://w3id.org/mixs/LibStrandEnum)

## Permissible Values
| Value | Meaning | Description |
| --- | --- | --- |
| single | None | Library constructed from single-stranded DNA molecules |
| double | None | Library constructed from double-stranded DNA molecules |




## Slots

| Name | Description |
| ---  | --- |
| [lib_strandedness](lib_strandedness.md) | The strandedness of the original template nucleic acid molecules used for con... |










## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/mixs






## LinkML Source

<details>
```yaml
name: LibStrandEnum
description: Options for the strandedness of the input 'template' DNA molecules used
  for DNA library construction.
from_schema: https://w3id.org/mixs
rank: 1000
permissible_values:
  single:
    text: single
    description: Library constructed from single-stranded DNA molecules.
  double:
    text: double
    description: Library constructed from double-stranded DNA molecules.

```
</details>