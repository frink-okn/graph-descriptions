

# Slot: neo4j_identifier


_No slot (predicate) description specified_





URI: [neo4j:identifier](neo4j://graph.schema#identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jCompound](../classes/Neo4jCompound.md) | No class (type) description specified |  no  |
| [Neo4jLocation](../classes/Neo4jLocation.md) | No class (type) description specified |  no  |
| [Neo4jDisease](../classes/Neo4jDisease.md) | No class (type) description specified |  no  |
| [Neo4jEnvironment](../classes/Neo4jEnvironment.md) | No class (type) description specified |  no  |
| [Neo4jSDoH](../classes/Neo4jSDoH.md) | No class (type) description specified |  no  |
| [Neo4jOrganism](../classes/Neo4jOrganism.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| neo4j_Environment → string | neo4j://graph.individuals#105029 | neo4j:identifier | ENVO_01000405 |
| neo4j_SDoH → string | neo4j://graph.individuals#119274 | neo4j:identifier | 158928002 |
| neo4j_Location → string | neo4j://graph.individuals#123229 | neo4j:identifier | 049999985379 |
| neo4j_Disease → string | neo4j://graph.individuals#142359 | neo4j:identifier | DOID:3074 |
| neo4j_Compound → string | neo4j://graph.individuals#1961711 | neo4j:identifier | inchikey:NWXMGUDVXFXRIG-WESIUVDSSA-N |
| neo4j_Organism → string | neo4j://graph.individuals#105042 | neo4j:identifier | 104102.36 |


## Comments

* 2 occurrences with subject type neo4j_Environment and object type string.
* 1426 occurrences with subject type neo4j_SDoH and object type string.
* 106067 occurrences with subject type neo4j_Location and object type string.
* 180 occurrences with subject type neo4j_Disease and object type string.
* 798 occurrences with subject type neo4j_Compound and object type string.
* 321442 occurrences with subject type neo4j_Organism and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:identifier |
| native | spoke-kg/:neo4j_identifier |




## LinkML Source

<details>
```yaml
name: neo4j_identifier
description: No slot (predicate) description specified
comments:
- 2 occurrences with subject type neo4j_Environment and object type string.
- 1426 occurrences with subject type neo4j_SDoH and object type string.
- 106067 occurrences with subject type neo4j_Location and object type string.
- 180 occurrences with subject type neo4j_Disease and object type string.
- 798 occurrences with subject type neo4j_Compound and object type string.
- 321442 occurrences with subject type neo4j_Organism and object type string.
examples:
- description: neo4j_Environment → string
  object:
    example_object: ENVO_01000405
    example_predicate: neo4j:identifier
    example_subject: neo4j://graph.individuals#105029
- description: neo4j_SDoH → string
  object:
    example_object: '158928002'
    example_predicate: neo4j:identifier
    example_subject: neo4j://graph.individuals#119274
- description: neo4j_Location → string
  object:
    example_object: 049999985379
    example_predicate: neo4j:identifier
    example_subject: neo4j://graph.individuals#123229
- description: neo4j_Disease → string
  object:
    example_object: DOID:3074
    example_predicate: neo4j:identifier
    example_subject: neo4j://graph.individuals#142359
- description: neo4j_Compound → string
  object:
    example_object: inchikey:NWXMGUDVXFXRIG-WESIUVDSSA-N
    example_predicate: neo4j:identifier
    example_subject: neo4j://graph.individuals#1961711
- description: neo4j_Organism → string
  object:
    example_object: '104102.36'
    example_predicate: neo4j:identifier
    example_subject: neo4j://graph.individuals#105042
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:identifier
alias: neo4j_identifier
domain_of:
- neo4j_Compound
- neo4j_Disease
- neo4j_Environment
- neo4j_Location
- neo4j_Organism
- neo4j_SDoH
range: string

```
</details>