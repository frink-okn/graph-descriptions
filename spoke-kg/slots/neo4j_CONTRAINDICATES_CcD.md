

# Slot: neo4j_CONTRAINDICATES_CcD


_No slot (predicate) description specified_





URI: [neo4j:CONTRAINDICATES_CcD](neo4j://graph.schema#CONTRAINDICATES_CcD)



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
| neo4j_Compound → neo4j_Disease | neo4j://graph.individuals#387655 | neo4j:CONTRAINDICATES_CcD | neo4j://graph.individuals#152911 |


## Comments

* 51 occurrences with subject type neo4j_Compound and object type neo4j_Disease.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:CONTRAINDICATES_CcD |
| native | spoke-kg/:neo4j_CONTRAINDICATES_CcD |




## LinkML Source

<details>
```yaml
name: neo4j_CONTRAINDICATES_CcD
description: No slot (predicate) description specified
comments:
- 51 occurrences with subject type neo4j_Compound and object type neo4j_Disease.
examples:
- description: neo4j_Compound → neo4j_Disease
  object:
    example_object: neo4j://graph.individuals#152911
    example_predicate: neo4j:CONTRAINDICATES_CcD
    example_subject: neo4j://graph.individuals#387655
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:CONTRAINDICATES_CcD
alias: neo4j_CONTRAINDICATES_CcD
domain_of:
- neo4j_Compound
range: neo4j_Disease

```
</details>