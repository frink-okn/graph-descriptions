

# Slot: No slot (predicate) name specified (sockg_countyName)


_No slot (predicate) description specified_






This slot occurs 33 times.


URI: [sockg:countyName](https://idir.uta.edu/sockg-ontology/docs/countyName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgCounty](../classes/SockgCounty.md) | A County represents a specific geographical area within a state, often encomp... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_County | string | sockg:individuals/46904 | Macon | 33 |


## See Also

* [https://lod.nal.usda.gov/nalt/2217129](https://lod.nal.usda.gov/nalt/2217129)



## LinkML Source

<details>

```yaml
name: sockg_countyName
annotations:
  count:
    tag: count
    value: 33
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Macon
    example_object_type: string
    example_predicate: sockg:countyName
    example_subject: sockg:individuals/46904
    example_subject_type: sockg_County
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/2217129
rank: 1000
domain: sockg_County
slot_uri: sockg:countyName
alias: sockg_countyName
domain_of:
- sockg_County
range: string

```
</details>