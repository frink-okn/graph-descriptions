

# Slot: No slot (predicate) name specified (sockg_stateProvince)


_No slot (predicate) description specified_






This slot occurs 19 times.


URI: [sockg:stateProvince](https://idir.uta.edu/sockg-ontology/docs/stateProvince)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgState](../classes/SockgState.md) | A State represents a regional jurisdiction within a country, often defined by... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_State | string | sockg:individuals/336400 | AL | 19 |


## See Also

* [https://lod.nal.usda.gov/nalt/5430914](https://lod.nal.usda.gov/nalt/5430914)



## LinkML Source

<details>

```yaml
name: sockg_stateProvince
annotations:
  count:
    tag: count
    value: 19
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AL
    example_object_type: string
    example_predicate: sockg:stateProvince
    example_subject: sockg:individuals/336400
    example_subject_type: sockg_State
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/5430914
rank: 1000
domain: sockg_State
slot_uri: sockg:stateProvince
alias: sockg_stateProvince
domain_of:
- sockg_State
range: string

```
</details>