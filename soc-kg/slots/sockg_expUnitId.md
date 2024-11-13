

# Slot: sockg_expUnitId


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:expUnitId](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/expUnitId)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#52840 sockg:expUnitId GAJPCSR1_B2P102F1H1X600Y90 |
| neo4j://graph.individuals#201638 sockg:expUnitId NELITCSE_509 |
| neo4j://graph.individuals#55654 sockg:expUnitId WIPDBARN_3 |
| neo4j://graph.individuals#360565 sockg:expUnitId IAAMKELL__120 |
| neo4j://graph.individuals#359954 sockg:expUnitId WIPDBARN_1 |
| neo4j://graph.individuals#509440 sockg:expUnitId ALAURye_410 |
| neo4j://graph.individuals#509305 sockg:expUnitId TXBSWEWC_COMP5 |

## Comments

* 3809 occurrences with subject type sockg:ExperimentalUnit and object type string.
* 2791 occurrences with subject type sockg:NutrientEfficiency and object type string.
* 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
* 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
* 667 occurrences with subject type sockg:WaterQualityArea and object type string.
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
| self | sockg:expUnitId |
| native | soc-kg/main/:sockg_expUnitId |




## LinkML Source

<details>
```yaml
name: sockg_expUnitId
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 3809 occurrences with subject type sockg:ExperimentalUnit and object type string.
- 2791 occurrences with subject type sockg:NutrientEfficiency and object type string.
- 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
- 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
- 667 occurrences with subject type sockg:WaterQualityArea and object type string.
- 429 occurrences with subject type sockg:YieldNutrientUptake and object type string.
- 15 occurrences with subject type sockg:WindErosionArea and object type string.
examples:
- value: neo4j://graph.individuals#52840 sockg:expUnitId GAJPCSR1_B2P102F1H1X600Y90
- value: neo4j://graph.individuals#201638 sockg:expUnitId NELITCSE_509
- value: neo4j://graph.individuals#55654 sockg:expUnitId WIPDBARN_3
- value: neo4j://graph.individuals#360565 sockg:expUnitId IAAMKELL__120
- value: neo4j://graph.individuals#359954 sockg:expUnitId WIPDBARN_1
- value: neo4j://graph.individuals#509440 sockg:expUnitId ALAURye_410
- value: neo4j://graph.individuals#509305 sockg:expUnitId TXBSWEWC_COMP5
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:expUnitId
alias: sockg_expUnitId
domain_of:
- sockg_ExperimentalUnit
- sockg_GasNutrientLoss
- sockg_NutrientEfficiency
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
- sockg_YieldNutrientUptake
range: string

```
</details>