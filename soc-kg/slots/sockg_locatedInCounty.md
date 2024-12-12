

# Slot: sockg_locatedInCounty


_No slot description provided_





URI: [sockg:locatedInCounty](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/locatedInCounty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSite](../classes/SockgSite.md) | No type description provided |  no  |







## Properties

* Range: [SockgCounty](../classes/SockgCounty.md)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#230729 sockg:locatedInCounty neo4j://graph.individuals#46732 |

## Comments

* 61 occurrences with subject type sockg:Site and object type sockg:County.

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
| self | sockg:locatedInCounty |
| native | soc-kg/main/:sockg_locatedInCounty |




## LinkML Source

<details>
```yaml
name: sockg_locatedInCounty
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 61 occurrences with subject type sockg:Site and object type sockg:County.
examples:
- value: neo4j://graph.individuals#230729 sockg:locatedInCounty neo4j://graph.individuals#46732
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:locatedInCounty
alias: sockg_locatedInCounty
domain_of:
- sockg_Site
range: sockg_County

```
</details>