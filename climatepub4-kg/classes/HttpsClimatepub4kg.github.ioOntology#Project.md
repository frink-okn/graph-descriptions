

# Class: HttpsClimatepub4kg.github.ioOntology#Project




This class occurs 33 times.


URI: [https://climatepub4kg.github.io/ontology#Project](https://climatepub4kg.github.io/ontology#Project)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#Project
    click HttpsClimatepub4kg.github.ioOntology#Project href "../HttpsClimatepub4kg.github.ioOntology#Project"
      HttpsClimatepub4kg.github.ioOntology#Project : https___climatepub4kg.github.io_ontology#COVERS_DOMAIN
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Project --> "0..1" HttpsClimatepub4kg.github.ioOntology#Domain : https___climatepub4kg.github.io_ontology#COVERS_DOMAIN
    click HttpsClimatepub4kg.github.ioOntology#Domain href "../HttpsClimatepub4kg.github.ioOntology#Domain"

        
      HttpsClimatepub4kg.github.ioOntology#Project : neo4j_name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Project --> "0..1" String : neo4j_name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Project : neo4j_names
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Project --> "0..1" String : neo4j_names
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Project : neo4j_uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Project --> "0..1" String : neo4j_uuid
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [neo4j_uuid](../slots/neo4j_uuid.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 33 |
| [neo4j_name](../slots/neo4j_name.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 33 |
| [https___climatepub4kg.github.io_ontology#COVERS_DOMAIN](../slots/https___climatepub4kg.github.io_ontology#COVERS_DOMAIN.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Domain](../classes/HttpsClimatepub4kg.github.ioOntology#Domain.md) |  <br/>  | direct | 42 |
| [neo4j_names](../slots/neo4j_names.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 33 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Activity](../classes/HttpsClimatepub4kg.github.ioOntology#Activity.md) | [https___climatepub4kg.github.io_ontology#PART_OF_PROJECT](../slots/https___climatepub4kg.github.io_ontology#PART_OF_PROJECT.md) | range | [HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |
| [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) | [https___climatepub4kg.github.io_ontology#PART_OF_PROJECT](../slots/https___climatepub4kg.github.io_ontology#PART_OF_PROJECT.md) | range | [HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |
| [HttpsClimatepub4kg.github.ioOntology#Institute](../classes/HttpsClimatepub4kg.github.ioOntology#Institute.md) | [https___climatepub4kg.github.io_ontology#PARTICIPATED_IN](../slots/https___climatepub4kg.github.io_ontology#PARTICIPATED_IN.md) | range | [HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_MENTIONS](../slots/https___climatepub4kg.github.io_ontology#PAPER_MENTIONS.md) | any_of[range] | [HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |
| [HttpsClimatepub4kg.github.ioOntology#RCM](../classes/HttpsClimatepub4kg.github.ioOntology#RCM.md) | [https___climatepub4kg.github.io_ontology#PART_OF_PROJECT](../slots/https___climatepub4kg.github.io_ontology#PART_OF_PROJECT.md) | range | [HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#PART_OF_PROJECT](../slots/https___climatepub4kg.github.io_ontology#PART_OF_PROJECT.md) | range | [HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Project
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- neo4j_uuid
- neo4j_name
- https___climatepub4kg.github.io_ontology#COVERS_DOMAIN
- neo4j_names
class_uri: https://climatepub4kg.github.io/ontology#Project

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Project
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  neo4j_uuid:
    name: neo4j_uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:uuid
    alias: neo4j_uuid
    owner: https___climatepub4kg.github.io_ontology#Project
    domain_of:
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#Continent
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Domain
    - https___climatepub4kg.github.io_ontology#Ensemble
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#ExperimentFamily
    - https___climatepub4kg.github.io_ontology#Field
    - https___climatepub4kg.github.io_ontology#Forcing
    - https___climatepub4kg.github.io_ontology#Frequency
    - https___climatepub4kg.github.io_ontology#Innovation
    - https___climatepub4kg.github.io_ontology#Institute
    - https___climatepub4kg.github.io_ontology#Instrument
    - https___climatepub4kg.github.io_ontology#Keyword
    - https___climatepub4kg.github.io_ontology#MIPEra
    - https___climatepub4kg.github.io_ontology#Member
    - https___climatepub4kg.github.io_ontology#Method
    - https___climatepub4kg.github.io_ontology#Metric
    - https___climatepub4kg.github.io_ontology#Model
    - https___climatepub4kg.github.io_ontology#Natural_Hazard
    - https___climatepub4kg.github.io_ontology#No_Country_Region
    - https___climatepub4kg.github.io_ontology#ObservationalDataset
    - https___climatepub4kg.github.io_ontology#Ocean_Circulation
    - https___climatepub4kg.github.io_ontology#Paper
    - https___climatepub4kg.github.io_ontology#PhysicalFeature
    - https___climatepub4kg.github.io_ontology#PhysicalScheme
    - https___climatepub4kg.github.io_ontology#Platform
    - https___climatepub4kg.github.io_ontology#Problem
    - https___climatepub4kg.github.io_ontology#Project
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Realm
    - https___climatepub4kg.github.io_ontology#Resolution
    - https___climatepub4kg.github.io_ontology#Result
    - https___climatepub4kg.github.io_ontology#SimulationType
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    - https___climatepub4kg.github.io_ontology#SourceType
    - https___climatepub4kg.github.io_ontology#SubExperiment
    - https___climatepub4kg.github.io_ontology#Task
    - https___climatepub4kg.github.io_ontology#Teleconnection
    - https___climatepub4kg.github.io_ontology#Variable
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    - https___climatepub4kg.github.io_ontology#Weather_Event
    range: string
  neo4j_name:
    name: neo4j_name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:name
    alias: neo4j_name
    owner: https___climatepub4kg.github.io_ontology#Project
    domain_of:
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#Continent
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Domain
    - https___climatepub4kg.github.io_ontology#Ensemble
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#ExperimentFamily
    - https___climatepub4kg.github.io_ontology#Field
    - https___climatepub4kg.github.io_ontology#Forcing
    - https___climatepub4kg.github.io_ontology#Frequency
    - https___climatepub4kg.github.io_ontology#Innovation
    - https___climatepub4kg.github.io_ontology#Institute
    - https___climatepub4kg.github.io_ontology#Instrument
    - https___climatepub4kg.github.io_ontology#Keyword
    - https___climatepub4kg.github.io_ontology#MIPEra
    - https___climatepub4kg.github.io_ontology#Member
    - https___climatepub4kg.github.io_ontology#Method
    - https___climatepub4kg.github.io_ontology#Metric
    - https___climatepub4kg.github.io_ontology#Model
    - https___climatepub4kg.github.io_ontology#Natural_Hazard
    - https___climatepub4kg.github.io_ontology#No_Country_Region
    - https___climatepub4kg.github.io_ontology#ObservationalDataset
    - https___climatepub4kg.github.io_ontology#Ocean_Circulation
    - https___climatepub4kg.github.io_ontology#Paper
    - https___climatepub4kg.github.io_ontology#PhysicalFeature
    - https___climatepub4kg.github.io_ontology#PhysicalScheme
    - https___climatepub4kg.github.io_ontology#Platform
    - https___climatepub4kg.github.io_ontology#Problem
    - https___climatepub4kg.github.io_ontology#Project
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Realm
    - https___climatepub4kg.github.io_ontology#Resolution
    - https___climatepub4kg.github.io_ontology#Result
    - https___climatepub4kg.github.io_ontology#SimulationType
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    - https___climatepub4kg.github.io_ontology#SourceType
    - https___climatepub4kg.github.io_ontology#SubExperiment
    - https___climatepub4kg.github.io_ontology#Task
    - https___climatepub4kg.github.io_ontology#Teleconnection
    - https___climatepub4kg.github.io_ontology#Variable
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    - https___climatepub4kg.github.io_ontology#Weather_Event
    range: string
  https___climatepub4kg.github.io_ontology#COVERS_DOMAIN:
    name: https___climatepub4kg.github.io_ontology#COVERS_DOMAIN
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#COVERS_DOMAIN
    alias: https___climatepub4kg.github.io_ontology#COVERS_DOMAIN
    owner: https___climatepub4kg.github.io_ontology#Project
    domain_of:
    - https___climatepub4kg.github.io_ontology#Project
    - https___climatepub4kg.github.io_ontology#RCM
    range: https___climatepub4kg.github.io_ontology#Domain
  neo4j_names:
    name: neo4j_names
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:names
    alias: neo4j_names
    owner: https___climatepub4kg.github.io_ontology#Project
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
    range: string
class_uri: https://climatepub4kg.github.io/ontology#Project

```
</details>