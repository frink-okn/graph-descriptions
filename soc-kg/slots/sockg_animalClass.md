

# Slot: No slot (predicate) name specified (sockg_animalClass)


_No slot (predicate) description specified_






This slot occurs 1833 times.


URI: [sockg:animalClass](https://idir.uta.edu/sockg-ontology/docs/animalClass)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGrazingManagementEvent](../classes/SockgGrazingManagementEvent.md) | A GrazingManagementEvent represents a specific instance of land management pr... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GrazingManagementEvent | string | sockg:individuals/170961 | Neutered male | 1833 |


## See Also

* [https://lod.nal.usda.gov/nalt/4377260](https://lod.nal.usda.gov/nalt/4377260)



## LinkML Source

<details>

```yaml
name: sockg_animalClass
annotations:
  count:
    tag: count
    value: 1833
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Neutered male
    example_object_type: string
    example_predicate: sockg:animalClass
    example_subject: sockg:individuals/170961
    example_subject_type: sockg_GrazingManagementEvent
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/4377260
rank: 1000
domain: sockg_GrazingManagementEvent
slot_uri: sockg:animalClass
alias: sockg_animalClass
domain_of:
- sockg_GrazingManagementEvent
range: string

```
</details>