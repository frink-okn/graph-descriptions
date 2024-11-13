

# Slot: sockg_hasState


_TODO -- tell the world what this slot (predicate) describes._





URI: [sockg:hasState](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/hasState)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgCountry](../classes/SockgCountry.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [SockgState](../classes/SockgState.md)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#46720 sockg:hasState neo4j://graph.individuals#331926 |

## Comments

* 20 occurrences with subject type sockg:Country and object type sockg:State.

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
| self | sockg:hasState |
| native | soc-kg/main/:sockg_hasState |




## LinkML Source

<details>
```yaml
name: sockg_hasState
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 20 occurrences with subject type sockg:Country and object type sockg:State.
examples:
- value: neo4j://graph.individuals#46720 sockg:hasState neo4j://graph.individuals#331926
from_schema: soc-kg/main
rank: 1000
slot_uri: sockg:hasState
alias: sockg_hasState
domain_of:
- sockg_Country
range: sockg_State

```
</details>