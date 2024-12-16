

# Slot: neo4j_RESEMBLES_DrD


_No slot (predicate) description specified_





URI: [neo4j:RESEMBLES_DrD](neo4j://graph.schema#RESEMBLES_DrD)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jDisease](../classes/Neo4jDisease.md) | No class (type) description specified |  no  |







## Properties

* Range: [Neo4jDisease](../classes/Neo4jDisease.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| neo4j_Disease → neo4j_Disease | neo4j://graph.individuals#152554 | neo4j:RESEMBLES_DrD | neo4j://graph.individuals#144201 |


## Comments

* 67 occurrences with subject type neo4j_Disease and object type neo4j_Disease.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:RESEMBLES_DrD |
| native | spoke-kg/:neo4j_RESEMBLES_DrD |




## LinkML Source

<details>
```yaml
name: neo4j_RESEMBLES_DrD
description: No slot (predicate) description specified
comments:
- 67 occurrences with subject type neo4j_Disease and object type neo4j_Disease.
examples:
- description: neo4j_Disease → neo4j_Disease
  object:
    example_object: neo4j://graph.individuals#144201
    example_predicate: neo4j:RESEMBLES_DrD
    example_subject: neo4j://graph.individuals#152554
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:RESEMBLES_DrD
alias: neo4j_RESEMBLES_DrD
domain_of:
- neo4j_Disease
range: neo4j_Disease

```
</details>