

# Slot: sockg_elevation_m


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:elevation_m](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/elevation_m)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgField](../classes/SockgField.md) | TODO -- tell the world what this class (type) describes |  no  |
| [SockgWeatherStation](../classes/SockgWeatherStation.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#55601 sockg:elevation_m nan |
| neo4j://graph.individuals#509298 sockg:elevation_m nan |

## Comments

* 58 occurrences with subject type sockg:Field and object type xsd:double.
* 12 occurrences with subject type sockg:WeatherStation and object type xsd:double.

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
| self | sockg:elevation_m |
| native | soc-kg/main/:sockg_elevation_m |




## LinkML Source

<details>
```yaml
name: sockg_elevation_m
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 58 occurrences with subject type sockg:Field and object type xsd:double.
- 12 occurrences with subject type sockg:WeatherStation and object type xsd:double.
examples:
- value: neo4j://graph.individuals#55601 sockg:elevation_m nan
- value: neo4j://graph.individuals#509298 sockg:elevation_m nan
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:elevation_m
alias: sockg_elevation_m
domain_of:
- sockg_Field
- sockg_WeatherStation
range: double

```
</details>