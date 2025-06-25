

# Slot: No slot (predicate) name specified (sockg_plantFraction)


_No slot (predicate) description specified_






This slot occurs 21471 times.


URI: [sockg:plantFraction](https://idir.uta.edu/sockg-ontology/docs/plantFraction)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgBioMassMineral](../classes/SockgBioMassMineral.md) | BioMassMiner is a class that represents the analysis of biomass in terms of i... |  yes  |
| [SockgBioMassCarbohydrate](../classes/SockgBioMassCarbohydrate.md) | BioMassCarbohydrate represents the carbohydrate content in biomass derived fr... |  yes  |
| [SockgBioMassEnergy](../classes/SockgBioMassEnergy.md) | BioMassEnergy represents the energy content derived from agricultural biomass... |  yes  |
| [SockgHarvestFraction](../classes/SockgHarvestFraction.md) | The HarvestFraction class represents the quantifiable metrics and characteris... |  yes  |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | The YieldNutrientUptake class represents the assessment of nutrient uptake by... |  yes  |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | The NutrientEfficiency class represents the effectiveness of nutrient utiliza... |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_HarvestFraction | string | sockg:individuals/191262 | Roots | 9470 |
| sockg_BioMassCarbohydrate | string | sockg:individuals/37796 | Above earshank | 1367 |
| sockg_BioMassEnergy | string | sockg:individuals/39163 | Below earshank leaves | 799 |
| sockg_BioMassMineral | string | sockg:individuals/39962 | Stover (all non-grain biomass) | 6723 |
| sockg_NutrientEfficiency | string | sockg:individuals/200732 | Seed Oil | 2683 |
| sockg_YieldNutrientUptake | string | sockg:individuals/624587 | Grain | 429 |


## See Also

* [https://lod.nal.usda.gov/nalt/849](https://lod.nal.usda.gov/nalt/849)



## LinkML Source

<details>

```yaml
name: sockg_plantFraction
annotations:
  count:
    tag: count
    value: 21471
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Roots
    example_object_type: string
    example_predicate: sockg:plantFraction
    example_subject: sockg:individuals/191262
    example_subject_type: sockg_HarvestFraction
- object:
    example_object: Above earshank
    example_object_type: string
    example_predicate: sockg:plantFraction
    example_subject: sockg:individuals/37796
    example_subject_type: sockg_BioMassCarbohydrate
- object:
    example_object: Below earshank leaves
    example_object_type: string
    example_predicate: sockg:plantFraction
    example_subject: sockg:individuals/39163
    example_subject_type: sockg_BioMassEnergy
- object:
    example_object: Stover (all non-grain biomass)
    example_object_type: string
    example_predicate: sockg:plantFraction
    example_subject: sockg:individuals/39962
    example_subject_type: sockg_BioMassMineral
- object:
    example_object: Seed Oil
    example_object_type: string
    example_predicate: sockg:plantFraction
    example_subject: sockg:individuals/200732
    example_subject_type: sockg_NutrientEfficiency
- object:
    example_object: Grain
    example_object_type: string
    example_predicate: sockg:plantFraction
    example_subject: sockg:individuals/624587
    example_subject_type: sockg_YieldNutrientUptake
from_schema: soc-kg
see_also:
- https://lod.nal.usda.gov/nalt/849
rank: 1000
slot_uri: sockg:plantFraction
alias: sockg_plantFraction
domain_of:
- sockg_BioMassCarbohydrate
- sockg_BioMassEnergy
- sockg_BioMassMineral
- sockg_HarvestFraction
- sockg_NutrientEfficiency
- sockg_YieldNutrientUptake
union_of:
- '{''domain'': ''sockg_NutrientEfficiency''}'
- '{''domain'': ''sockg_YieldNutrientUptake''}'
- '{''domain'': ''sockg_BioMassMineral''}'
- '{''domain'': ''sockg_BioMassCarbohydrate''}'
- '{''domain'': ''sockg_BioMassEnergy''}'
- '{''domain'': ''sockg_HarvestFraction''}'
range: string

```
</details>