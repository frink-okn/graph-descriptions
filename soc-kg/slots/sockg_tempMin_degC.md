

# Slot: sockg_tempMin_degC


_No slot description provided_





URI: [sockg:tempMin_degC](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/tempMin_degC)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgWeatherObservation](../classes/SockgWeatherObservation.md) | No type description provided |  no  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#489925 sockg:tempMin_degC -22.66 |

## Comments

* 147305 occurrences with subject type sockg:WeatherObservation and object type xsd:double.

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
| self | sockg:tempMin_degC |
| native | soc-kg/main/:sockg_tempMin_degC |




## LinkML Source

<details>
```yaml
name: sockg_tempMin_degC
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 147305 occurrences with subject type sockg:WeatherObservation and object type xsd:double.
examples:
- value: neo4j://graph.individuals#489925 sockg:tempMin_degC -22.66
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:tempMin_degC
alias: sockg_tempMin_degC
domain_of:
- sockg_WeatherObservation
range: double

```
</details>