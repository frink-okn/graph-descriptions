

# Slot: No slot (predicate) name specified (sockg_nitrateNitrogen_kg_ha)


_No slot (predicate) description specified_






This slot occurs 667 times.


URI: [sockg:nitrateNitrogen_kg_ha](https://idir.uta.edu/sockg-ontology/docs/nitrateNitrogen_kg_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | A WaterQualityArea represents a designated agricultural zone where water qual... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WaterQualityArea | double | sockg:individuals/364326 | 0.02023422 | 667 |




## LinkML Source

<details>

```yaml
name: sockg_nitrateNitrogen_kg_ha
annotations:
  count:
    tag: count
    value: 667
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.02023422'
    example_object_type: double
    example_predicate: sockg:nitrateNitrogen_kg_ha
    example_subject: sockg:individuals/364326
    example_subject_type: sockg_WaterQualityArea
from_schema: soc-kg
rank: 1000
domain: sockg_WaterQualityArea
slot_uri: sockg:nitrateNitrogen_kg_ha
alias: sockg_nitrateNitrogen_kg_ha
domain_of:
- sockg_WaterQualityArea
range: Any
any_of:
- range: float
- range: double

```
</details>