

# Slot: asciiname (neo4j_asciiname)




This slot occurs 40677 times.


URI: [neo4j:asciiname](neo4j://graph.schema#asciiname)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#NoCountryRegion](../classes/HttpsClimatepub4kg.github.ioOntology#NoCountryRegion.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#CountrySubdivision](../classes/HttpsClimatepub4kg.github.ioOntology#CountrySubdivision.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#City](../classes/HttpsClimatepub4kg.github.ioOntology#City.md) |  |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: neo4j_asciiname
title: asciiname
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: neo4j:asciiname
alias: neo4j_asciiname
domain_of:
- https___climatepub4kg.github.io_ontology#City
- https___climatepub4kg.github.io_ontology#Country_Subdivision
- https___climatepub4kg.github.io_ontology#No_Country_Region
union_of:
- neo4j_No_Country_Region
- neo4j_Country_Subdivision
- neo4j_City
range: string

```
</details>