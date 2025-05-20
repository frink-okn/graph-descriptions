

# Slot: No slot (predicate) name specified (sockg_totalDissolvedPhosphorus_kgP_ha)


_No slot (predicate) description specified_






This slot occurs 667 times.


URI: [sockg:totalDissolvedPhosphorus_kgP_ha](https://idir.uta.edu/sockg-ontology/docs/totalDissolvedPhosphorus_kgP_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | A WaterQualityArea represents a designated agricultural zone where water qual... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WaterQualityArea | double | sockg:individuals/364326 | 1.409174 | 667 |




## LinkML Source

<details>

```yaml
name: sockg_totalDissolvedPhosphorus_kgP_ha
annotations:
  count:
    tag: count
    value: 667
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '1.409174'
    example_object_type: double
    example_predicate: sockg:totalDissolvedPhosphorus_kgP_ha
    example_subject: sockg:individuals/364326
    example_subject_type: sockg_WaterQualityArea
from_schema: soc-kg
rank: 1000
domain: sockg_WaterQualityArea
slot_uri: sockg:totalDissolvedPhosphorus_kgP_ha
alias: sockg_totalDissolvedPhosphorus_kgP_ha
domain_of:
- sockg_WaterQualityArea
range: Any
any_of:
- range: double
- range: float

```
</details>