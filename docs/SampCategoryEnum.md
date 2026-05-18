# Enum: SampCategoryEnum 




_Controlled vocabulary defining the category of a sample based on its experiental role._



URI: [SampCategoryEnum](SampCategoryEnum.md)

## Permissible Values

| Value | Description |
| --- | --- |
| sample | Biological or environmental sample, including biological and technical replic... |
| negative control | Negative control used to detect contamination, such as field negatives, extra... |
| positive control | Positive control used to verify successful amplification or detection, such a... |
| PCR standard | Standard consisting of known quantities of target nucleic acid used to genera... |
| Other | Other types of samples not represented in the controlled vocabulary |




## Terms

| Name | Description |
| ---  | --- |
| [samp_category](samp_category.md) | The type/category of a sample |










## LinkML Source

<details>
```yaml
name: SampCategoryEnum
description: Controlled vocabulary defining the category of a sample based on its
  experiental role.
from_schema: https://w3id.org/mixs
rank: 1000
permissible_values:
  sample:
    text: sample
    description: Biological or environmental sample, including biological and technical
      replicates.
  negative control:
    text: negative control
    description: Negative control used to detect contamination, such as field negatives,
      extraction negatives, or PCR negatives (No-template control; NTC).
  positive control:
    text: positive control
    description: Positive control used to verify successful amplification or detection,
      such as extraction positives or PCR positives.
  PCR standard:
    text: PCR standard
    description: Standard consisting of known quantities of target nucleic acid used
      to generate calibration curves and enable quantification of target molecules.
  Other:
    text: Other
    description: Other types of samples not represented in the controlled vocabulary.

```
</details>
