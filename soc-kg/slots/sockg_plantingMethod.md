

# Slot: No slot (predicate) name specified (sockg_plantingMethod)


_No slot (predicate) description specified_






This slot occurs 22314 times.


URI: [sockg:plantingMethod](https://idir.uta.edu/sockg-ontology/docs/plantingMethod)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPlantingEvent](../classes/SockgPlantingEvent.md) | An event involving the act of planting, which includes considerations for spa... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_PlantingEvent | string | sockg:individuals/203988 | Broadcast | 22314 |


## See Also

* [https://lod.nal.usda.gov/nalt/33957](https://lod.nal.usda.gov/nalt/33957)



## LinkML Source

<details>

```yaml
name: sockg_plantingMethod
annotations:
  count:
    tag: count
    value: 22314
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Broadcast
    example_object_type: string
    example_predicate: sockg:plantingMethod
    example_subject: sockg:individuals/203988
    example_subject_type: sockg_PlantingEvent
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/33957
rank: 1000
domain: sockg_PlantingEvent
slot_uri: sockg:plantingMethod
alias: sockg_plantingMethod
domain_of:
- sockg_PlantingEvent
range: string

```
</details>