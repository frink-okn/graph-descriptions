

# Slot: sockg_lowerDepth_cm


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:lowerDepth_cm](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/lowerDepth_cm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSoilBiologicalSample](../classes/SockgSoilBiologicalSample.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgSoilPhysicalSample](../classes/SockgSoilPhysicalSample.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgSoilChemicalSample](../classes/SockgSoilChemicalSample.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#260140 sockg:lowerDepth_cm 30.0 |
| neo4j://graph.individuals#328453 sockg:lowerDepth_cm 15.0 |
| neo4j://graph.individuals#236782 sockg:lowerDepth_cm 120 |

## Comments

* 53833 occurrences with subject type sockg:SoilChemicalSample and object type xsd:double.
* 28082 occurrences with subject type sockg:SoilPhysicalSample and object type xsd:double.
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
| self | sockg:lowerDepth_cm |
| native | soc-kg/main/:sockg_lowerDepth_cm |




## LinkML Source

<details>
```yaml
name: sockg_lowerDepth_cm
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 53833 occurrences with subject type sockg:SoilChemicalSample and object type xsd:double.
- 28082 occurrences with subject type sockg:SoilPhysicalSample and object type xsd:double.
- 18222 occurrences with subject type sockg:SoilBiologicalSample and object type xsd:long.
examples:
- value: neo4j://graph.individuals#260140 sockg:lowerDepth_cm 30.0
- value: neo4j://graph.individuals#328453 sockg:lowerDepth_cm 15.0
- value: neo4j://graph.individuals#236782 sockg:lowerDepth_cm 120
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:lowerDepth_cm
alias: sockg_lowerDepth_cm
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