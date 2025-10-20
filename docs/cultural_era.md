# Term: cultural era or period (cultural_era) 


_The cultural era approximating to the period in which the archaeological remains existed in. Where possible use terms from ontologies such as Chronontology (https://chronontology.dainst.org/) or PeriodO (https://perio.do/en/)._



URI: [MIXS:999999902](https://w3id.org/mixs/999999902)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use cultural_era.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: 0..1






## Examples

| Value |
| --- |
| Copper Age [Chronotology: NW6hofAScJSE] |
| Upper Middle Palaeolthic |
| Not collected |




### Annotations
* Expected_value: chronotology or PeriodO term; text



## LinkML Source

<details>
```yaml
name: cultural_era
annotations:
  Expected_value:
    tag: Expected_value
    value: chronotology or PeriodO term; text
description: The cultural era approximating to the period in which the archaeological
  remains existed in. Where possible use terms from ontologies such as Chronontology
  (https://chronontology.dainst.org/) or PeriodO (https://perio.do/en/).
title: cultural era or period
examples:
- value: 'Copper Age [Chronotology: NW6hofAScJSE]'
- value: Upper Middle Palaeolthic
- value: Not collected
in_subset:
- nucleic acid sequence source
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- ancient
- age
string_serialization: '{termLabel} [{termID}]|{text}'
slot_uri: MIXS:999999902
alias: cultural_era
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: false

```
</details>