# Class: MIxS compliant data (MixsCompliantData) 


_A collection of data that complies with some combination of a MIxS checklist and environmental extension_







## Terms 

| MIXS ID | Name | Cardinality and Range | Description |
| ---  | --- | --- | --- |
| [MIXS:ancient_data](https://w3id.org/mixs/ancient_data) | [ancient_data](ancient_data.md) | * <br/> [Ancient](Ancient.md) | Data that comply with Extension Ancient |










## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: MixsCompliantData
description: A collection of data that complies with some combination of a MIxS checklist
  and environmental extension
title: MIxS compliant data
from_schema: https://w3id.org/mixs
slots:
- ancient_data
tree_root: true

```
</details>

### Induced

<details>
```yaml
name: MixsCompliantData
description: A collection of data that complies with some combination of a MIxS checklist
  and environmental extension
title: MIxS compliant data
from_schema: https://w3id.org/mixs
attributes:
  ancient_data:
    name: ancient_data
    description: Data that comply with Extension Ancient
    title: Ancient data
    from_schema: https://w3id.org/mixs
    rank: 1000
    domain: MixsCompliantData
    slot_uri: MIXS:ancient_data
    alias: ancient_data
    owner: MixsCompliantData
    domain_of:
    - MixsCompliantData
    range: Ancient
    multivalued: true
    inlined: true
    inlined_as_list: true
tree_root: true

```
</details>