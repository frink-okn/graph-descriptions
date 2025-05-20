

# Slot: No slot (predicate) name specified (sockg_locatedInState)


_No slot (predicate) description specified_






This slot occurs 60 times.


URI: [sockg:locatedInState](https://idir.uta.edu/sockg-ontology/docs/locatedInState)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSite](../classes/SockgSite.md) | A Site represents a specific geographical location related to agricultural ac... |  yes  |







## Properties

* Range: [SockgState](../classes/SockgState.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Site | sockg_State | sockg:individuals/231056 | sockg:individuals/336400 | 60 |




## LinkML Source

<details>

```yaml
name: sockg_locatedInState
annotations:
  count:
    tag: count
    value: 60
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/336400
    example_object_type: sockg_State
    example_predicate: sockg:locatedInState
    example_subject: sockg:individuals/231056
    example_subject_type: sockg_Site
from_schema: soc-kg
rank: 1000
domain: sockg_Site
slot_uri: sockg:locatedInState
alias: sockg_locatedInState
domain_of:
- sockg_Site
range: sockg_State

```
</details>