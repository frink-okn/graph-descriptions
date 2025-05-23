

# Slot: No slot (predicate) name specified (sockg_expUnitId)


_No slot (predicate) description specified_






This slot occurs 33442 times.


URI: [sockg:expUnitId](https://idir.uta.edu/sockg-ontology/docs/expUnitId)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parame... |  yes  |
| [SockgPlantingEvent](../classes/SockgPlantingEvent.md) | An event involving the act of planting, which includes considerations for spa... |  yes  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | The GasNutrientLoss class represents the assessment of gaseous nutrient losse... |  yes  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detail... |  yes  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | A WaterQualityArea represents a designated agricultural zone where water qual... |  yes  |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | The YieldNutrientUptake class represents the assessment of nutrient uptake by... |  yes  |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | An ExperimentalUnit represents a specific segment of agricultural research fo... |  yes  |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | The NutrientEfficiency class represents the effectiveness of nutrient utiliza... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_ExperimentalUnit | string | sockg:individuals/51937 | MTSIFERE_GrazW-P/B-F3w2 | 3863 |
| sockg_NutrientEfficiency | string | sockg:individuals/200732 | MNMOCAL_614 | 2791 |
| sockg_PlantingEvent | string | sockg:individuals/203988 | MNMOFS_71 | 23450 |
| sockg_WaterQualityArea | string | sockg:individuals/364326 | WIPDBARN_2 | 667 |
| sockg_WaterQualityConc | string | sockg:individuals/364993 | IAAMKELL__120 | 1479 |
| sockg_GasNutrientLoss | string | sockg:individuals/55858 | IAAMKELL__116 | 748 |
| sockg_WindErosionArea | string | sockg:individuals/624572 | TXBSWEWC_COMP2 | 15 |
| sockg_YieldNutrientUptake | string | sockg:individuals/624587 | MNSP4R_U-S100B | 429 |


## See Also

* [https://lod.nal.usda.gov/nalt/849](https://lod.nal.usda.gov/nalt/849)



## LinkML Source

<details>

```yaml
name: sockg_expUnitId
annotations:
  count:
    tag: count
    value: 33442
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: MTSIFERE_GrazW-P/B-F3w2
    example_object_type: string
    example_predicate: sockg:expUnitId
    example_subject: sockg:individuals/51937
    example_subject_type: sockg_ExperimentalUnit
- object:
    example_object: MNMOCAL_614
    example_object_type: string
    example_predicate: sockg:expUnitId
    example_subject: sockg:individuals/200732
    example_subject_type: sockg_NutrientEfficiency
- object:
    example_object: MNMOFS_71
    example_object_type: string
    example_predicate: sockg:expUnitId
    example_subject: sockg:individuals/203988
    example_subject_type: sockg_PlantingEvent
- object:
    example_object: WIPDBARN_2
    example_object_type: string
    example_predicate: sockg:expUnitId
    example_subject: sockg:individuals/364326
    example_subject_type: sockg_WaterQualityArea
- object:
    example_object: IAAMKELL__120
    example_object_type: string
    example_predicate: sockg:expUnitId
    example_subject: sockg:individuals/364993
    example_subject_type: sockg_WaterQualityConc
- object:
    example_object: IAAMKELL__116
    example_object_type: string
    example_predicate: sockg:expUnitId
    example_subject: sockg:individuals/55858
    example_subject_type: sockg_GasNutrientLoss
- object:
    example_object: TXBSWEWC_COMP2
    example_object_type: string
    example_predicate: sockg:expUnitId
    example_subject: sockg:individuals/624572
    example_subject_type: sockg_WindErosionArea
- object:
    example_object: MNSP4R_U-S100B
    example_object_type: string
    example_predicate: sockg:expUnitId
    example_subject: sockg:individuals/624587
    example_subject_type: sockg_YieldNutrientUptake
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/849
rank: 1000
slot_uri: sockg:expUnitId
alias: sockg_expUnitId
domain_of:
- sockg_ExperimentalUnit
- sockg_GasNutrientLoss
- sockg_NutrientEfficiency
- sockg_PlantingEvent
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
- sockg_YieldNutrientUptake
union_of:
- '{''domain'': ''sockg_WaterQualityArea''}'
- '{''domain'': ''sockg_WindErosionArea''}'
- '{''domain'': ''sockg_NutrientEfficiency''}'
- '{''domain'': ''sockg_WaterQualityConc''}'
- '{''domain'': ''sockg_CropGrowthStage''}'
- '{''domain'': ''sockg_ExperimentalUnit''}'
- '{''domain'': ''sockg_Harvest''}'
- '{''domain'': ''sockg_GasNutrientLoss''}'
- '{''domain'': ''sockg_Amendment''}'
- '{''domain'': ''sockg_YieldNutrientUptake''}'
- '{''domain'': ''sockg_HarvestFraction''}'
- '{''domain'': ''sockg_ResidueManagementEvent''}'
- '{''domain'': ''sockg_GasSample''}'
range: string

```
</details>