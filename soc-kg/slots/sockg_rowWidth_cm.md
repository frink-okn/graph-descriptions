

# Slot: No slot (predicate) name specified (sockg_rowWidth_cm)


_No slot (predicate) description specified_






This slot occurs 23450 times.


URI: [sockg:rowWidth_cm](https://idir.uta.edu/sockg-ontology/docs/rowWidth_cm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPlantingEvent](../classes/SockgPlantingEvent.md) | An event involving the act of planting, which includes considerations for spa... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_PlantingEvent | double | sockg:individuals/203988 | 0.0 | 23450 |


## See Also

* [https://lod.nal.usda.gov/nalt/58548](https://lod.nal.usda.gov/nalt/58548)



## LinkML Source

<details>

```yaml
name: sockg_rowWidth_cm
annotations:
  count:
    tag: count
    value: 23450
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.0'
    example_object_type: double
    example_predicate: sockg:rowWidth_cm
    example_subject: sockg:individuals/203988
    example_subject_type: sockg_PlantingEvent
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/58548
rank: 1000
domain: sockg_PlantingEvent
slot_uri: sockg:rowWidth_cm
alias: sockg_rowWidth_cm
domain_of:
- sockg_PlantingEvent
range: Any
any_of:
- range: double
- range: float

```
</details>