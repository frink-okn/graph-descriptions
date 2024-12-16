

# Slot: neo4j_PARTOF_CpC


_No slot (predicate) description specified_





URI: [neo4j:PARTOF_CpC](neo4j://graph.schema#PARTOF_CpC)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jCompound](../classes/Neo4jCompound.md) | No class (type) description specified |  no  |







## Properties

* Range: [Neo4jCompound](../classes/Neo4jCompound.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| neo4j_Compound → neo4j_Compound | neo4j://graph.individuals#395317 | neo4j:PARTOF_CpC | neo4j://graph.individuals#395791 |


## Comments

* 18 occurrences with subject type neo4j_Compound and object type neo4j_Compound.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:PARTOF_CpC |
| native | spoke-kg/:neo4j_PARTOF_CpC |




## LinkML Source

<details>
```yaml
name: neo4j_PARTOF_CpC
description: No slot (predicate) description specified
comments:
- 18 occurrences with subject type neo4j_Compound and object type neo4j_Compound.
examples:
- description: neo4j_Compound → neo4j_Compound
  object:
    example_object: neo4j://graph.individuals#395791
    example_predicate: neo4j:PARTOF_CpC
    example_subject: neo4j://graph.individuals#395317
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:PARTOF_CpC
alias: neo4j_PARTOF_CpC
domain_of:
- neo4j_Compound
range: neo4j_Compound

```
</details>