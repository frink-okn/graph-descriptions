

# Slot: neo4j_MORTALITY_DmL


_No slot (predicate) description specified_





URI: [neo4j:MORTALITY_DmL](neo4j://graph.schema#MORTALITY_DmL)



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
| neo4j_Disease → neo4j_Location | neo4j://graph.individuals#152579 | neo4j:MORTALITY_DmL | neo4j://graph.individuals#80756 |


## Comments

* 10802 occurrences with subject type neo4j_Disease and object type neo4j_Location.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:MORTALITY_DmL |
| native | spoke-kg/:neo4j_MORTALITY_DmL |




## LinkML Source

<details>
```yaml
name: neo4j_MORTALITY_DmL
description: No slot (predicate) description specified
comments:
- 10802 occurrences with subject type neo4j_Disease and object type neo4j_Location.
examples:
- description: neo4j_Disease → neo4j_Location
  object:
    example_object: neo4j://graph.individuals#80756
    example_predicate: neo4j:MORTALITY_DmL
    example_subject: neo4j://graph.individuals#152579
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:MORTALITY_DmL
alias: neo4j_MORTALITY_DmL
domain_of:
- neo4j_Disease
range: neo4j_Location

```
</details>