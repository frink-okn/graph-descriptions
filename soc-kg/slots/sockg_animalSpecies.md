

# Slot: No slot (predicate) name specified (sockg_animalSpecies)


_No slot (predicate) description specified_






This slot occurs 1951 times.


URI: [sockg:animalSpecies](https://idir.uta.edu/sockg-ontology/docs/animalSpecies)



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
| sockg_GrazingManagementEvent | string | sockg:individuals/170955 | Beef Cattle | 1951 |


## See Also

* [https://lod.nal.usda.gov/nalt/65](https://lod.nal.usda.gov/nalt/65)



## LinkML Source

<details>

```yaml
name: sockg_animalSpecies
annotations:
  count:
    tag: count
    value: 1951
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Beef Cattle
    example_object_type: string
    example_predicate: sockg:animalSpecies
    example_subject: sockg:individuals/170955
    example_subject_type: sockg_GrazingManagementEvent
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/65
rank: 1000
domain: sockg_GrazingManagementEvent
slot_uri: sockg:animalSpecies
alias: sockg_animalSpecies
domain_of:
- sockg_GrazingManagementEvent
range: string

```
</details>