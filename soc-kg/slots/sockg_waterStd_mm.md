

# Slot: sockg_waterStd_mm


_No slot description provided_





URI: [sockg:waterStd_mm](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/waterStd_mm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | No type description provided |  no  |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | No type description provided |  no  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#361263 sockg:waterStd_mm nan |
| neo4j://graph.individuals#359881 sockg:waterStd_mm nan |

## Comments

* 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
* 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.

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
| self | sockg:waterStd_mm |
| native | soc-kg/main/:sockg_waterStd_mm |




## LinkML Source

<details>
```yaml
name: sockg_waterStd_mm
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
- 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
examples:
- value: neo4j://graph.individuals#361263 sockg:waterStd_mm nan
- value: neo4j://graph.individuals#359881 sockg:waterStd_mm nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:waterStd_mm
alias: sockg_waterStd_mm
domain_of:
- sockg_WaterQualityArea
- sockg_WaterQualityConc
range: double

```
</details>