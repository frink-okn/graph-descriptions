

# Slot: No slot (predicate) name specified (sockg_fracMoisturePercent)


_No slot (predicate) description specified_






This slot occurs 20 times.


URI: [sockg:fracMoisturePercent](https://idir.uta.edu/sockg-ontology/docs/fracMoisturePercent)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | The YieldNutrientUptake class represents the assessment of nutrient uptake by... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_YieldNutrientUptake | double | sockg:individuals/624926 | 25.8 | 20 |




## LinkML Source

<details>

```yaml
name: sockg_fracMoisturePercent
annotations:
  count:
    tag: count
    value: 20
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '25.8'
    example_object_type: double
    example_predicate: sockg:fracMoisturePercent
    example_subject: sockg:individuals/624926
    example_subject_type: sockg_YieldNutrientUptake
from_schema: soc-kg
rank: 1000
domain: sockg_YieldNutrientUptake
slot_uri: sockg:fracMoisturePercent
alias: sockg_fracMoisturePercent
domain_of:
- sockg_YieldNutrientUptake
range: Any
any_of:
- range: float
- range: double

```
</details>