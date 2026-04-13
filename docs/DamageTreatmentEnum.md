# Enum: DamageTreatmentEnum 




_Options for types of molecular damage removal during library construction of ancient DNA libraries._



URI: [DamageTreatmentEnum](DamageTreatmentEnum.md)

## Permissible Values

| Value | Description |
| --- | --- |
| no-removal | Molecular damage-derived misincorporations have not been removed using labora... |
| partial-removal | Molecular damage-derived misincorporations have been partially removed using ... |
| complete-removal | Molecular damage-derived misincorporations have been entirely removed using l... |
| damage-selection | Library preparation-derived technique that retain only molecules containing d... |
| other | Other type of damage treatment that are further described in other method des... |




## Terms

| Name | Description |
| ---  | --- |
| [damage_treatment](damage_treatment.md) | Indication of whether characteristic ancient DNA damage has been altered or r... |










## LinkML Source

<details>
```yaml
name: DamageTreatmentEnum
description: Options for types of molecular damage removal during library construction
  of ancient DNA libraries.
from_schema: https://w3id.org/mixs
rank: 1000
permissible_values:
  no-removal:
    text: no-removal
    description: Molecular damage-derived misincorporations have not been removed
      using laboratory techniques.
  partial-removal:
    text: partial-removal
    description: Molecular damage-derived misincorporations have been partially removed
      using laboratory techniques such as with an early stopped uracil-DNA glycosylase
      (UDG) or USER treatment, leaving a small number of nucleotides with damage at
      ends of molecules.
  complete-removal:
    text: complete-removal
    description: Molecular damage-derived misincorporations have been entirely removed
      using laboratory techniques such as with complete uracil-DNA glycosylase (UDG)
      or USER treatment, leaving no nucleotides with damage at ends of molecules.
  damage-selection:
    text: damage-selection
    description: Library preparation-derived technique that retain only molecules
      containing damage, and have discarded those without damage.
  other:
    text: other
    description: Other type of damage treatment that are further described in other
      method description terms. If damage has been removed, but whether full or partial
      is unknown - use this option and describe known information in `experimental_sop`
      and related free text descriptive terms.

```
</details>
