

# Slot: sockg_expUnit_UID


_No slot description provided_





URI: [sockg:expUnit_UID](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/expUnit_UID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | No type description provided |  no  |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | No type description provided |  no  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | No type description provided |  no  |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | No type description provided |  no  |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | No type description provided |  no  |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#52433 sockg:expUnit_UID AgCros_TXLULIB1_26 |
| neo4j://graph.individuals#201925 sockg:expUnit_UID AgCros_NELITCSE_201 |
| neo4j://graph.individuals#55653 sockg:expUnit_UID AgCros_WIPDBARN_1 |
| neo4j://graph.individuals#360941 sockg:expUnit_UID AgCros_IAAMKELL_120 |
| neo4j://graph.individuals#509548 sockg:expUnit_UID AgCros_MNMOCAM_678 |
| neo4j://graph.individuals#509309 sockg:expUnit_UID AgCros_TXBSWEWC_COMP3 |

## Comments

* 3809 occurrences with subject type sockg:ExperimentalUnit and object type string.
* 2791 occurrences with subject type sockg:NutrientEfficiency and object type string.
* 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
* 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
* 429 occurrences with subject type sockg:YieldNutrientUptake and object type string.
* 15 occurrences with subject type sockg:WindErosionArea and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: soc-kg/main




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sockg:expUnit_UID |
| native | soc-kg/main/:sockg_expUnit_UID |




## LinkML Source

<details>
```yaml
name: sockg_expUnit_UID
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 3809 occurrences with subject type sockg:ExperimentalUnit and object type string.
- 2791 occurrences with subject type sockg:NutrientEfficiency and object type string.
- 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
- 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
- 429 occurrences with subject type sockg:YieldNutrientUptake and object type string.
- 15 occurrences with subject type sockg:WindErosionArea and object type string.
examples:
- value: neo4j://graph.individuals#52433 sockg:expUnit_UID AgCros_TXLULIB1_26
- value: neo4j://graph.individuals#201925 sockg:expUnit_UID AgCros_NELITCSE_201
- value: neo4j://graph.individuals#55653 sockg:expUnit_UID AgCros_WIPDBARN_1
- value: neo4j://graph.individuals#360941 sockg:expUnit_UID AgCros_IAAMKELL_120
- value: neo4j://graph.individuals#509548 sockg:expUnit_UID AgCros_MNMOCAM_678
- value: neo4j://graph.individuals#509309 sockg:expUnit_UID AgCros_TXBSWEWC_COMP3
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:expUnit_UID
alias: sockg_expUnit_UID
domain_of:
- sockg_ExperimentalUnit
- sockg_GasNutrientLoss
- sockg_NutrientEfficiency
- sockg_WaterQualityConc
- sockg_WindErosionArea
- sockg_YieldNutrientUptake
range: string

```
</details>