

# Slot: No slot (predicate) name specified (sockg_soil_t_ha)


_No slot (predicate) description specified_






This slot occurs 15 times.


URI: [sockg:soil_t_ha](https://idir.uta.edu/sockg-ontology/docs/soil_t_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detail... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WindErosionArea | double | sockg:individuals/624572 | 987.2 | 15 |




## LinkML Source

<details>

```yaml
name: sockg_soil_t_ha
annotations:
  count:
    tag: count
    value: 15
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '987.2'
    example_object_type: double
    example_predicate: sockg:soil_t_ha
    example_subject: sockg:individuals/624572
    example_subject_type: sockg_WindErosionArea
from_schema: soc-kg
rank: 1000
domain: sockg_WindErosionArea
slot_uri: sockg:soil_t_ha
alias: sockg_soil_t_ha
domain_of:
- sockg_WindErosionArea
range: Any
any_of:
- range: float
- range: double

```
</details>