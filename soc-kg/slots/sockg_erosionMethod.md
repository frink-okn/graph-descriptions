

# Slot: sockg_erosionMethod


_No slot description provided_





URI: [sockg:erosionMethod](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/erosionMethod)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | No type description provided |  no  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | No type description provided |  no  |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | No type description provided |  no  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#361342 sockg:erosionMethod nan |
| neo4j://graph.individuals#360282 sockg:erosionMethod nan |
| neo4j://graph.individuals#509302 sockg:erosionMethod nan |

## Comments

* 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
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
| self | sockg:erosionMethod |
| native | soc-kg/main/:sockg_erosionMethod |




## LinkML Source

<details>
```yaml
name: sockg_erosionMethod
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
- 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
- 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
examples:
- value: neo4j://graph.individuals#361342 sockg:erosionMethod nan
- value: neo4j://graph.individuals#360282 sockg:erosionMethod nan
- value: neo4j://graph.individuals#509302 sockg:erosionMethod nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:erosionMethod
alias: sockg_erosionMethod
domain_of:
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
range: double

```
</details>