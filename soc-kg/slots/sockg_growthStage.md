

# Slot: No slot (predicate) name specified (sockg_growthStage)


_No slot (predicate) description specified_






This slot occurs 51226 times.


URI: [sockg:growthStage](https://idir.uta.edu/sockg-ontology/docs/growthStage)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parame... |  yes  |
| [SockgCropGrowthStage](../classes/SockgCropGrowthStage.md) | The CropGrowthStage class represents the various phases of development that a... |  yes  |
| [SockgBioMassMineral](../classes/SockgBioMassMineral.md) | BioMassMiner is a class that represents the analysis of biomass in terms of i... |  yes  |
| [SockgBioMassCarbohydrate](../classes/SockgBioMassCarbohydrate.md) | BioMassCarbohydrate represents the carbohydrate content in biomass derived fr... |  yes  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | The GasNutrientLoss class represents the assessment of gaseous nutrient losse... |  yes  |
| [SockgHarvest](../classes/SockgHarvest.md) | Harvest represents the process of collecting mature crops from the fields, wi... |  yes  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | The WindErosionArea class represents regions affected by wind erosion, detail... |  yes  |
| [SockgBioMassEnergy](../classes/SockgBioMassEnergy.md) | BioMassEnergy represents the energy content derived from agricultural biomass... |  yes  |
| [SockgHarvestFraction](../classes/SockgHarvestFraction.md) | The HarvestFraction class represents the quantifiable metrics and characteris... |  yes  |
| [SockgGrazing](../classes/SockgGrazing.md) | The Grazing class represents the assessment of various productivity metrics a... |  yes  |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | The YieldNutrientUptake class represents the assessment of nutrient uptake by... |  yes  |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | The NutrientEfficiency class represents the effectiveness of nutrient utiliza... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Grazing | string | sockg:individuals/163960 | Maturity | 6683 |
| sockg_Harvest | string | sockg:individuals/172911 | Harvest | 17240 |
| sockg_HarvestFraction | string | sockg:individuals/191262 | V7 | 9407 |
| sockg_BioMassCarbohydrate | string | sockg:individuals/37796 | Maturity | 1367 |
| sockg_BioMassEnergy | string | sockg:individuals/39163 | Harvest | 799 |
| sockg_BioMassMineral | string | sockg:individuals/39962 | Maturity | 6723 |
| sockg_CropGrowthStage | string | sockg:individuals/46937 | R6 | 4896 |
| sockg_NutrientEfficiency | string | sockg:individuals/200732 | Maturity | 2791 |
| sockg_WaterQualityConc | string | sockg:individuals/364993 | Pre-graze | 812 |
| sockg_GasNutrientLoss | string | sockg:individuals/55858 | Pre-graze | 64 |
| sockg_WindErosionArea | string | sockg:individuals/624572 | Pre-graze | 15 |
| sockg_YieldNutrientUptake | string | sockg:individuals/624587 | Harvest | 429 |


## See Also

* [https://lod.nal.usda.gov/nalt/7140](https://lod.nal.usda.gov/nalt/7140)



## LinkML Source

<details>

```yaml
name: sockg_growthStage
annotations:
  count:
    tag: count
    value: 51226
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Maturity
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/163960
    example_subject_type: sockg_Grazing
- object:
    example_object: Harvest
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/172911
    example_subject_type: sockg_Harvest
- object:
    example_object: V7
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/191262
    example_subject_type: sockg_HarvestFraction
- object:
    example_object: Maturity
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/37796
    example_subject_type: sockg_BioMassCarbohydrate
- object:
    example_object: Harvest
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/39163
    example_subject_type: sockg_BioMassEnergy
- object:
    example_object: Maturity
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/39962
    example_subject_type: sockg_BioMassMineral
- object:
    example_object: R6
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/46937
    example_subject_type: sockg_CropGrowthStage
- object:
    example_object: Maturity
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/200732
    example_subject_type: sockg_NutrientEfficiency
- object:
    example_object: Pre-graze
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/364993
    example_subject_type: sockg_WaterQualityConc
- object:
    example_object: Pre-graze
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/55858
    example_subject_type: sockg_GasNutrientLoss
- object:
    example_object: Pre-graze
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/624572
    example_subject_type: sockg_WindErosionArea
- object:
    example_object: Harvest
    example_object_type: string
    example_predicate: sockg:growthStage
    example_subject: sockg:individuals/624587
    example_subject_type: sockg_YieldNutrientUptake
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/7140
rank: 1000
slot_uri: sockg:growthStage
alias: sockg_growthStage
domain_of:
- sockg_BioMassCarbohydrate
- sockg_BioMassEnergy
- sockg_BioMassMineral
- sockg_CropGrowthStage
- sockg_GasNutrientLoss
- sockg_Grazing
- sockg_Harvest
- sockg_HarvestFraction
- sockg_NutrientEfficiency
- sockg_WaterQualityConc
- sockg_WindErosionArea
- sockg_YieldNutrientUptake
union_of:
- '{''domain'': ''sockg_WaterQualityArea''}'
- '{''domain'': ''sockg_WindErosionArea''}'
- '{''domain'': ''sockg_NutrientEfficiency''}'
- '{''domain'': ''sockg_WaterQualityConc''}'
- '{''domain'': ''sockg_CropGrowthStage''}'
- '{''domain'': ''sockg_Grazing''}'
- '{''domain'': ''sockg_GasNutrientLoss''}'
- '{''domain'': ''sockg_Harvest''}'
- '{''domain'': ''sockg_BioMassMineral''}'
- '{''domain'': ''sockg_YieldNutrientUptake''}'
- '{''domain'': ''sockg_BioMassCarbohydrate''}'
- '{''domain'': ''sockg_BioMassEnergy''}'
- '{''domain'': ''sockg_HarvestFraction''}'
range: string

```
</details>