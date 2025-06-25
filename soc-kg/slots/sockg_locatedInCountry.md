

# Slot: No slot (predicate) name specified (sockg_locatedInCountry)


_No slot (predicate) description specified_






This slot occurs 60 times.


URI: [sockg:locatedInCountry](https://idir.uta.edu/sockg-ontology/docs/locatedInCountry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSite](../classes/SockgSite.md) | A Site represents a specific geographical location related to agricultural ac... |  yes  |







## Properties

* Range: [SockgCountry](../classes/SockgCountry.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Site | sockg_Country | sockg:individuals/231056 | sockg:individuals/46901 | 60 |




## LinkML Source

<details>

```yaml
name: sockg_locatedInCountry
annotations:
  count:
    tag: count
    value: 60
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/46901
    example_object_type: sockg_Country
    example_predicate: sockg:locatedInCountry
    example_subject: sockg:individuals/231056
    example_subject_type: sockg_Site
from_schema: soc-kg
rank: 1000
domain: sockg_Site
slot_uri: sockg:locatedInCountry
alias: sockg_locatedInCountry
domain_of:
- sockg_Site
range: sockg_Country

```
</details>