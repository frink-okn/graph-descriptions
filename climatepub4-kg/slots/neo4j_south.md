

# Slot: south (neo4j_south)




This slot occurs 4268 times.


URI: [neo4j:south](neo4j://graph.schema#south)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#WaterBodies](../classes/HttpsClimatepub4kg.github.ioOntology#WaterBodies.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#CountrySubdivision](../classes/HttpsClimatepub4kg.github.ioOntology#CountrySubdivision.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Country](../classes/HttpsClimatepub4kg.github.ioOntology#Country.md) |  |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: neo4j_south
title: south
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: neo4j:south
alias: neo4j_south
domain_of:
- https___climatepub4kg.github.io_ontology#Country
- https___climatepub4kg.github.io_ontology#Country_Subdivision
- https___climatepub4kg.github.io_ontology#Water_Bodies
union_of:
- neo4j_Water_Bodies
- neo4j_Country
- neo4j_Country_Subdivision
range: string

```
</details>