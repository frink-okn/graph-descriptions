

# Slot: No slot (predicate) name specified (sockg_hasCounty)


_No slot (predicate) description specified_






This slot occurs 33 times.


URI: [sockg:hasCounty](https://idir.uta.edu/sockg-ontology/docs/hasCounty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgState](../classes/SockgState.md) | A State represents a regional jurisdiction within a country, often defined by... |  yes  |







## Properties

* Range: [SockgCounty](../classes/SockgCounty.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_State | sockg_County | sockg:individuals/336400 | sockg:individuals/46904 | 33 |




## LinkML Source

<details>

```yaml
name: sockg_hasCounty
annotations:
  count:
    tag: count
    value: 33
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/46904
    example_object_type: sockg_County
    example_predicate: sockg:hasCounty
    example_subject: sockg:individuals/336400
    example_subject_type: sockg_State
from_schema: soc-kg
rank: 1000
domain: sockg_State
slot_uri: sockg:hasCounty
alias: sockg_hasCounty
domain_of:
- sockg_State
range: sockg_County

```
</details>