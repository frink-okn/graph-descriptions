

# Slot: No slot (predicate) name specified (sockg_lossesOrDeposition)


_No slot (predicate) description specified_






This slot occurs 139 times.


URI: [sockg:lossesOrDeposition](https://idir.uta.edu/sockg-ontology/docs/lossesOrDeposition)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detail... |  yes  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | A WaterQualityArea represents a designated agricultural zone where water qual... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WaterQualityArea | string | sockg:individuals/364326 | Deposition | 132 |
| sockg_WindErosionArea | string | sockg:individuals/624572 | Losses | 7 |




## LinkML Source

<details>

```yaml
name: sockg_lossesOrDeposition
annotations:
  count:
    tag: count
    value: 139
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Deposition
    example_object_type: string
    example_predicate: sockg:lossesOrDeposition
    example_subject: sockg:individuals/364326
    example_subject_type: sockg_WaterQualityArea
- object:
    example_object: Losses
    example_object_type: string
    example_predicate: sockg:lossesOrDeposition
    example_subject: sockg:individuals/624572
    example_subject_type: sockg_WindErosionArea
from_schema: soc-kg
rank: 1000
slot_uri: sockg:lossesOrDeposition
alias: sockg_lossesOrDeposition
domain_of:
- sockg_WaterQualityArea
- sockg_WindErosionArea
union_of:
- '{''domain'': ''sockg_WaterQualityArea''}'
- '{''domain'': ''sockg_WindErosionArea''}'
range: Any
any_of:
- range: float
- range: string

```
</details>