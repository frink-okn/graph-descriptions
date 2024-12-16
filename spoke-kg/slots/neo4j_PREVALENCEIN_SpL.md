

# Slot: neo4j_PREVALENCEIN_SpL


_No slot (predicate) description specified_





URI: [neo4j:PREVALENCEIN_SpL](neo4j://graph.schema#PREVALENCEIN_SpL)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jSDoH](../classes/Neo4jSDoH.md) | No class (type) description specified |  no  |







## Properties

* Range: [Neo4jLocation](../classes/Neo4jLocation.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| neo4j_SDoH → neo4j_Location | neo4j://graph.individuals#29697526 | neo4j:PREVALENCEIN_SpL | neo4j://graph.individuals#29671883 |


## Comments

* 2999117 occurrences with subject type neo4j_SDoH and object type neo4j_Location.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:PREVALENCEIN_SpL |
| native | spoke-kg/:neo4j_PREVALENCEIN_SpL |




## LinkML Source

<details>
```yaml
name: neo4j_PREVALENCEIN_SpL
description: No slot (predicate) description specified
comments:
- 2999117 occurrences with subject type neo4j_SDoH and object type neo4j_Location.
examples:
- description: neo4j_SDoH → neo4j_Location
  object:
    example_object: neo4j://graph.individuals#29671883
    example_predicate: neo4j:PREVALENCEIN_SpL
    example_subject: neo4j://graph.individuals#29697526
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:PREVALENCEIN_SpL
alias: neo4j_PREVALENCEIN_SpL
domain_of:
- neo4j_SDoH
range: neo4j_Location

```
</details>