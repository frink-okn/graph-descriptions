

# Slot: neo4j_sources


_No slot (predicate) description specified_





URI: [neo4j:sources](neo4j://graph.schema#sources)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jCompound](../classes/Neo4jCompound.md) | No class (type) description specified |  no  |
| [Neo4jLocation](../classes/Neo4jLocation.md) | No class (type) description specified |  no  |
| [Neo4jEnvironment](../classes/Neo4jEnvironment.md) | No class (type) description specified |  no  |
| [Neo4jSDoH](../classes/Neo4jSDoH.md) | No class (type) description specified |  no  |
| [Neo4jOrganism](../classes/Neo4jOrganism.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| neo4j_Environment → string | neo4j://graph.individuals#105029 | neo4j:sources | Environment Ontology |
| neo4j_SDoH → string | neo4j://graph.individuals#119274 | neo4j:sources | SNOMED CT |
| neo4j_Location → string | neo4j://graph.individuals#123229 | neo4j:sources | UnitedStatesZipcode_database |
| neo4j_Compound → string | neo4j://graph.individuals#1961711 | neo4j:sources | BioCyc |
| neo4j_Organism → string | neo4j://graph.individuals#105042 | neo4j:sources | BV-BRC |


## Comments

* 2 occurrences with subject type neo4j_Environment and object type string.
* 1426 occurrences with subject type neo4j_SDoH and object type string.
* 106067 occurrences with subject type neo4j_Location and object type string.
* 3336 occurrences with subject type neo4j_Compound and object type string.
* 321442 occurrences with subject type neo4j_Organism and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:sources |
| native | spoke-kg/:neo4j_sources |




## LinkML Source

<details>
```yaml
name: neo4j_sources
description: No slot (predicate) description specified
comments:
- 2 occurrences with subject type neo4j_Environment and object type string.
- 1426 occurrences with subject type neo4j_SDoH and object type string.
- 106067 occurrences with subject type neo4j_Location and object type string.
- 3336 occurrences with subject type neo4j_Compound and object type string.
- 321442 occurrences with subject type neo4j_Organism and object type string.
examples:
- description: neo4j_Environment → string
  object:
    example_object: Environment Ontology
    example_predicate: neo4j:sources
    example_subject: neo4j://graph.individuals#105029
- description: neo4j_SDoH → string
  object:
    example_object: SNOMED CT
    example_predicate: neo4j:sources
    example_subject: neo4j://graph.individuals#119274
- description: neo4j_Location → string
  object:
    example_object: UnitedStatesZipcode_database
    example_predicate: neo4j:sources
    example_subject: neo4j://graph.individuals#123229
- description: neo4j_Compound → string
  object:
    example_object: BioCyc
    example_predicate: neo4j:sources
    example_subject: neo4j://graph.individuals#1961711
- description: neo4j_Organism → string
  object:
    example_object: BV-BRC
    example_predicate: neo4j:sources
    example_subject: neo4j://graph.individuals#105042
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:sources
alias: neo4j_sources
domain_of:
- neo4j_Compound
- neo4j_Environment
- neo4j_Location
- neo4j_Organism
- neo4j_SDoH
range: string

```
</details>