

# Slot: No slot (predicate) name specified (sockg_fracManganese_gMn_ha)


_No slot (predicate) description specified_






This slot occurs 20 times.


URI: [sockg:fracManganese_gMn_ha](https://idir.uta.edu/sockg-ontology/docs/fracManganese_gMn_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | The YieldNutrientUptake class represents the assessment of nutrient uptake by... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_YieldNutrientUptake | double | sockg:individuals/624996 | 6.586922 | 20 |




## LinkML Source

<details>

```yaml
name: sockg_fracManganese_gMn_ha
annotations:
  count:
    tag: count
    value: 20
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '6.586922'
    example_object_type: double
    example_predicate: sockg:fracManganese_gMn_ha
    example_subject: sockg:individuals/624996
    example_subject_type: sockg_YieldNutrientUptake
from_schema: soc-kg
rank: 1000
domain: sockg_YieldNutrientUptake
slot_uri: sockg:fracManganese_gMn_ha
alias: sockg_fracManganese_gMn_ha
domain_of:
- sockg_YieldNutrientUptake
range: Any
any_of:
- range: double
- range: float

```
</details>