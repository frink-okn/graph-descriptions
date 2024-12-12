

# Slot: sockg_samplingStartStopInterval


_No slot description provided_





URI: [sockg:samplingStartStopInterval](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/samplingStartStopInterval)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | No type description provided |  no  |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | No type description provided |  no  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | No type description provided |  no  |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#361366 sockg:samplingStartStopInterval nan |
| neo4j://graph.individuals#56298 sockg:samplingStartStopInterval nan |
| neo4j://graph.individuals#360222 sockg:samplingStartStopInterval nan |
| neo4j://graph.individuals#360975 sockg:samplingStartStopInterval Stop-Start |
| neo4j://graph.individuals#509301 sockg:samplingStartStopInterval Stop |
| neo4j://graph.individuals#56333 sockg:samplingStartStopInterval Stop-Start |

## Comments

* 667 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
* 684 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
* 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
* 812 occurrences with subject type sockg:WaterQualityConc and object type string.
* 15 occurrences with subject type sockg:WindErosionArea and object type string.
* 64 occurrences with subject type sockg:GasNutrientLoss and object type string.

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
| self | sockg:samplingStartStopInterval |
| native | soc-kg/main/:sockg_samplingStartStopInterval |




## LinkML Source

<details>
```yaml
name: sockg_samplingStartStopInterval
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 667 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
- 684 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
- 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
- 812 occurrences with subject type sockg:WaterQualityConc and object type string.
- 15 occurrences with subject type sockg:WindErosionArea and object type string.
- 64 occurrences with subject type sockg:GasNutrientLoss and object type string.
examples:
- value: neo4j://graph.individuals#361366 sockg:samplingStartStopInterval nan
- value: neo4j://graph.individuals#56298 sockg:samplingStartStopInterval nan
- value: neo4j://graph.individuals#360222 sockg:samplingStartStopInterval nan
- value: neo4j://graph.individuals#360975 sockg:samplingStartStopInterval Stop-Start
- value: neo4j://graph.individuals#509301 sockg:samplingStartStopInterval Stop
- value: neo4j://graph.individuals#56333 sockg:samplingStartStopInterval Stop-Start
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:samplingStartStopInterval
alias: sockg_samplingStartStopInterval
domain_of:
- sockg_GasNutrientLoss
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
range: Any
any_of:
- range: double
- range: string

```
</details>