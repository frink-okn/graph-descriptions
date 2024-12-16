

# Slot: neo4j_TREATS_CtD


_No slot (predicate) description specified_





URI: [neo4j:TREATS_CtD](neo4j://graph.schema#TREATS_CtD)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jCompound](../classes/Neo4jCompound.md) | No class (type) description specified |  no  |







## Properties

* Range: [Neo4jDisease](../classes/Neo4jDisease.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| neo4j_Compound → neo4j_Disease | neo4j://graph.individuals#399981 | neo4j:TREATS_CtD | neo4j://graph.individuals#145652 |


## Comments

* 163 occurrences with subject type neo4j_Compound and object type neo4j_Disease.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:TREATS_CtD |
| native | spoke-kg/:neo4j_TREATS_CtD |




## LinkML Source

<details>
```yaml
name: neo4j_TREATS_CtD
description: No slot (predicate) description specified
comments:
- 163 occurrences with subject type neo4j_Compound and object type neo4j_Disease.
examples:
- description: neo4j_Compound → neo4j_Disease
  object:
    example_object: neo4j://graph.individuals#145652
    example_predicate: neo4j:TREATS_CtD
    example_subject: neo4j://graph.individuals#399981
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:TREATS_CtD
alias: neo4j_TREATS_CtD
domain_of:
- neo4j_Compound
range: neo4j_Disease

```
</details>