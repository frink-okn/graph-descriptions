

# Slot: sockg_modelIfSimulated


_No slot description provided_





URI: [sockg:modelIfSimulated](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/modelIfSimulated)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgGasNutrientLoss](../classes/SockgGasNutrientLoss.md) | No type description provided |  no  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | No type description provided |  no  |
| [SockgYieldNutrientUptake](../classes/SockgYieldNutrientUptake.md) | No type description provided |  no  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | No type description provided |  no  |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#509423 sockg:modelIfSimulated nan |
| neo4j://graph.individuals#360133 sockg:modelIfSimulated nan |
| neo4j://graph.individuals#56071 sockg:modelIfSimulated nan |
| neo4j://graph.individuals#361440 sockg:modelIfSimulated nan |
| neo4j://graph.individuals#55638 sockg:modelIfSimulated RZWQM |
| neo4j://graph.individuals#361269 sockg:modelIfSimulated RZWQM |
| neo4j://graph.individuals#509307 sockg:modelIfSimulated Linear Proportional with particle size correction factor |
| neo4j://graph.individuals#509303 sockg:modelIfSimulated nan |

## Comments

* 429 occurrences with subject type sockg:YieldNutrientUptake and object type xsd:double.
* 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
* 692 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
* 1466 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
* 56 occurrences with subject type sockg:GasNutrientLoss and object type string.
* 13 occurrences with subject type sockg:WaterQualityConc and object type string.
* 4 occurrences with subject type sockg:WindErosionArea and object type string.
* 11 occurrences with subject type sockg:WindErosionArea and object type xsd:double.

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
| self | sockg:modelIfSimulated |
| native | soc-kg/main/:sockg_modelIfSimulated |




## LinkML Source

<details>
```yaml
name: sockg_modelIfSimulated
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 429 occurrences with subject type sockg:YieldNutrientUptake and object type xsd:double.
- 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
- 692 occurrences with subject type sockg:GasNutrientLoss and object type xsd:double.
- 1466 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
- 56 occurrences with subject type sockg:GasNutrientLoss and object type string.
- 13 occurrences with subject type sockg:WaterQualityConc and object type string.
- 4 occurrences with subject type sockg:WindErosionArea and object type string.
- 11 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
examples:
- value: neo4j://graph.individuals#509423 sockg:modelIfSimulated nan
- value: neo4j://graph.individuals#360133 sockg:modelIfSimulated nan
- value: neo4j://graph.individuals#56071 sockg:modelIfSimulated nan
- value: neo4j://graph.individuals#361440 sockg:modelIfSimulated nan
- value: neo4j://graph.individuals#55638 sockg:modelIfSimulated RZWQM
- value: neo4j://graph.individuals#361269 sockg:modelIfSimulated RZWQM
- value: neo4j://graph.individuals#509307 sockg:modelIfSimulated Linear Proportional
    with particle size correction factor
- value: neo4j://graph.individuals#509303 sockg:modelIfSimulated nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:modelIfSimulated
alias: sockg_modelIfSimulated
domain_of:
- sockg_GasNutrientLoss
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
- sockg_YieldNutrientUptake
range: Any
any_of:
- range: double
- range: string

```
</details>