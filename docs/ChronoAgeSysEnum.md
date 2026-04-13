# Enum: ChronoAgeSysEnum 




_Options for specifying the chonometric age reference or timescale of a date._



URI: [ChronoAgeSysEnum](ChronoAgeSysEnum.md)

## Permissible Values

| Value | Description |
| --- | --- |
| BCE | Before Common Era (before year 0 in the Christian calendar), equivalent to BC... |
| CE | Common Era (after year 0 in the Christian calendar), equivalent to AD (anno D... |
| BP | Before Present (~1950), known as 'Standard Year' |
| cal BP | Calibrated Before Present (~1950), known as 'Standard Year' |
| cal BCE | Calibrated Before Common Era (year 0 in the Christian calendar), equivalent t... |
| cal CE | Calibrated Common Era (~1950), equivalent to AD (anno Domini, after Christ) |
| ka | kiloannum; thousands of years ago |
| Ma | megaannum; millions of years ago |




## Terms

| Name | Description |
| ---  | --- |
| [earliest_chrono_sys](earliest_chrono_sys.md) | The reference system associated with the earliest_chrono_age |
| [latest_chrono_sys](latest_chrono_sys.md) | The reference system associated with the latest_chrono_age |










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
