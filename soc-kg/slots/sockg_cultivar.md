

# Slot: sockg_cultivar


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:cultivar](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/cultivar)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgPlantingEvent](../classes/SockgPlantingEvent.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#222400 sockg:cultivar Pioneer P1498AMI |
| neo4j://graph.individuals#220777 sockg:cultivar nan |

## Comments

* 20817 occurrences with subject type sockg:PlantingEvent and object type string.
* 2633 occurrences with subject type sockg:PlantingEvent and object type xsd:double.

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
| self | sockg:cultivar |
| native | soc-kg/main/:sockg_cultivar |




## LinkML Source

<details>
```yaml
name: sockg_cultivar
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 20817 occurrences with subject type sockg:PlantingEvent and object type string.
- 2633 occurrences with subject type sockg:PlantingEvent and object type xsd:double.
examples:
- value: neo4j://graph.individuals#222400 sockg:cultivar Pioneer P1498AMI
- value: neo4j://graph.individuals#220777 sockg:cultivar nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:cultivar
alias: sockg_cultivar
domain_of:
- sockg_PlantingEvent
range: Any
any_of:
- range: string
- range: double

```
</details>