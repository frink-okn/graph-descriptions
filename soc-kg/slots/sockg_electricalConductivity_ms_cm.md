

# Slot: sockg_electricalConductivity_ms_cm


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:electricalConductivity_ms_cm](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/electricalConductivity_ms_cm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWaterQualityConc](../classes/SockgWaterQualityConc.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgWindErosionArea](../classes/SockgWindErosionArea.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgWaterQualityArea](../classes/SockgWaterQualityArea.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#361630 sockg:electricalConductivity_ms_cm nan |
| neo4j://graph.individuals#509308 sockg:electricalConductivity_ms_cm nan |
| neo4j://graph.individuals#359870 sockg:electricalConductivity_ms_cm nan |

## Comments

* 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
* 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
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
| self | sockg:electricalConductivity_ms_cm |
| native | soc-kg/main/:sockg_electricalConductivity_ms_cm |




## LinkML Source

<details>
```yaml
name: sockg_electricalConductivity_ms_cm
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1479 occurrences with subject type sockg:WaterQualityConc and object type xsd:double.
- 15 occurrences with subject type sockg:WindErosionArea and object type xsd:double.
- 667 occurrences with subject type sockg:WaterQualityArea and object type xsd:double.
examples:
- value: neo4j://graph.individuals#361630 sockg:electricalConductivity_ms_cm nan
- value: neo4j://graph.individuals#509308 sockg:electricalConductivity_ms_cm nan
- value: neo4j://graph.individuals#359870 sockg:electricalConductivity_ms_cm nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:electricalConductivity_ms_cm
alias: sockg_electricalConductivity_ms_cm
domain_of:
- sockg_WaterQualityArea
- sockg_WaterQualityConc
- sockg_WindErosionArea
range: double

```
</details>