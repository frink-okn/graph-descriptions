

# Slot: neo4j_ASSOCIATES_SaD


_No slot (predicate) description specified_





URI: [neo4j:ASSOCIATES_SaD](neo4j://graph.schema#ASSOCIATES_SaD)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jSDoH](../classes/Neo4jSDoH.md) | No class (type) description specified |  no  |







## Properties

* Range: [Neo4jDisease](../classes/Neo4jDisease.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| neo4j_SDoH → neo4j_Disease | neo4j://graph.individuals#29589048 | neo4j:ASSOCIATES_SaD | neo4j://graph.individuals#152986 |


## Comments

* 39 occurrences with subject type neo4j_SDoH and object type neo4j_Disease.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:ASSOCIATES_SaD |
| native | spoke-kg/:neo4j_ASSOCIATES_SaD |




## LinkML Source

<details>
```yaml
name: neo4j_ASSOCIATES_SaD
description: No slot (predicate) description specified
comments:
- 39 occurrences with subject type neo4j_SDoH and object type neo4j_Disease.
examples:
- description: neo4j_SDoH → neo4j_Disease
  object:
    example_object: neo4j://graph.individuals#152986
    example_predicate: neo4j:ASSOCIATES_SaD
    example_subject: neo4j://graph.individuals#29589048
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:ASSOCIATES_SaD
alias: neo4j_ASSOCIATES_SaD
domain_of:
- neo4j_SDoH
range: neo4j_Disease

```
</details>