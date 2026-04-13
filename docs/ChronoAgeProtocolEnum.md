# Enum: ChronoAgeProtocolEnum 




_Options for methods to determine the age at time of death of an organism or the date of sample deposition._



URI: [ChronoAgeProtocolEnum](ChronoAgeProtocolEnum.md)

## Permissible Values

| Value | Description |
| --- | --- |
| radiocarbon dating |  |
| optically stimulated infrared luminescence |  |
| amino acid racemisation |  |
| electron spin resonance |  |
| uranium thorium |  |
| age-depth modelling | Age-depth models are constructed based on limited numbers of dated depths (ty... |
| contextual dating | A non-absolute date inferred from the specific context of an archaeological o... |
| associated absolute dating | Dates inferred from the absolute dates of associated materials within the sam... |
| historical records |  |
| other |  |




## Terms

| Name | Description |
| ---  | --- |
| [chrono_age_protocol](chrono_age_protocol.md) | A description of or reference to the methods used to determine the earliest_c... |










## LinkML Source

<details>
```yaml
name: ChronoAgeProtocolEnum
description: Options for methods to determine the age at time of death of an organism
  or the date of sample deposition.
from_schema: https://w3id.org/mixs
rank: 1000
permissible_values:
  radiocarbon dating:
    text: radiocarbon dating
  optically stimulated infrared luminescence:
    text: optically stimulated infrared luminescence
  amino acid racemisation:
    text: amino acid racemisation
  electron spin resonance:
    text: electron spin resonance
  uranium thorium:
    text: uranium thorium
  age-depth modelling:
    text: age-depth modelling
    description: Age-depth models are constructed based on limited numbers of dated
      depths (typically in sediment cores) to estimate the calendar ages. Different
      models are used based on assumptions about the sequence of deposit formation
      at each dated depth.
  contextual dating:
    text: contextual dating
    description: A non-absolute date inferred from the specific context of an archaeological
      or palaeontological sample (e.g. stratigraphic layers, coins).
  associated absolute dating:
    text: associated absolute dating
    description: Dates inferred from the absolute dates of associated materials within
      the same specific context of the sample (e.g. C14 dating of a animal bone artefact
      in the same context of a human burial).
  historical records:
    text: historical records
  other:
    text: other

```
</details>
