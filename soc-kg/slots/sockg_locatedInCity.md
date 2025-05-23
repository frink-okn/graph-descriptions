

# Slot: No slot (predicate) name specified (sockg_locatedInCity)


_No slot (predicate) description specified_






This slot occurs 59 times.


URI: [sockg:locatedInCity](https://idir.uta.edu/sockg-ontology/docs/locatedInCity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSite](../classes/SockgSite.md) | A Site represents a specific geographical location related to agricultural ac... |  yes  |







## Properties

* Range: [SockgCity](../classes/SockgCity.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Site | sockg_City | sockg:individuals/231056 | sockg:individuals/46864 | 59 |




## LinkML Source

<details>

```yaml
name: sockg_locatedInCity
annotations:
  count:
    tag: count
    value: 59
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/46864
    example_object_type: sockg_City
    example_predicate: sockg:locatedInCity
    example_subject: sockg:individuals/231056
    example_subject_type: sockg_Site
from_schema: soc-kg
rank: 1000
domain: sockg_Site
slot_uri: sockg:locatedInCity
alias: sockg_locatedInCity
domain_of:
- sockg_Site
range: sockg_City

```
</details>