

# Slot: No slot (predicate) name specified (sockg_expUnit_UID)


_No slot (predicate) description specified_






This slot occurs 9992 times.


URI: [sockg:expUnit_UID](https://idir.uta.edu/sockg-ontology/docs/expUnit_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | The YieldNutrientUptake class represents the assessment of nutrient uptake by... |  yes  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | A WaterQualityArea represents a designated agricultural zone where water qual... |  yes  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | The GasNutrientLoss class represents the assessment of gaseous nutrient losse... |  yes  |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parame... |  yes  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detail... |  yes  |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | The NutrientEfficiency class represents the effectiveness of nutrient utiliza... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ExperimentalUnit | string | sockg:individuals/51937 | AgCros_MTSIFERE_GrazW-P_B-F3w2 | 3863 |
| sockg_NutrientEfficiency | string | sockg:individuals/200732 | AgCros_MNMOCAL_614 | 2791 |
| sockg_WaterQualityArea | string | sockg:individuals/364326 | AgCros_WIPDBARN_2 | 667 |
| sockg_WaterQualityConc | string | sockg:individuals/364993 | AgCros_IAAMKELL_120 | 1479 |
| sockg_GasNutrientLoss | string | sockg:individuals/55858 | AgCros_IAAMKELL_116 | 748 |
| sockg_WindErosionArea | string | sockg:individuals/624572 | AgCros_TXBSWEWC_COMP2 | 15 |
| sockg_YieldNutrientUptake | string | sockg:individuals/624587 | AgCros_MNSP4R_U-S100B | 429 |




## LinkML Source

<details>

```yaml
name: sockg_expUnit_UID
annotations:
  count:
    tag: count
    value: 9992
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AgCros_MTSIFERE_GrazW-P_B-F3w2
    example_object_type: string
    example_predicate: sockg:expUnit_UID
    example_subject: sockg:individuals/51937
    example_subject_type: sockg_ExperimentalUnit
- object:
    example_object: AgCros_MNMOCAL_614
    example_object_type: string
    example_predicate: sockg:expUnit_UID
    example_subject: sockg:individuals/200732
    example_subject_type: sockg_NutrientEfficiency
- object:
    example_object: AgCros_WIPDBARN_2
    example_object_type: string
    example_predicate: sockg:expUnit_UID
    example_subject: sockg:individuals/364326
    example_subject_type: sockg_WaterQualityArea
- object:
    example_object: AgCros_IAAMKELL_120
    example_object_type: string
    example_predicate: sockg:expUnit_UID
    example_subject: sockg:individuals/364993
    example_subject_type: sockg_WaterQualityConc
- object:
    example_object: AgCros_IAAMKELL_116
    example_object_type: string
    example_predicate: sockg:expUnit_UID
    example_subject: sockg:individuals/55858
    example_subject_type: sockg_GasNutrientLoss
- object:
    example_object: AgCros_TXBSWEWC_COMP2
    example_object_type: string
    example_predicate: sockg:expUnit_UID
    example_subject: sockg:individuals/624572
    example_subject_type: sockg_WindErosionArea
- object:
    example_object: AgCros_MNSP4R_U-S100B
    example_object_type: string
    example_predicate: sockg:expUnit_UID
    example_subject: sockg:individuals/624587
    example_subject_type: sockg_YieldNutrientUptake
from_schema: soc-kg
rank: 1000
slot_uri: sockg:expUnit_UID
alias: sockg_expUnit_UID
domain_of:
- sockg_ExperimentalUnit
- sockg_GasNutrientLoss
- sockg_NutrientEfficiency
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
- sockg_YieldNutrientUptake
union_of:
- '{''domain'': ''sockg_ExperimentalUnit''}'
- '{''domain'': ''sockg_NutrientEfficiency''}'
- '{''domain'': ''sockg_WaterQualityConc''}'
- '{''domain'': ''sockg_WindErosionArea''}'
- '{''domain'': ''sockg_GasNutrientLoss''}'
- '{''domain'': ''sockg_YieldNutrientUptake''}'
range: string

```
</details>