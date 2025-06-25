

# Slot: No slot (predicate) name specified (sockg_modelIfSimulated)


_No slot (predicate) description specified_






This slot occurs 861 times.


URI: [sockg:modelIfSimulated](https://idir.uta.edu/sockg-ontology/docs/modelIfSimulated)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parame... |  yes  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | The GasNutrientLoss class represents the assessment of gaseous nutrient losse... |  yes  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detail... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_WaterQualityConc | string | sockg:individuals/364993 | RZWQM | 798 |
| sockg_GasNutrientLoss | string | sockg:individuals/55858 | RZWQM | 56 |
| sockg_WindErosionArea | string | sockg:individuals/624572 | Linear Proportional | 7 |




## LinkML Source

<details>

```yaml
name: sockg_modelIfSimulated
annotations:
  count:
    tag: count
    value: 861
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: RZWQM
    example_object_type: string
    example_predicate: sockg:modelIfSimulated
    example_subject: sockg:individuals/364993
    example_subject_type: sockg_WaterQualityConc
- object:
    example_object: RZWQM
    example_object_type: string
    example_predicate: sockg:modelIfSimulated
    example_subject: sockg:individuals/55858
    example_subject_type: sockg_GasNutrientLoss
- object:
    example_object: Linear Proportional
    example_object_type: string
    example_predicate: sockg:modelIfSimulated
    example_subject: sockg:individuals/624572
    example_subject_type: sockg_WindErosionArea
from_schema: soc-kg
rank: 1000
slot_uri: sockg:modelIfSimulated
alias: sockg_modelIfSimulated
domain_of:
- sockg_GasNutrientLoss
- sockg_WaterQualityConc
- sockg_WindErosionArea
union_of:
- '{''domain'': ''sockg_WaterQualityArea''}'
- '{''domain'': ''sockg_WindErosionArea''}'
- '{''domain'': ''sockg_WaterQualityConc''}'
- '{''domain'': ''sockg_GasNutrientLoss''}'
- '{''domain'': ''sockg_YieldNutrientUptake''}'
range: string

```
</details>