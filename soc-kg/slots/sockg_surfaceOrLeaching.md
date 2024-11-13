

# Slot: sockg_surfaceOrLeaching


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:surfaceOrLeaching](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/surfaceOrLeaching)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#361259 sockg:surfaceOrLeaching Leaching |
| neo4j://graph.individuals#360315 sockg:surfaceOrLeaching Leaching |

## Comments

* 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
* 667 occurrences with subject type sockg:WaterQualityArea and object type string.

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
| self | sockg:surfaceOrLeaching |
| native | soc-kg/main/:sockg_surfaceOrLeaching |




## LinkML Source

<details>
```yaml
name: sockg_surfaceOrLeaching
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1479 occurrences with subject type sockg:WaterQualityConc and object type string.
- 667 occurrences with subject type sockg:WaterQualityArea and object type string.
examples:
- value: neo4j://graph.individuals#361259 sockg:surfaceOrLeaching Leaching
- value: neo4j://graph.individuals#360315 sockg:surfaceOrLeaching Leaching
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:surfaceOrLeaching
alias: sockg_surfaceOrLeaching
domain_of:
- sockg_WaterQualityArea
- sockg_WaterQualityConc
range: string

```
</details>