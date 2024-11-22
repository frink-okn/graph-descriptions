

# Slot: neo4j_name


_TODO -- tell the world what this slot (predicate) describes._





URI: [neo4j:name](neo4j://graph.schema#name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jSDoH](../classes/Neo4jSDoH.md) | TODO -- tell the world what this class (type) describes |  no  |
| [Neo4jDisease](../classes/Neo4jDisease.md) | TODO -- tell the world what this class (type) describes |  no  |
| [Neo4jOrganism](../classes/Neo4jOrganism.md) | TODO -- tell the world what this class (type) describes |  no  |
| [Neo4jEnvironment](../classes/Neo4jEnvironment.md) | TODO -- tell the world what this class (type) describes |  no  |
| [Neo4jLocation](../classes/Neo4jLocation.md) | TODO -- tell the world what this class (type) describes |  no  |
| [Neo4jCompound](../classes/Neo4jCompound.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| neo4j://graph.individuals#105029 neo4j:name respirable suspended particulate matter |
| neo4j://graph.individuals#119274 neo4j:name Social scientist (occupation) |
| neo4j://graph.individuals#123229 neo4j:name Outside city limits |
| neo4j://graph.individuals#142359 neo4j:name giant cell glioblastoma |
| neo4j://graph.individuals#1961711 neo4j:name Tetracycline |
| neo4j://graph.individuals#105042 neo4j:name Acetobacter tropicalis strain DmPark25_167 |

## Comments

* 2 occurrences with subject type neo4j_Environment and object type string.
* 1426 occurrences with subject type neo4j_SDoH and object type string.
* 106067 occurrences with subject type neo4j_Location and object type string.
* 180 occurrences with subject type neo4j_Disease and object type string.
* 798 occurrences with subject type neo4j_Compound and object type string.
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
| self | neo4j:name |
| native | spoke-kg/:neo4j_name |




## LinkML Source

<details>
```yaml
name: neo4j_name
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 2 occurrences with subject type neo4j_Environment and object type string.
- 1426 occurrences with subject type neo4j_SDoH and object type string.
- 106067 occurrences with subject type neo4j_Location and object type string.
- 180 occurrences with subject type neo4j_Disease and object type string.
- 798 occurrences with subject type neo4j_Compound and object type string.
- 321442 occurrences with subject type neo4j_Organism and object type string.
examples:
- value: neo4j://graph.individuals#105029 neo4j:name respirable suspended particulate
    matter
- value: neo4j://graph.individuals#119274 neo4j:name Social scientist (occupation)
- value: neo4j://graph.individuals#123229 neo4j:name Outside city limits
- value: neo4j://graph.individuals#142359 neo4j:name giant cell glioblastoma
- value: neo4j://graph.individuals#1961711 neo4j:name Tetracycline
- value: neo4j://graph.individuals#105042 neo4j:name Acetobacter tropicalis strain
    DmPark25_167
from_schema: spoke-kg
rank: 1000
slot_uri: neo4j:name
alias: neo4j_name
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