

# Slot: No slot (predicate) name specified (sockg_nitrousOxide_g_ha)


_No slot (predicate) description specified_






This slot occurs 748 times.


URI: [sockg:nitrousOxide_g_ha](https://idir.uta.edu/sockg-ontology/docs/nitrousOxide_g_ha)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | The GasNutrientLoss class represents the assessment of gaseous nutrient losse... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_GasNutrientLoss | double | sockg:individuals/55858 | 10.36667 | 748 |




## LinkML Source

<details>

```yaml
name: sockg_nitrousOxide_g_ha
annotations:
  count:
    tag: count
    value: 748
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '10.36667'
    example_object_type: double
    example_predicate: sockg:nitrousOxide_g_ha
    example_subject: sockg:individuals/55858
    example_subject_type: sockg_GasNutrientLoss
from_schema: soc-kg
rank: 1000
domain: sockg_GasNutrientLoss
slot_uri: sockg:nitrousOxide_g_ha
alias: sockg_nitrousOxide_g_ha
domain_of:
- sockg_GasNutrientLoss
range: Any
any_of:
- range: float
- range: double

```
</details>