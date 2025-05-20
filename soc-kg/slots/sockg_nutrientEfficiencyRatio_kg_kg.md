

# Slot: No slot (predicate) name specified (sockg_nutrientEfficiencyRatio_kg_kg)


_No slot (predicate) description specified_






This slot occurs 2569 times.


URI: [sockg:nutrientEfficiencyRatio_kg_kg](https://idir.uta.edu/sockg-ontology/docs/nutrientEfficiencyRatio_kg_kg)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | The NutrientEfficiency class represents the effectiveness of nutrient utiliza... |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_NutrientEfficiency | double | sockg:individuals/200732 | 2.098475 | 2569 |




## LinkML Source

<details>

```yaml
name: sockg_nutrientEfficiencyRatio_kg_kg
annotations:
  count:
    tag: count
    value: 2569
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '2.098475'
    example_object_type: double
    example_predicate: sockg:nutrientEfficiencyRatio_kg_kg
    example_subject: sockg:individuals/200732
    example_subject_type: sockg_NutrientEfficiency
from_schema: soc-kg
rank: 1000
domain: sockg_NutrientEfficiency
slot_uri: sockg:nutrientEfficiencyRatio_kg_kg
alias: sockg_nutrientEfficiencyRatio_kg_kg
domain_of:
- sockg_NutrientEfficiency
range: Any
any_of:
- range: double
- range: float

```
</details>