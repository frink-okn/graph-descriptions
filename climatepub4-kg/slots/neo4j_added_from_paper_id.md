

# Slot: added_from_paper_id (neo4j_added_from_paper_id)




This slot occurs 2204 times.


URI: [neo4j:added_from_paper_id](neo4j://graph.schema#added_from_paper_id)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#NaturalHazard](../classes/HttpsClimatepub4kg.github.ioOntology#NaturalHazard.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Metric](../classes/HttpsClimatepub4kg.github.ioOntology#Metric.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#SourceComponent](../classes/HttpsClimatepub4kg.github.ioOntology#SourceComponent.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#WeatherEvent](../classes/HttpsClimatepub4kg.github.ioOntology#WeatherEvent.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Platform](../classes/HttpsClimatepub4kg.github.ioOntology#Platform.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#OceanCirculation](../classes/HttpsClimatepub4kg.github.ioOntology#OceanCirculation.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#SimulationType](../classes/HttpsClimatepub4kg.github.ioOntology#SimulationType.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Teleconnection](../classes/HttpsClimatepub4kg.github.ioOntology#Teleconnection.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#PhysicalFeature](../classes/HttpsClimatepub4kg.github.ioOntology#PhysicalFeature.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Instrument](../classes/HttpsClimatepub4kg.github.ioOntology#Instrument.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#PhysicalScheme](../classes/HttpsClimatepub4kg.github.ioOntology#PhysicalScheme.md) |  |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: neo4j_added_from_paper_id
title: added_from_paper_id
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: neo4j:added_from_paper_id
alias: neo4j_added_from_paper_id
domain_of:
- https___climatepub4kg.github.io_ontology#Instrument
- https___climatepub4kg.github.io_ontology#Metric
- https___climatepub4kg.github.io_ontology#Natural_Hazard
- https___climatepub4kg.github.io_ontology#Ocean_Circulation
- https___climatepub4kg.github.io_ontology#PhysicalFeature
- https___climatepub4kg.github.io_ontology#PhysicalScheme
- https___climatepub4kg.github.io_ontology#Platform
- https___climatepub4kg.github.io_ontology#SimulationType
- https___climatepub4kg.github.io_ontology#SourceComponent
- https___climatepub4kg.github.io_ontology#Teleconnection
- https___climatepub4kg.github.io_ontology#Weather_Event
union_of:
- neo4j_Teleconnection
- neo4j_Weather_Event
- neo4j_Platform
- neo4j_SimulationType
- neo4j_Instrument
- neo4j_Metric
- neo4j_Ocean_Circulation
- neo4j_Natural_Hazard
- neo4j_PhysicalScheme
- neo4j_PhysicalFeature
- neo4j_SourceComponent
range: string

```
</details>