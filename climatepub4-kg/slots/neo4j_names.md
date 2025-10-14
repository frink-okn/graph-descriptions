

# Slot: names (neo4j_names)




This slot occurs 10876 times.


URI: [neo4j:names](neo4j://graph.schema#names)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#SubExperiment](../classes/HttpsClimatepub4kg.github.ioOntology#SubExperiment.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Domain](../classes/HttpsClimatepub4kg.github.ioOntology#Domain.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Forcing](../classes/HttpsClimatepub4kg.github.ioOntology#Forcing.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Ensemble](../classes/HttpsClimatepub4kg.github.ioOntology#Ensemble.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#MIPEra](../classes/HttpsClimatepub4kg.github.ioOntology#MIPEra.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Member](../classes/HttpsClimatepub4kg.github.ioOntology#Member.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Activity](../classes/HttpsClimatepub4kg.github.ioOntology#Activity.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#RCM](../classes/HttpsClimatepub4kg.github.ioOntology#RCM.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Resolution](../classes/HttpsClimatepub4kg.github.ioOntology#Resolution.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#SourceType](../classes/HttpsClimatepub4kg.github.ioOntology#SourceType.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Variable](../classes/HttpsClimatepub4kg.github.ioOntology#Variable.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Frequency](../classes/HttpsClimatepub4kg.github.ioOntology#Frequency.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Realm](../classes/HttpsClimatepub4kg.github.ioOntology#Realm.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#ExperimentFamily](../classes/HttpsClimatepub4kg.github.ioOntology#ExperimentFamily.md) |  |  no  |
| [HttpsClimatepub4kg.github.ioOntology#Institute](../classes/HttpsClimatepub4kg.github.ioOntology#Institute.md) |  |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: neo4j_names
title: names
from_schema: okns:climatepub4-kg
rank: 1000
slot_uri: neo4j:names
alias: neo4j_names
domain_of:
- https___climatepub4kg.github.io_ontology#Activity
- https___climatepub4kg.github.io_ontology#Domain
- https___climatepub4kg.github.io_ontology#Ensemble
- https___climatepub4kg.github.io_ontology#Experiment
- https___climatepub4kg.github.io_ontology#ExperimentFamily
- https___climatepub4kg.github.io_ontology#Forcing
- https___climatepub4kg.github.io_ontology#Frequency
- https___climatepub4kg.github.io_ontology#Institute
- https___climatepub4kg.github.io_ontology#MIPEra
- https___climatepub4kg.github.io_ontology#Member
- https___climatepub4kg.github.io_ontology#Project
- https___climatepub4kg.github.io_ontology#RCM
- https___climatepub4kg.github.io_ontology#Realm
- https___climatepub4kg.github.io_ontology#Resolution
- https___climatepub4kg.github.io_ontology#Source
- https___climatepub4kg.github.io_ontology#SourceType
- https___climatepub4kg.github.io_ontology#SubExperiment
- https___climatepub4kg.github.io_ontology#Variable
union_of:
- neo4j_Experiment
- neo4j_Institute
- neo4j_Member
- neo4j_GridLabel
- neo4j_Project
- neo4j_Ensemble
- neo4j_ExperimentFamily
- neo4j_Forcing
- neo4j_Variable
- neo4j_RCM
- neo4j_Domain
- neo4j_SubExperiment
- neo4j_MIPEra
- neo4j_Frequency
- neo4j_Realm
- neo4j_Activity
- neo4j_Resolution
- neo4j_SourceType
- neo4j_Source
range: string

```
</details>