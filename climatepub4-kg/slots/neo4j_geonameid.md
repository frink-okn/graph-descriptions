

# Slot: geonameid (neo4j_geonameid)




This slot occurs 41059 times.


URI: [neo4j:geonameid](neo4j://graph.schema#geonameid)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#WaterBodies](../classes/HttpsClimatepub4kg.github.ioOntology#WaterBodies.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#City](../classes/HttpsClimatepub4kg.github.ioOntology#City.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#NoCountryRegion](../classes/HttpsClimatepub4kg.github.ioOntology#NoCountryRegion.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Country](../classes/HttpsClimatepub4kg.github.ioOntology#Country.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#CountrySubdivision](../classes/HttpsClimatepub4kg.github.ioOntology#CountrySubdivision.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Continent](../classes/HttpsClimatepub4kg.github.ioOntology#Continent.md) |  |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: neo4j_geonameid
title: geonameid
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: neo4j:geonameid
alias: neo4j_geonameid
domain_of:
- https___climatepub4kg.github.io_ontology#City
- https___climatepub4kg.github.io_ontology#Continent
- https___climatepub4kg.github.io_ontology#Country
- https___climatepub4kg.github.io_ontology#Country_Subdivision
- https___climatepub4kg.github.io_ontology#No_Country_Region
- https___climatepub4kg.github.io_ontology#Water_Bodies
union_of:
- neo4j_City
- neo4j_Water_Bodies
- neo4j_Country
- neo4j_Country_Subdivision
- neo4j_No_Country_Region
- neo4j_Continent
range: string

```
</details>