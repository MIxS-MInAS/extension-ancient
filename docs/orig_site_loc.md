# Term: original site location (orig_site_loc) 


_The original geographical origin of the sample, when sampled outside its original natural environment (e.g. sampled in a museum collection), as defined by the country or sea name followed by specific region name.  Country or sea names should be chosen from the INSDC country list (http://insdc.org/country.html), or the GAZ ontology (http://purl.bioontology.org/ontology/GAZ)._



URI: [MIXS:999999902](https://w3id.org/mixs/999999902)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use orig_site_loc.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: 0..1

* Structured pattern: `^{country}: {region}, {specific_location}$`






## Examples

| Value |
| --- |
| South Africa: Western Cape |
| Germany: Baden-Württemberg, Geißenklösterle Cave |
| Northern Italy: Lombardy |




### Annotations
* Expected_value: Name of original geographic origin of the sample



## LinkML Source

<details>
```yaml
name: orig_site_loc
annotations:
  Expected_value:
    tag: Expected_value
    value: Name of original geographic origin of the sample
description: The original geographical origin of the sample, when sampled outside
  its original natural environment (e.g. sampled in a museum collection), as defined
  by the country or sea name followed by specific region name.  Country or sea names
  should be chosen from the INSDC country list (http://insdc.org/country.html), or
  the GAZ ontology (http://purl.bioontology.org/ontology/GAZ).
title: original site location
examples:
- value: 'South Africa: Western Cape'
- value: 'Germany: Baden-Württemberg, Geißenklösterle Cave'
- value: 'Northern Italy: Lombardy'
in_subset:
- environment
from_schema: https://w3id.org/mixs
rank: 1000
keywords:
- location
- site
slot_uri: MIXS:999999902
alias: orig_site_loc
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: false
structured_pattern:
  syntax: '^{country}: {region}, {specific_location}$'

```
</details>