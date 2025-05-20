

# Slot: No slot (predicate) name specified (sockg_samplingDepth_cm)


_No slot (predicate) description specified_






This slot occurs 1479 times.


URI: [sockg:samplingDepth_cm](https://idir.uta.edu/sockg-ontology/docs/samplingDepth_cm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parame... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WaterQualityConc | integer | sockg:individuals/364993 | 120 | 1479 |




## LinkML Source

<details>

```yaml
name: sockg_samplingDepth_cm
annotations:
  count:
    tag: count
    value: 1479
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '120'
    example_object_type: integer
    example_predicate: sockg:samplingDepth_cm
    example_subject: sockg:individuals/364993
    example_subject_type: sockg_WaterQualityConc
from_schema: soc-kg
rank: 1000
slot_uri: sockg:samplingDepth_cm
alias: sockg_samplingDepth_cm
domain_of:
- sockg_WaterQualityConc
union_of:
- '{''domain'': ''sockg_WaterQualityArea''}'
- '{''domain'': ''sockg_WaterQualityConc''}'
range: Any
any_of:
- range: integer
- range: float

```
</details>