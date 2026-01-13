# Enum: SampAgeInferMethod 



URI: [MIXS:SampAgeInferMethod](https://w3id.org/mixs/SampAgeInferMethod)

## Permissible Values

| Value | Meaning | Description |
| --- | --- | --- |
| radiocarbon dating | None |  |
| optically stimulated infrared luminescence | None |  |
| amino acid racemisation | None |  |
| electron spin resonance | None |  |
| uranium thorium | None |  |
| contextual dating | None | A non-absolute date inferred from the specific context of an archaeological o... |
| associated absolute dating | None | Dates inferred from the absolute dates of associated materials within the sam... |
| historical records | None |  |
| other | None |  |




## Slots

| Name | Description |
| ---  | --- |
| [samp_age_range_inference_methods](samp_age_range_inference_methods.md) | The method used to infer the sample age |





## Identifier and Mapping Information






### Schema Source


* from schema: https://w3id.org/mixs






## LinkML Source

<details>
```yaml
name: SampAgeInferMethod
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