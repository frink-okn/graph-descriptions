

# Slot: No slot (predicate) name specified (sockg_nitrogenUseEfficiencyPct)


_No slot (predicate) description specified_






This slot occurs 2791 times.


URI: [sockg:nitrogenUseEfficiencyPct](https://idir.uta.edu/sockg-ontology/docs/nitrogenUseEfficiencyPct)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | The NutrientEfficiency class represents the effectiveness of nutrient utiliza... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_NutrientEfficiency | double | sockg:individuals/200732 | 0.0 | 2791 |




## LinkML Source

<details>

```yaml
name: sockg_nitrogenUseEfficiencyPct
annotations:
  count:
    tag: count
    value: 2791
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '0.0'
    example_object_type: double
    example_predicate: sockg:nitrogenUseEfficiencyPct
    example_subject: sockg:individuals/200732
    example_subject_type: sockg_NutrientEfficiency
from_schema: soc-kg
rank: 1000
domain: sockg_NutrientEfficiency
slot_uri: sockg:nitrogenUseEfficiencyPct
alias: sockg_nitrogenUseEfficiencyPct
domain_of:
- sockg_NutrientEfficiency
range: Any
any_of:
- range: float
- range: double

```
</details>