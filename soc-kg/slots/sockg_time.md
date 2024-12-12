

# Slot: sockg_time


_No slot description provided_





URI: [sockg:time](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/time)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasSample](../classes/SockgGasSample.md) | No type description provided |  no  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | No type description provided |  no  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | No type description provided |  no  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | No type description provided |  no  |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#97100 sockg:time nan |
| neo4j://graph.individuals#160382 sockg:time 11:09:00 |
| neo4j://graph.individuals#361705 sockg:time nan |
| neo4j://graph.individuals#55832 sockg:time nan |
| neo4j://graph.individuals#360324 sockg:time nan |
| neo4j://graph.individuals#509313 sockg:time nan |

## Comments

* 101883 occurrences with subject type sockg:GasSample and object type xsd:double.
* 5471 occurrences with subject type sockg:GasSample and object type string.
* 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
* 748 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
* 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
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
| self | sockg:time |
| native | soc-kg/main/:sockg_time |




## LinkML Source

<details>
```yaml
name: sockg_time
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 101883 occurrences with subject type sockg:GasSample and object type xsd:double.
- 5471 occurrences with subject type sockg:GasSample and object type string.
- 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
- 748 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
- 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
- 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
examples:
- value: neo4j://graph.individuals#97100 sockg:time nan
- value: neo4j://graph.individuals#160382 sockg:time 11:09:00
- value: neo4j://graph.individuals#361705 sockg:time nan
- value: neo4j://graph.individuals#55832 sockg:time nan
- value: neo4j://graph.individuals#360324 sockg:time nan
- value: neo4j://graph.individuals#509313 sockg:time nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:time
alias: sockg_time
domain_of:
- sockg_GasNutrientLoss
- sockg_GasSample
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
range: Any
any_of:
- range: double
- range: string

```
</details>