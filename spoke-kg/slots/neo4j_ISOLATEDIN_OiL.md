

# Slot: neo4j_ISOLATEDIN_OiL


_No slot (predicate) description specified_





URI: [neo4j:ISOLATEDIN_OiL](neo4j://graph.schema#ISOLATEDIN_OiL)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jOrganism](../classes/Neo4jOrganism.md) | No class (type) description specified |  no  |







## Properties

* Range: [Neo4jLocation](../classes/Neo4jLocation.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| neo4j_Organism → neo4j_Location | neo4j://graph.individuals#38641 | neo4j:ISOLATEDIN_OiL | neo4j://graph.individuals#80505 |


## Comments

* 321442 occurrences with subject type neo4j_Organism and object type neo4j_Location.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:ISOLATEDIN_OiL |
| native | spoke-kg/:neo4j_ISOLATEDIN_OiL |




## LinkML Source

<details>
```yaml
name: neo4j_ISOLATEDIN_OiL
description: No slot (predicate) description specified
comments:
- 321442 occurrences with subject type neo4j_Organism and object type neo4j_Location.
examples:
- description: neo4j_Organism → neo4j_Location
  object:
    example_object: neo4j://graph.individuals#80505
    example_predicate: neo4j:ISOLATEDIN_OiL
    example_subject: neo4j://graph.individuals#38641
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:ISOLATEDIN_OiL
alias: neo4j_ISOLATEDIN_OiL
domain_of:
- neo4j_Organism
range: neo4j_Location

```
</details>