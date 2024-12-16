

# Slot: neo4j_ISA_DiD


_No slot (predicate) description specified_





URI: [neo4j:ISA_DiD](neo4j://graph.schema#ISA_DiD)



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
| neo4j_Disease → neo4j_Disease | neo4j://graph.individuals#152421 | neo4j:ISA_DiD | neo4j://graph.individuals#152053 |


## Comments

* 41 occurrences with subject type neo4j_Disease and object type neo4j_Disease.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:ISA_DiD |
| native | spoke-kg/:neo4j_ISA_DiD |




## LinkML Source

<details>
```yaml
name: neo4j_ISA_DiD
description: No slot (predicate) description specified
comments:
- 41 occurrences with subject type neo4j_Disease and object type neo4j_Disease.
examples:
- description: neo4j_Disease → neo4j_Disease
  object:
    example_object: neo4j://graph.individuals#152053
    example_predicate: neo4j:ISA_DiD
    example_subject: neo4j://graph.individuals#152421
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:ISA_DiD
alias: neo4j_ISA_DiD
domain_of:
- neo4j_Disease
range: neo4j_Disease

```
</details>