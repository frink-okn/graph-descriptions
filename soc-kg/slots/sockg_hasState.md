

# Slot: No slot (predicate) name specified (sockg_hasState)


_No slot (predicate) description specified_






This slot occurs 19 times.


URI: [sockg:hasState](https://idir.uta.edu/sockg-ontology/docs/hasState)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgCountry](../classes/SockgCountry.md) | A Country is a distinct territorial body with its own government and borders,... |  yes  |







## Properties

* Range: [SockgState](../classes/SockgState.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Country | sockg_State | sockg:individuals/46901 | sockg:individuals/336400 | 19 |




## LinkML Source

<details>

```yaml
name: sockg_hasState
annotations:
  count:
    tag: count
    value: 19
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: sockg:individuals/336400
    example_object_type: sockg_State
    example_predicate: sockg:hasState
    example_subject: sockg:individuals/46901
    example_subject_type: sockg_Country
from_schema: soc-kg
rank: 1000
domain: sockg_Country
slot_uri: sockg:hasState
alias: sockg_hasState
domain_of:
- sockg_Country
range: sockg_State

```
</details>