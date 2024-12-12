

# Slot: sockg_hasCity


_No slot description provided_





URI: [sockg:hasCity](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/hasCity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgCounty](../classes/SockgCounty.md) | No type description provided |  no  |







## Properties

* Range: [SockgCity](../classes/SockgCity.md)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#46724 sockg:hasCity neo4j://graph.individuals#46688 |

## Comments

* 33 occurrences with subject type sockg:County and object type sockg:City.

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
| self | sockg:hasCity |
| native | soc-kg/main/:sockg_hasCity |




## LinkML Source

<details>
```yaml
name: sockg_hasCity
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 33 occurrences with subject type sockg:County and object type sockg:City.
examples:
- value: neo4j://graph.individuals#46724 sockg:hasCity neo4j://graph.individuals#46688
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:hasCity
alias: sockg_hasCity
domain_of:
- sockg_County
range: sockg_City

```
</details>