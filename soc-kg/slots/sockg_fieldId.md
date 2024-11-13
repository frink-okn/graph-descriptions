

# Slot: sockg_fieldId


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:fieldId](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/fieldId)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgField](../classes/SockgField.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#201298 sockg:fieldId NELITCSE |
| neo4j://graph.individuals#55677 sockg:fieldId WIPDBARN |
| neo4j://graph.individuals#360040 sockg:fieldId WIPDBARN |
| neo4j://graph.individuals#509384 sockg:fieldId ALAURye |
| neo4j://graph.individuals#361395 sockg:fieldId WIPDBARN |
| neo4j://graph.individuals#509301 sockg:fieldId TXBSWEWC |
| neo4j://graph.individuals#55606 sockg:fieldId NELITCSE |

## Comments

* 2791 occurrences with subject type sockg:NutrientEfficiency and object type string.
* 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
* 667 occurrences with subject type sockg:WaterQualityArea and object type string.
* 429 occurrences with subject type sockg:YieldNutrientUptake and object type string.
* 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
* 15 occurrences with subject type sockg:WindErosionArea and object type string.
* 58 occurrences with subject type sockg:Field and object type string.

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
| self | sockg:fieldId |
| native | soc-kg/main/:sockg_fieldId |




## LinkML Source

<details>
```yaml
name: sockg_fieldId
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 2791 occurrences with subject type sockg:NutrientEfficiency and object type string.
- 748 occurrences with subject type sockg:GasNutrientLoss and object type string.
- 667 occurrences with subject type sockg:WaterQualityArea and object type string.
- 429 occurrences with subject type sockg:YieldNutrientUptake and object type string.
- 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
- 15 occurrences with subject type sockg:WindErosionArea and object type string.
- 58 occurrences with subject type sockg:Field and object type string.
examples:
- value: neo4j://graph.individuals#201298 sockg:fieldId NELITCSE
- value: neo4j://graph.individuals#55677 sockg:fieldId WIPDBARN
- value: neo4j://graph.individuals#360040 sockg:fieldId WIPDBARN
- value: neo4j://graph.individuals#509384 sockg:fieldId ALAURye
- value: neo4j://graph.individuals#361395 sockg:fieldId WIPDBARN
- value: neo4j://graph.individuals#509301 sockg:fieldId TXBSWEWC
- value: neo4j://graph.individuals#55606 sockg:fieldId NELITCSE
from_schema: soc-kg/main
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
range: string

```
</details>