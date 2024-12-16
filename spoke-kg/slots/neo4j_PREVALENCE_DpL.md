

# Slot: neo4j_PREVALENCE_DpL


_No slot (predicate) description specified_





URI: [neo4j:PREVALENCE_DpL](neo4j://graph.schema#PREVALENCE_DpL)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jDisease](../classes/Neo4jDisease.md) | No class (type) description specified |  no  |







## Properties

* Range: [Neo4jLocation](../classes/Neo4jLocation.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| neo4j_Disease → neo4j_Location | neo4j://graph.individuals#153323 | neo4j:PREVALENCE_DpL | neo4j://graph.individuals#80756 |


## Comments

* 275085 occurrences with subject type neo4j_Disease and object type neo4j_Location.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:PREVALENCE_DpL |
| native | spoke-kg/:neo4j_PREVALENCE_DpL |




## LinkML Source

<details>
```yaml
name: neo4j_PREVALENCE_DpL
description: No slot (predicate) description specified
comments:
- 275085 occurrences with subject type neo4j_Disease and object type neo4j_Location.
examples:
- description: neo4j_Disease → neo4j_Location
  object:
    example_object: neo4j://graph.individuals#80756
    example_predicate: neo4j:PREVALENCE_DpL
    example_subject: neo4j://graph.individuals#153323
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:PREVALENCE_DpL
alias: neo4j_PREVALENCE_DpL
domain_of:
- neo4j_Disease
range: neo4j_Location

```
</details>