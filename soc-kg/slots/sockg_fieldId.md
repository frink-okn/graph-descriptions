

# Slot: No slot (predicate) name specified (sockg_fieldId)


_No slot (predicate) description specified_






This slot occurs 6187 times.


URI: [sockg:fieldId](https://idir.uta.edu/sockg-ontology/docs/fieldId)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | The YieldNutrientUptake class represents the assessment of nutrient uptake by... |  yes  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | A WaterQualityArea represents a designated agricultural zone where water qual... |  yes  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | The GasNutrientLoss class represents the assessment of gaseous nutrient losse... |  yes  |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parame... |  yes  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detail... |  yes  |
| [SockgField](../classes/SockgField.md) | A Field represents a specific area of land used for agricultural purposes, wh... |  yes  |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | The NutrientEfficiency class represents the effectiveness of nutrient utiliza... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Field | string | sockg:individuals/55800 | ALAUSDR | 58 |
| sockg_NutrientEfficiency | string | sockg:individuals/200732 | MNMOCAL | 2791 |
| sockg_WaterQualityArea | string | sockg:individuals/364326 | WIPDBARN | 667 |
| sockg_WaterQualityConc | string | sockg:individuals/364993 | IAAMKELL | 1479 |
| sockg_GasNutrientLoss | string | sockg:individuals/55858 | IAAMKELL | 748 |
| sockg_WindErosionArea | string | sockg:individuals/624572 | TXBSWEWC | 15 |
| sockg_YieldNutrientUptake | string | sockg:individuals/624587 | MNSP4R | 429 |




## LinkML Source

<details>

```yaml
name: sockg_fieldId
annotations:
  count:
    tag: count
    value: 6187
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: ALAUSDR
    example_object_type: string
    example_predicate: sockg:fieldId
    example_subject: sockg:individuals/55800
    example_subject_type: sockg_Field
- object:
    example_object: MNMOCAL
    example_object_type: string
    example_predicate: sockg:fieldId
    example_subject: sockg:individuals/200732
    example_subject_type: sockg_NutrientEfficiency
- object:
    example_object: WIPDBARN
    example_object_type: string
    example_predicate: sockg:fieldId
    example_subject: sockg:individuals/364326
    example_subject_type: sockg_WaterQualityArea
- object:
    example_object: IAAMKELL
    example_object_type: string
    example_predicate: sockg:fieldId
    example_subject: sockg:individuals/364993
    example_subject_type: sockg_WaterQualityConc
- object:
    example_object: IAAMKELL
    example_object_type: string
    example_predicate: sockg:fieldId
    example_subject: sockg:individuals/55858
    example_subject_type: sockg_GasNutrientLoss
- object:
    example_object: TXBSWEWC
    example_object_type: string
    example_predicate: sockg:fieldId
    example_subject: sockg:individuals/624572
    example_subject_type: sockg_WindErosionArea
- object:
    example_object: MNSP4R
    example_object_type: string
    example_predicate: sockg:fieldId
    example_subject: sockg:individuals/624587
    example_subject_type: sockg_YieldNutrientUptake
from_schema: soc-kg
rank: 1000
slot_uri: sockg:fieldId
alias: sockg_fieldId
domain_of:
- sockg_Field
- sockg_GasNutrientLoss
- sockg_NutrientEfficiency
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
- sockg_YieldNutrientUptake
union_of:
- '{''domain'': ''sockg_WaterQualityArea''}'
- '{''domain'': ''sockg_NutrientEfficiency''}'
- '{''domain'': ''sockg_Field''}'
- '{''domain'': ''sockg_WaterQualityConc''}'
- '{''domain'': ''sockg_WindErosionArea''}'
- '{''domain'': ''sockg_GasNutrientLoss''}'
- '{''domain'': ''sockg_YieldNutrientUptake''}'
range: string

```
</details>