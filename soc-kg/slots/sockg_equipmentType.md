

# Slot: No slot (predicate) name specified (sockg_equipmentType)


_No slot (predicate) description specified_






This slot occurs 3044 times.


URI: [sockg:equipmentType](https://idir.uta.edu/sockg-ontology/docs/equipmentType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgResidueManagementEvent](../classes/SockgResidueManagementEvent.md) | A ResidueManagementEvent represents a specific instance of managing agricultu... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ResidueManagementEvent | string | sockg:individuals/227674 | Single Row Forage Harvester | 3044 |


## See Also

* [https://lod.nal.usda.gov/nalt/5401](https://lod.nal.usda.gov/nalt/5401)



## LinkML Source

<details>

```yaml
name: sockg_equipmentType
annotations:
  count:
    tag: count
    value: 3044
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Single Row Forage Harvester
    example_object_type: string
    example_predicate: sockg:equipmentType
    example_subject: sockg:individuals/227674
    example_subject_type: sockg_ResidueManagementEvent
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/5401
rank: 1000
domain: sockg_ResidueManagementEvent
slot_uri: sockg:equipmentType
alias: sockg_equipmentType
domain_of:
- sockg_ResidueManagementEvent
range: string

```
</details>