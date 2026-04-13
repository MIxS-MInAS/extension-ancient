# Term: original geographic location (latitude) (orig_site_lat) 


_The latitude coordinate of the original geographical origin of the sample, e.g. the original place the sample was buried, deposited, or formed. In cases where the sample was directly sampled in the burial environment for the purposes of scientific investigation, this will be the same as geo_loc_name, and lat_lon.  For samples kept in collections, the geo_loc_name and lat_lon terms are used to refer to the collection where the sample is stored, but this term is used for the original geographic location the sample existed in prior to archiving in a collection (i.e., should correspond to  orig_site_loc, not the collection itself as recorded in site_name). The values should be reported in decimal degrees, limited to 8 decimal points, and in WGS84 system._



URI: [MIXS:999999903](https://w3id.org/mixs/999999903)



<!-- no inheritance hierarchy -->





## Applicable [Checklists](index.md#checklists) and [Extensions](index.md#extensions)

<b>NOTE:</b> does not include [Combinations](combinations.md) (of checklists and extensions) that use orig_site_lat.

| Name | Description | Checklist/Extension |
| --- | --- | --- |
| [Ancient](Ancient.md) | A collection of terms appropriate when collecting samples and sequencing samp... | Extension |




## Properties

* Range: [String](String.md)
* Cardinality: 0..1

* Structured pattern: `^{lat}$`






## Examples

| Value |
| --- |
| 50.586825 |
| -0.123 |





## LinkML Source

<details>
```yaml
name: orig_site_lat
description: The latitude coordinate of the original geographical origin of the sample,
  e.g. the original place the sample was buried, deposited, or formed. In cases where
  the sample was directly sampled in the burial environment for the purposes of scientific
  investigation, this will be the same as geo_loc_name, and lat_lon.  For samples
  kept in collections, the geo_loc_name and lat_lon terms are used to refer to the
  collection where the sample is stored, but this term is used for the original geographic
  location the sample existed in prior to archiving in a collection (i.e., should
  correspond to  orig_site_loc, not the collection itself as recorded in site_name).
  The values should be reported in decimal degrees, limited to 8 decimal points, and
  in WGS84 system.
title: original geographic location (latitude)
examples:
- value: '50.586825'
- value: '-0.123'
in_subset:
- environment
from_schema: https://w3id.org/mixs
rank: 1000
slot_uri: MIXS:999999903
alias: orig_site_lat
domain_of:
- Ancient
range: string
required: false
recommended: false
multivalued: false
structured_pattern:
  syntax: ^{lat}$
  interpolated: true
  partial_match: true

```
</details>