

# Slot: No slot (predicate) name specified (sockg_locatedInCounty)


_No slot (predicate) description specified_






This slot occurs 61 times.


URI: [sockg:locatedInCounty](https://idir.uta.edu/sockg-ontology/docs/locatedInCounty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSite](../classes/SockgSite.md) | A Site represents a specific geographical location related to agricultural ac... |  yes  |







## Properties

* Range: [SockgCounty](../classes/SockgCounty.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Site | sockg_County | sockg:individuals/231056 | sockg:individuals/46904 | 61 |




## LinkML Source

<details>

```yaml
name: sockg_locatedInCounty
annotations:
  count:
    tag: count
    value: 61
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/46904
    example_object_type: sockg_County
    example_predicate: sockg:locatedInCounty
    example_subject: sockg:individuals/231056
    example_subject_type: sockg_Site
from_schema: soc-kg
rank: 1000
domain: sockg_Site
slot_uri: sockg:locatedInCounty
alias: sockg_locatedInCounty
domain_of:
- sockg_Site
range: sockg_County

```
</details>