

# Slot: sockg_plantFraction


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:plantFraction](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/plantFraction)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgBioMassMineral](../classes/SockgBioMassMineral.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgBioMassCarbohydrate](../classes/SockgBioMassCarbohydrate.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgHarvestFraction](../classes/SockgHarvestFraction.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgBioMassEnergy](../classes/SockgBioMassEnergy.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#192293 sockg:plantFraction Grain |
| neo4j://graph.individuals#44722 sockg:plantFraction Grain |
| neo4j://graph.individuals#201773 sockg:plantFraction Grain |
| neo4j://graph.individuals#509641 sockg:plantFraction Roots |
| neo4j://graph.individuals#37806 sockg:plantFraction Above earshank |
| neo4j://graph.individuals#39360 sockg:plantFraction Cobs |
| neo4j://graph.individuals#200713 sockg:plantFraction nan |

## Comments

* 9470 occurrences with subject type sockg:HarvestFraction and object type string.
* 6723 occurrences with subject type sockg:BioMassMineral and object type string.
* 2683 occurrences with subject type sockg:NutrientEfficiency and object type string.
* 429 occurrences with subject type sockg:YieldNutrientUptake and object type string.
* 1367 occurrences with subject type sockg:BioMassCarbohydrate and object type string.
* 799 occurrences with subject type sockg:BioMassEnergy and object type string.
* 108 occurrences with subject type sockg:NutrientEfficiency and object type xsd:double.

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
| self | sockg:plantFraction |
| native | soc-kg/main/:sockg_plantFraction |




## LinkML Source

<details>
```yaml
name: sockg_plantFraction
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 9470 occurrences with subject type sockg:HarvestFraction and object type string.
- 6723 occurrences with subject type sockg:BioMassMineral and object type string.
- 2683 occurrences with subject type sockg:NutrientEfficiency and object type string.
- 429 occurrences with subject type sockg:YieldNutrientUptake and object type string.
- 1367 occurrences with subject type sockg:BioMassCarbohydrate and object type string.
- 799 occurrences with subject type sockg:BioMassEnergy and object type string.
- 108 occurrences with subject type sockg:NutrientEfficiency and object type xsd:double.
examples:
- value: neo4j://graph.individuals#192293 sockg:plantFraction Grain
- value: neo4j://graph.individuals#44722 sockg:plantFraction Grain
- value: neo4j://graph.individuals#201773 sockg:plantFraction Grain
- value: neo4j://graph.individuals#509641 sockg:plantFraction Roots
- value: neo4j://graph.individuals#37806 sockg:plantFraction Above earshank
- value: neo4j://graph.individuals#39360 sockg:plantFraction Cobs
- value: neo4j://graph.individuals#200713 sockg:plantFraction nan
from_schema: soc-kg/main
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
range: Any
any_of:
- range: string
- range: double

```
</details>