

# Slot: sockg_upperDepth_cm


_No slot description provided_





URI: [sockg:upperDepth_cm](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/upperDepth_cm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilPhysicalSample](../classes/SockgSoilPhysicalSample.md) | No type description provided |  no  |
| [SockgSoilBiologicalSample](../classes/SockgSoilBiologicalSample.md) | No type description provided |  no  |
| [SockgSoilChemicalSample](../classes/SockgSoilChemicalSample.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#320164 sockg:upperDepth_cm 30.0 |
| neo4j://graph.individuals#299540 sockg:upperDepth_cm 0.0 |
| neo4j://graph.individuals#240599 sockg:upperDepth_cm 90 |

## Comments

* 28082 occurrences with subject type sockg:SoilPhysicalSample and object type xsd:double.
* 53833 occurrences with subject type sockg:SoilChemicalSample and object type xsd:double.
* 18222 occurrences with subject type sockg:SoilBiologicalSample and object type xsd:long.

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
| self | sockg:upperDepth_cm |
| native | soc-kg/main/:sockg_upperDepth_cm |




## LinkML Source

<details>
```yaml
name: sockg_upperDepth_cm
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 28082 occurrences with subject type sockg:SoilPhysicalSample and object type xsd:double.
- 53833 occurrences with subject type sockg:SoilChemicalSample and object type xsd:double.
- 18222 occurrences with subject type sockg:SoilBiologicalSample and object type xsd:long.
examples:
- value: neo4j://graph.individuals#320164 sockg:upperDepth_cm 30.0
- value: neo4j://graph.individuals#299540 sockg:upperDepth_cm 0.0
- value: neo4j://graph.individuals#240599 sockg:upperDepth_cm 90
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:upperDepth_cm
alias: sockg_upperDepth_cm
domain_of:
- sockg_SoilBiologicalSample
- sockg_SoilChemicalSample
- sockg_SoilPhysicalSample
range: Any
any_of:
- range: double
- range: integer

```
</details>