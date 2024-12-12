

# Slot: sockg_weatherRecordedBy


_No slot description provided_





URI: [sockg:weatherRecordedBy](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/weatherRecordedBy)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherStation](../classes/SockgWeatherStation.md) | No type description provided |  no  |







## Properties

* Range: [SockgWeatherObservation](../classes/SockgWeatherObservation.md)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#509289 sockg:weatherRecordedBy neo4j://graph.individuals#442714 |

## Comments

* 39489 occurrences with subject type sockg:WeatherStation and object type sockg:WeatherObservation.

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
| self | sockg:weatherRecordedBy |
| native | soc-kg/main/:sockg_weatherRecordedBy |




## LinkML Source

<details>
```yaml
name: sockg_weatherRecordedBy
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 39489 occurrences with subject type sockg:WeatherStation and object type sockg:WeatherObservation.
examples:
- value: neo4j://graph.individuals#509289 sockg:weatherRecordedBy neo4j://graph.individuals#442714
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:weatherRecordedBy
alias: sockg_weatherRecordedBy
domain_of:
- sockg_WeatherStation
range: sockg_WeatherObservation

```
</details>