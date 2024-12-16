

# Slot: neo4j_PARTOF_LpL


_No slot (predicate) description specified_





URI: [neo4j:PARTOF_LpL](neo4j://graph.schema#PARTOF_LpL)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jLocation](../classes/Neo4jLocation.md) | No class (type) description specified |  no  |







## Properties

* Range: [Neo4jLocation](../classes/Neo4jLocation.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| neo4j_Location → neo4j_Location | neo4j://graph.individuals#84571 | neo4j:PARTOF_LpL | neo4j://graph.individuals#80740 |


## Comments

* 119810 occurrences with subject type neo4j_Location and object type neo4j_Location.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:PARTOF_LpL |
| native | spoke-kg/:neo4j_PARTOF_LpL |




## LinkML Source

<details>
```yaml
name: neo4j_PARTOF_LpL
description: No slot (predicate) description specified
comments:
- 119810 occurrences with subject type neo4j_Location and object type neo4j_Location.
examples:
- description: neo4j_Location → neo4j_Location
  object:
    example_object: neo4j://graph.individuals#80740
    example_predicate: neo4j:PARTOF_LpL
    example_subject: neo4j://graph.individuals#84571
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:PARTOF_LpL
alias: neo4j_PARTOF_LpL
domain_of:
- neo4j_Location
range: neo4j_Location

```
</details>