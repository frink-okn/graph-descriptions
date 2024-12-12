

# Slot: neo4j_source


_No slot description provided_





URI: [neo4j:source](neo4j://graph.schema#source)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jDisease](../classes/Neo4jDisease.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#142359 neo4j:source Disease Ontology |

## Comments

* 180 occurrences with subject type neo4j_Disease and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:source |
| native | spoke-kg/:neo4j_source |




## LinkML Source

<details>
```yaml
name: neo4j_source
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 180 occurrences with subject type neo4j_Disease and object type string.
examples:
- value: neo4j://graph.individuals#142359 neo4j:source Disease Ontology
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:source
alias: neo4j_source
domain_of:
- neo4j_Disease
range: string

```
</details>