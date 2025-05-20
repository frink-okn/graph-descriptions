

# Slot: No slot (predicate) name specified (sockg_water_mm)


_No slot (predicate) description specified_






This slot occurs 2146 times.


URI: [sockg:water_mm](https://idir.uta.edu/sockg-ontology/docs/water_mm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parame... |  yes  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | A WaterQualityArea represents a designated agricultural zone where water qual... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WaterQualityArea | double | sockg:individuals/364326 | 33.61166 | 667 |
| sockg_WaterQualityConc | double | sockg:individuals/364993 | 70.85973 | 1479 |




## LinkML Source

<details>

```yaml
name: sockg_water_mm
annotations:
  count:
    tag: count
    value: 2146
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '33.61166'
    example_object_type: double
    example_predicate: sockg:water_mm
    example_subject: sockg:individuals/364326
    example_subject_type: sockg_WaterQualityArea
- object:
    example_object: '70.85973'
    example_object_type: double
    example_predicate: sockg:water_mm
    example_subject: sockg:individuals/364993
    example_subject_type: sockg_WaterQualityConc
from_schema: soc-kg
rank: 1000
domain: sockg_WaterQualityConc
slot_uri: sockg:water_mm
alias: sockg_water_mm
domain_of:
- sockg_WaterQualityArea
- sockg_WaterQualityConc
range: Any
any_of:
- range: double
- range: float

```
</details>