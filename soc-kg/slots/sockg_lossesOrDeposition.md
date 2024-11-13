

# Slot: sockg_lossesOrDeposition


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:lossesOrDeposition](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/lossesOrDeposition)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#360365 sockg:lossesOrDeposition nan |
| neo4j://graph.individuals#359910 sockg:lossesOrDeposition Deposition |
| neo4j://graph.individuals#509301 sockg:lossesOrDeposition Losses |
| neo4j://graph.individuals#509305 sockg:lossesOrDeposition nan |

## Comments

* 549 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
* 118 occurrences with subject type sockg:WaterQualityArea and object type string.
* 5 occurrences with subject type sockg:WindErosionArea and object type string.
* 10 occurrences with subject type sockg:WindErosionArea and object type xsd:double.

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
| self | sockg:lossesOrDeposition |
| native | soc-kg/main/:sockg_lossesOrDeposition |




## LinkML Source

<details>
```yaml
name: sockg_lossesOrDeposition
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 549 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
- 118 occurrences with subject type sockg:WaterQualityArea and object type string.
- 5 occurrences with subject type sockg:WindErosionArea and object type string.
- 10 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
examples:
- value: neo4j://graph.individuals#360365 sockg:lossesOrDeposition nan
- value: neo4j://graph.individuals#359910 sockg:lossesOrDeposition Deposition
- value: neo4j://graph.individuals#509301 sockg:lossesOrDeposition Losses
- value: neo4j://graph.individuals#509305 sockg:lossesOrDeposition nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:lossesOrDeposition
alias: sockg_lossesOrDeposition
domain_of:
- sockg_WaterQualityArea
- sockg_WindErosionArea
range: Any
any_of:
- range: double
- range: string

```
</details>