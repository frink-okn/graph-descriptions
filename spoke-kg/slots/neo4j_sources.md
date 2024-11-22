

# Slot: neo4j_sources


_TODO -- tell the world what this slot (predicate) describes._





URI: [neo4j:sources](neo4j://graph.schema#sources)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jSDoH](../classes/Neo4jSDoH.md) | TODO -- tell the world what this class (type) describes |  no  |
| [Neo4jOrganism](../classes/Neo4jOrganism.md) | TODO -- tell the world what this class (type) describes |  no  |
| [Neo4jEnvironment](../classes/Neo4jEnvironment.md) | TODO -- tell the world what this class (type) describes |  no  |
| [Neo4jLocation](../classes/Neo4jLocation.md) | TODO -- tell the world what this class (type) describes |  no  |
| [Neo4jCompound](../classes/Neo4jCompound.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#105029 neo4j:sources Environment Ontology |
| neo4j://graph.individuals#119274 neo4j:sources SNOMED CT |
| neo4j://graph.individuals#123229 neo4j:sources UnitedStatesZipcode_database |
| neo4j://graph.individuals#1961711 neo4j:sources BioCyc |
| neo4j://graph.individuals#105042 neo4j:sources BV-BRC |

## Comments

* 2 occurrences with subject type neo4j_Environment and object type string.
* 1426 occurrences with subject type neo4j_SDoH and object type string.
* 106067 occurrences with subject type neo4j_Location and object type string.
* 3336 occurrences with subject type neo4j_Compound and object type string.
* 321442 occurrences with subject type neo4j_Organism and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

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
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 2 occurrences with subject type neo4j_Environment and object type string.
- 1426 occurrences with subject type neo4j_SDoH and object type string.
- 106067 occurrences with subject type neo4j_Location and object type string.
- 3336 occurrences with subject type neo4j_Compound and object type string.
- 321442 occurrences with subject type neo4j_Organism and object type string.
examples:
- value: neo4j://graph.individuals#105029 neo4j:sources Environment Ontology
- value: neo4j://graph.individuals#119274 neo4j:sources SNOMED CT
- value: neo4j://graph.individuals#123229 neo4j:sources UnitedStatesZipcode_database
- value: neo4j://graph.individuals#1961711 neo4j:sources BioCyc
- value: neo4j://graph.individuals#105042 neo4j:sources BV-BRC
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