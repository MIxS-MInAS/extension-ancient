# Enum: ChronoAgeSysEnum 




_Options for specifying the chonometric age reference or timescale of a date._



URI: [MIXS:ChronoAgeSysEnum](https://w3id.org/mixs/ChronoAgeSysEnum)

## Permissible Values
| Value | Meaning | Description |
| --- | --- | --- |
| BCE | None | Before Common Era (before year 0 in the Christian calendar), equivalent to BC... |
| CE | None | Common Era (after year 0 in the Christian calendar), equivalent to AD (anno D... |
| BP | None | Before Present (~1950), known as 'Standard Year' |
| cal BP | None | Calibrated Before Present (~1950), known as 'Standard Year' |
| cal BCE | None | Calibrated Before Common Era (year 0 in the Christian calendar), equivalent t... |
| cal CE | None | Calibrated Common Era (~1950), equivalent to AD (anno Domini, after Christ) |
| ka | None | kiloannum; thousands of years ago |
| Ma | None | megaannum; millions of years ago |




## Slots

| Name | Description |
| ---  | --- |
| [earliest_chrono_sys](earliest_chrono_sys.md) | The reference system associated with the earliest_chrono_age |
| [latest_chrono_sys](latest_chrono_sys.md) | The reference system associated with the latest_chrono_age |










## Identifier and Mapping Information





### Schema Source


* from schema: https://w3id.org/mixs






## LinkML Source

<details>
```yaml
name: ChronoAgeSysEnum
description: Options for specifying the chonometric age reference or timescale of
  a date.
from_schema: https://w3id.org/mixs
rank: 1000
permissible_values:
  BCE:
    text: BCE
    description: Before Common Era (before year 0 in the Christian calendar), equivalent
      to BC (before Christ).
  CE:
    text: CE
    description: Common Era (after year 0 in the Christian calendar), equivalent to
      AD (anno Domini, after Christ).
  BP:
    text: BP
    description: Before Present (~1950), known as 'Standard Year'.
  cal BP:
    text: cal BP
    description: Calibrated Before Present (~1950), known as 'Standard Year'.
  cal BCE:
    text: cal BCE
    description: Calibrated Before Common Era (year 0 in the Christian calendar),
      equivalent to BC (before Christ).
  cal CE:
    text: cal CE
    description: Calibrated Common Era (~1950), equivalent to AD (anno Domini, after
      Christ).
  ka:
    text: ka
    description: kiloannum; thousands of years ago.
  Ma:
    text: Ma
    description: megaannum; millions of years ago.

```
</details>