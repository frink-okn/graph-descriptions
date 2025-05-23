

# Slot: No slot (predicate) name specified (sockg_crop)


_No slot (predicate) description specified_






This slot occurs 213189 times.


URI: [sockg:crop](https://idir.uta.edu/sockg-ontology/docs/crop)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | WaterQualityConc represents the concentration of various water quality parame... |  yes  |
| [SockgPlantingEvent](../classes/SockgPlantingEvent.md) | An event involving the act of planting, which includes considerations for spa... |  yes  |
| [SockgCropGrowthStage](../classes/SockgCropGrowthStage.md) | The CropGrowthStage class represents the various phases of development that a... |  yes  |
| [SockgBioMassMineral](../classes/SockgBioMassMineral.md) | BioMassMiner is a class that represents the analysis of biomass in terms of i... |  yes  |
| [SockgResidueManagementEvent](../classes/SockgResidueManagementEvent.md) | A ResidueManagementEvent represents a specific instance of managing agricultu... |  yes  |
| [SockgBioMassCarbohydrate](../classes/SockgBioMassCarbohydrate.md) | BioMassCarbohydrate represents the carbohydrate content in biomass derived fr... |  yes  |
| [SockgGasSample](../classes/SockgGasSample.md) | GasSample represents a collection of measurements related to greenhouse gas e... |  yes  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | The GasNutrientLoss class represents the assessment of gaseous nutrient losse... |  yes  |
| [SockgHarvest](../classes/SockgHarvest.md) | Harvest represents the process of collecting mature crops from the fields, wi... |  yes  |
| [SockgBioMassEnergy](../classes/SockgBioMassEnergy.md) | BioMassEnergy represents the energy content derived from agricultural biomass... |  yes  |
| [SockgHarvestFraction](../classes/SockgHarvestFraction.md) | The HarvestFraction class represents the quantifiable metrics and characteris... |  yes  |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | The YieldNutrientUptake class represents the assessment of nutrient uptake by... |  yes  |
| [SockgAmendment](../classes/SockgAmendment.md) | An Amendment represents a specific alteration or addition made to agricultura... |  yes  |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | The NutrientEfficiency class represents the effectiveness of nutrient utiliza... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Amendment | string | sockg:individuals/0 | Glycine max (Soybean) | 35951 |
| sockg_GasSample | string | sockg:individuals/100000 | Rangeland | 105046 |
| sockg_Harvest | string | sockg:individuals/172906 | Glycine max (Soybean) | 18356 |
| sockg_HarvestFraction | string | sockg:individuals/191262 | Zea mays (Corn) | 9470 |
| sockg_ResidueManagementEvent | string | sockg:individuals/227674 | Zea mays (Corn) | 3308 |
| sockg_BioMassCarbohydrate | string | sockg:individuals/37796 | Zea mays (Corn) | 1367 |
| sockg_BioMassEnergy | string | sockg:individuals/39163 | Zea mays (Corn) | 799 |
| sockg_BioMassMineral | string | sockg:individuals/39962 | Zea mays (Corn) | 6723 |
| sockg_CropGrowthStage | string | sockg:individuals/46937 | Zea mays (Corn) | 4896 |
| sockg_NutrientEfficiency | string | sockg:individuals/200732 | Calendula officinalis L. (Calendula) | 2791 |
| sockg_PlantingEvent | string | sockg:individuals/203988 | Secale cereale (Rye) | 23450 |
| sockg_WaterQualityConc | string | sockg:individuals/364993 | Glycine max (Soybean) | 553 |
| sockg_GasNutrientLoss | string | sockg:individuals/55859 | Zea mays (Corn) | 50 |
| sockg_YieldNutrientUptake | string | sockg:individuals/624587 | Zea mays (Corn) | 429 |


## See Also

* [https://lod.nal.usda.gov/nalt/7140](https://lod.nal.usda.gov/nalt/7140)



## LinkML Source

<details>

```yaml
name: sockg_crop
annotations:
  count:
    tag: count
    value: 213189
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Glycine max (Soybean)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/0
    example_subject_type: sockg_Amendment
- object:
    example_object: Rangeland
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/100000
    example_subject_type: sockg_GasSample
- object:
    example_object: Glycine max (Soybean)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/172906
    example_subject_type: sockg_Harvest
- object:
    example_object: Zea mays (Corn)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/191262
    example_subject_type: sockg_HarvestFraction
- object:
    example_object: Zea mays (Corn)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/227674
    example_subject_type: sockg_ResidueManagementEvent
- object:
    example_object: Zea mays (Corn)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/37796
    example_subject_type: sockg_BioMassCarbohydrate
- object:
    example_object: Zea mays (Corn)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/39163
    example_subject_type: sockg_BioMassEnergy
- object:
    example_object: Zea mays (Corn)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/39962
    example_subject_type: sockg_BioMassMineral
- object:
    example_object: Zea mays (Corn)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/46937
    example_subject_type: sockg_CropGrowthStage
- object:
    example_object: Calendula officinalis L. (Calendula)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/200732
    example_subject_type: sockg_NutrientEfficiency
- object:
    example_object: Secale cereale (Rye)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/203988
    example_subject_type: sockg_PlantingEvent
- object:
    example_object: Glycine max (Soybean)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/364993
    example_subject_type: sockg_WaterQualityConc
- object:
    example_object: Zea mays (Corn)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/55859
    example_subject_type: sockg_GasNutrientLoss
- object:
    example_object: Zea mays (Corn)
    example_object_type: string
    example_predicate: sockg:crop
    example_subject: sockg:individuals/624587
    example_subject_type: sockg_YieldNutrientUptake
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/7140
rank: 1000
slot_uri: sockg:crop
alias: sockg_crop
domain_of:
- sockg_Amendment
- sockg_BioMassCarbohydrate
- sockg_BioMassEnergy
- sockg_BioMassMineral
- sockg_CropGrowthStage
- sockg_GasNutrientLoss
- sockg_GasSample
- sockg_Harvest
- sockg_HarvestFraction
- sockg_NutrientEfficiency
- sockg_PlantingEvent
- sockg_ResidueManagementEvent
- sockg_WaterQualityConc
- sockg_YieldNutrientUptake
union_of:
- '{''domain'': ''sockg_WaterQualityArea''}'
- '{''domain'': ''sockg_WindErosionArea''}'
- '{''domain'': ''sockg_NutrientEfficiency''}'
- '{''domain'': ''sockg_WaterQualityConc''}'
- '{''domain'': ''sockg_GasNutrientLoss''}'
- '{''domain'': ''sockg_YieldNutrientUptake''}'
- '{''domain'': ''sockg_BioMassMineral''}'
- '{''domain'': ''sockg_BioMassCarbohydrate''}'
- '{''domain'': ''sockg_BioMassEnergy''}'
- '{''domain'': ''sockg_Tillage''}'
range: string

```
</details>