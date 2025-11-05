

# Slot: neo4j_name




This slot occurs 429915 times.


URI: [neo4j:name](neo4j://graph.schema#name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Neo4jLocation](../classes/Neo4jLocation.md) |  |  no  |
| [Neo4jCompound](../classes/Neo4jCompound.md) |  |  no  |
| [Neo4jOrganism](../classes/Neo4jOrganism.md) |  |  no  |
| [Neo4jDisease](../classes/Neo4jDisease.md) |  |  no  |
| [Neo4jSDoH](../classes/Neo4jSDoH.md) |  |  no  |
| [Neo4jEnvironment](../classes/Neo4jEnvironment.md) |  |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: neo4j_name
from_schema: okns:spoke-kg
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