

# Slot: sockg_phStd


_No slot description provided_





URI: [sockg:phStd](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/phStd)



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
| neo4j://graph.individuals#360695 sockg:phStd nan |
| neo4j://graph.individuals#359965 sockg:phStd nan |
| neo4j://graph.individuals#509304 sockg:phStd nan |

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
| self | sockg:phStd |
| native | soc-kg/main/:sockg_phStd |




## LinkML Source

<details>
```yaml
name: sockg_phStd
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
- value: neo4j://graph.individuals#360695 sockg:phStd nan
- value: neo4j://graph.individuals#359965 sockg:phStd nan
- value: neo4j://graph.individuals#509304 sockg:phStd nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:phStd
alias: sockg_phStd
domain_of:
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
range: double

```
</details>