

# Slot: sockg_ph


_No slot description provided_





URI: [sockg:ph](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/ph)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | No type description provided |  no  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | No type description provided |  no  |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | No type description provided |  no  |
| [SockgSoilChemicalSample](../classes/SockgSoilChemicalSample.md) | No type description provided |  no  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#272323 sockg:ph nan |
| neo4j://graph.individuals#360143 sockg:ph nan |
| neo4j://graph.individuals#360790 sockg:ph nan |
| neo4j://graph.individuals#509304 sockg:ph nan |

## Comments

* 53833 occurrences with subject type sockg:SoilChemicalSample and object type xsd:double.
* 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
* 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
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
| self | sockg:ph |
| native | soc-kg/main/:sockg_ph |




## LinkML Source

<details>
```yaml
name: sockg_ph
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 53833 occurrences with subject type sockg:SoilChemicalSample and object type xsd:double.
- 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
- 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
- 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
examples:
- value: neo4j://graph.individuals#272323 sockg:ph nan
- value: neo4j://graph.individuals#360143 sockg:ph nan
- value: neo4j://graph.individuals#360790 sockg:ph nan
- value: neo4j://graph.individuals#509304 sockg:ph nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:ph
alias: sockg_ph
domain_of:
- sockg_SoilChemicalSample
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
range: double

```
</details>