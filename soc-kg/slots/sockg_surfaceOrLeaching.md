

# Slot: No slot (predicate) name specified (sockg_surfaceOrLeaching)


_No slot (predicate) description specified_






This slot occurs 2146 times.


URI: [sockg:surfaceOrLeaching](https://idir.uta.edu/sockg-ontology/docs/surfaceOrLeaching)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parame... |  yes  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | A WaterQualityArea represents a designated agricultural zone where water qual... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WaterQualityArea | string | sockg:individuals/364326 | Surface | 667 |
| sockg_WaterQualityConc | string | sockg:individuals/364993 | Leaching | 1479 |




## LinkML Source

<details>

```yaml
name: sockg_surfaceOrLeaching
annotations:
  count:
    tag: count
    value: 2146
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Surface
    example_object_type: string
    example_predicate: sockg:surfaceOrLeaching
    example_subject: sockg:individuals/364326
    example_subject_type: sockg_WaterQualityArea
- object:
    example_object: Leaching
    example_object_type: string
    example_predicate: sockg:surfaceOrLeaching
    example_subject: sockg:individuals/364993
    example_subject_type: sockg_WaterQualityConc
from_schema: soc-kg
rank: 1000
slot_uri: sockg:surfaceOrLeaching
alias: sockg_surfaceOrLeaching
domain_of:
- sockg_WaterQualityArea
- sockg_WaterQualityConc
union_of:
- '{''domain'': ''sockg_WaterQualityArea''}'
- '{''domain'': ''sockg_WaterQualityConc''}'
range: string

```
</details>