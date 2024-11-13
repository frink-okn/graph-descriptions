

# Slot: sockg_crop


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:crop](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/crop)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgNutrientEfficiency](../classes/SockgNutrientEfficiency.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgBioMassMineral](../classes/SockgBioMassMineral.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgBioMassCarbohydrate](../classes/SockgBioMassCarbohydrate.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgGasSample](../classes/SockgGasSample.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgBioMassEnergy](../classes/SockgBioMassEnergy.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#201065 sockg:crop Zea mays (Corn) |
| neo4j://graph.individuals#156219 sockg:crop Zea mays (Corn) |
| neo4j://graph.individuals#45025 sockg:crop Zea mays (Corn) |
| neo4j://graph.individuals#509340 sockg:crop Secale cereale (Rye) |
| neo4j://graph.individuals#360357 sockg:crop nan |
| neo4j://graph.individuals#37850 sockg:crop Zea mays (Corn) |
| neo4j://graph.individuals#39943 sockg:crop Zea mays (Corn) |
| neo4j://graph.individuals#112348 sockg:crop nan |
| neo4j://graph.individuals#360717 sockg:crop Glycine max (Soybean) |
| neo4j://graph.individuals#56206 sockg:crop nan |
| neo4j://graph.individuals#361559 sockg:crop nan |
| neo4j://graph.individuals#56324 sockg:crop Secale cereale (Rye) |
| neo4j://graph.individuals#509306 sockg:crop nan |

## Comments

* 2791 occurrences with subject type sockg:NutrientEfficiency and object type string.
* 105046 occurrences with subject type sockg:GasSample and object type string.
* 6723 occurrences with subject type sockg:BioMassMineral and object type string.
* 429 occurrences with subject type sockg:YieldNutrientUptake and object type string.
* 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
* 1367 occurrences with subject type sockg:BioMassCarbohydrate and object type string.
* 799 occurrences with subject type sockg:BioMassEnergy and object type string.
* 2308 occurrences with subject type sockg:GasSample and object type xsd:double.
* 553 occurrences with subject type sockg:WaterQualityConc and object type string.
* 698 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
* 926 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
* 50 occurrences with subject type sockg:GasNutrientLoss and object type string.
* 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.

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
| self | sockg:crop |
| native | soc-kg/main/:sockg_crop |




## LinkML Source

<details>
```yaml
name: sockg_crop
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 2791 occurrences with subject type sockg:NutrientEfficiency and object type string.
- 105046 occurrences with subject type sockg:GasSample and object type string.
- 6723 occurrences with subject type sockg:BioMassMineral and object type string.
- 429 occurrences with subject type sockg:YieldNutrientUptake and object type string.
- 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
- 1367 occurrences with subject type sockg:BioMassCarbohydrate and object type string.
- 799 occurrences with subject type sockg:BioMassEnergy and object type string.
- 2308 occurrences with subject type sockg:GasSample and object type xsd:double.
- 553 occurrences with subject type sockg:WaterQualityConc and object type string.
- 698 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
- 926 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
- 50 occurrences with subject type sockg:GasNutrientLoss and object type string.
- 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
examples:
- value: neo4j://graph.individuals#201065 sockg:crop Zea mays (Corn)
- value: neo4j://graph.individuals#156219 sockg:crop Zea mays (Corn)
- value: neo4j://graph.individuals#45025 sockg:crop Zea mays (Corn)
- value: neo4j://graph.individuals#509340 sockg:crop Secale cereale (Rye)
- value: neo4j://graph.individuals#360357 sockg:crop nan
- value: neo4j://graph.individuals#37850 sockg:crop Zea mays (Corn)
- value: neo4j://graph.individuals#39943 sockg:crop Zea mays (Corn)
- value: neo4j://graph.individuals#112348 sockg:crop nan
- value: neo4j://graph.individuals#360717 sockg:crop Glycine max (Soybean)
- value: neo4j://graph.individuals#56206 sockg:crop nan
- value: neo4j://graph.individuals#361559 sockg:crop nan
- value: neo4j://graph.individuals#56324 sockg:crop Secale cereale (Rye)
- value: neo4j://graph.individuals#509306 sockg:crop nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:crop
alias: sockg_crop
domain_of:
- sockg_BioMassCarbohydrate
- sockg_BioMassEnergy
- sockg_BioMassMineral
- sockg_GasNutrientLoss
- sockg_GasSample
- sockg_NutrientEfficiency
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
- sockg_YieldNutrientUptake
range: Any
any_of:
- range: string
- range: double

```
</details>