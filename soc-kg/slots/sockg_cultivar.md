

# Slot: No slot (predicate) name specified (sockg_cultivar)


_No slot (predicate) description specified_






This slot occurs 20817 times.


URI: [sockg:cultivar](https://idir.uta.edu/sockg-ontology/docs/cultivar)



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
| sockg_PlantingEvent | string | sockg:individuals/203988 | Rye | 20817 |


## See Also

* [https://lod.nal.usda.gov/nalt/5630](https://lod.nal.usda.gov/nalt/5630)



## LinkML Source

<details>

```yaml
name: sockg_cultivar
annotations:
  count:
    tag: count
    value: 20817
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Rye
    example_object_type: string
    example_predicate: sockg:cultivar
    example_subject: sockg:individuals/203988
    example_subject_type: sockg_PlantingEvent
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/5630
rank: 1000
domain: sockg_PlantingEvent
slot_uri: sockg:cultivar
alias: sockg_cultivar
domain_of:
- sockg_PlantingEvent
range: string

```
</details>