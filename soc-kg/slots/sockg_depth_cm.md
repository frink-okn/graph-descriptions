

# Slot: No slot (predicate) name specified (sockg_depth_cm)


_No slot (predicate) description specified_






This slot occurs 20535 times.


URI: [sockg:depth_cm](https://idir.uta.edu/sockg-ontology/docs/depth_cm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPlantingEvent](../classes/SockgPlantingEvent.md) | An event involving the act of planting, which includes considerations for spa... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_PlantingEvent | double | sockg:individuals/203988 | 0.0 | 20535 |


## See Also

* [https://lod.nal.usda.gov/nalt/305177](https://lod.nal.usda.gov/nalt/305177)



## LinkML Source

<details>

```yaml
name: sockg_depth_cm
annotations:
  count:
    tag: count
    value: 20535
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.0'
    example_object_type: double
    example_predicate: sockg:depth_cm
    example_subject: sockg:individuals/203988
    example_subject_type: sockg_PlantingEvent
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/305177
rank: 1000
slot_uri: sockg:depth_cm
alias: sockg_depth_cm
domain_of:
- sockg_PlantingEvent
union_of:
- '{''domain'': ''sockg_Amendment''}'
- '{''domain'': ''sockg_PlantingEvent''}'
range: Any
any_of:
- range: integer
- range: double
- range: float

```
</details>