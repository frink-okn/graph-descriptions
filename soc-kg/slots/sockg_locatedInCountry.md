

# Slot: sockg_locatedInCountry


_No slot description provided_





URI: [sockg:locatedInCountry](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/locatedInCountry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSite](../classes/SockgSite.md) | No type description provided |  no  |







## Properties

* Range: [SockgCountry](../classes/SockgCountry.md)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#230715 sockg:locatedInCountry neo4j://graph.individuals#46720 |

## Comments

* 60 occurrences with subject type sockg:Site and object type sockg:Country.

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
| self | sockg:locatedInCountry |
| native | soc-kg/main/:sockg_locatedInCountry |




## LinkML Source

<details>
```yaml
name: sockg_locatedInCountry
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 60 occurrences with subject type sockg:Site and object type sockg:Country.
examples:
- value: neo4j://graph.individuals#230715 sockg:locatedInCountry neo4j://graph.individuals#46720
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:locatedInCountry
alias: sockg_locatedInCountry
domain_of:
- sockg_Site
range: sockg_Country

```
</details>