

# Slot: neo4j_source


_No slot (predicate) description specified_





URI: [neo4j:source](neo4j://graph.schema#source)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jDisease](../classes/Neo4jDisease.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| neo4j_Disease → string | neo4j://graph.individuals#142359 | neo4j:source | Disease Ontology |


## Comments

* 180 occurrences with subject type neo4j_Disease and object type string.

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
description: No slot (predicate) description specified
comments:
- 180 occurrences with subject type neo4j_Disease and object type string.
examples:
- description: neo4j_Disease → string
  object:
    example_object: Disease Ontology
    example_predicate: neo4j:source
    example_subject: neo4j://graph.individuals#142359
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:source
alias: neo4j_source
domain_of:
- neo4j_Disease
range: string

```
</details>