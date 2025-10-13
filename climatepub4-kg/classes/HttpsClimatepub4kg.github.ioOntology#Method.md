

# Class: HttpsClimatepub4kg.github.ioOntology#Method




This class occurs 38 times.


URI: [https://climatepub4kg.github.io/ontology#Method](https://climatepub4kg.github.io/ontology#Method)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#Method
    click HttpsClimatepub4kg.github.ioOntology#Method href "../HttpsClimatepub4kg.github.ioOntology#Method"
      HttpsClimatepub4kg.github.ioOntology#Method : https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Method --> "0..1" HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    click HttpsClimatepub4kg.github.ioOntology#ObservationalDataset href "../HttpsClimatepub4kg.github.ioOntology#ObservationalDataset"

        
      HttpsClimatepub4kg.github.ioOntology#Method : https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Method --> "0..1" HttpsClimatepub4kg.github.ioOntology#Innovation : https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION
    click HttpsClimatepub4kg.github.ioOntology#Innovation href "../HttpsClimatepub4kg.github.ioOntology#Innovation"

        
      HttpsClimatepub4kg.github.ioOntology#Method : https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Method --> "0..1" HttpsClimatepub4kg.github.ioOntology#Result : https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT
    click HttpsClimatepub4kg.github.ioOntology#Result href "../HttpsClimatepub4kg.github.ioOntology#Result"

        
      HttpsClimatepub4kg.github.ioOntology#Method : https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Method --> "0..1" HttpsClimatepub4kg.github.ioOntology#Problem : https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM
    click HttpsClimatepub4kg.github.ioOntology#Problem href "../HttpsClimatepub4kg.github.ioOntology#Problem"

        
      HttpsClimatepub4kg.github.ioOntology#Method : https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Method --> "0..1" HttpsClimatepub4kg.github.ioOntology#Metric : https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC
    click HttpsClimatepub4kg.github.ioOntology#Metric href "../HttpsClimatepub4kg.github.ioOntology#Metric"

        
      HttpsClimatepub4kg.github.ioOntology#Method : https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Method --> "0..1" HttpsClimatepub4kg.github.ioOntology#Model : https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL
    click HttpsClimatepub4kg.github.ioOntology#Model href "../HttpsClimatepub4kg.github.ioOntology#Model"

        
      HttpsClimatepub4kg.github.ioOntology#Method : https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Method --> "0..1" HttpsClimatepub4kg.github.ioOntology#Task : https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK
    click HttpsClimatepub4kg.github.ioOntology#Task href "../HttpsClimatepub4kg.github.ioOntology#Task"

        
      HttpsClimatepub4kg.github.ioOntology#Method : neo4j_name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Method --> "0..1" String : neo4j_name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Method : neo4j_paper_id
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Method --> "0..1" String : neo4j_paper_id
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Method : neo4j_uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Method --> "0..1" String : neo4j_uuid
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [neo4j_paper_id](../slots/neo4j_paper_id.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION](../slots/https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Innovation](../classes/HttpsClimatepub4kg.github.ioOntology#Innovation.md) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM](../slots/https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Problem](../classes/HttpsClimatepub4kg.github.ioOntology#Problem.md) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT](../slots/https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Result](../classes/HttpsClimatepub4kg.github.ioOntology#Result.md) |  <br/>  | direct | 669 |
| [https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK](../slots/https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Task](../classes/HttpsClimatepub4kg.github.ioOntology#Task.md) |  <br/>  | direct | 38 |
| [neo4j_name](../slots/neo4j_name.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](../slots/https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#ObservationalDataset](../classes/HttpsClimatepub4kg.github.ioOntology#ObservationalDataset.md) |  <br/>  | direct | 127 |
| [neo4j_uuid](../slots/neo4j_uuid.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC](../slots/https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Metric](../classes/HttpsClimatepub4kg.github.ioOntology#Metric.md) |  <br/>  | direct | 438 |
| [https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL](../slots/https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) |  <br/>  | direct | 38 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD](../slots/https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD.md) | range | [HttpsClimatepub4kg.github.ioOntology#Method](../classes/HttpsClimatepub4kg.github.ioOntology#Method.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Method
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- neo4j_paper_id
- https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION
- https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM
- https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT
- https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK
- neo4j_name
- https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
- neo4j_uuid
- https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC
- https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL
class_uri: https://climatepub4kg.github.io/ontology#Method

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Method
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  neo4j_paper_id:
    name: neo4j_paper_id
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:paper_id
    alias: neo4j_paper_id
    owner: https___climatepub4kg.github.io_ontology#Method
    domain_of:
    - https___climatepub4kg.github.io_ontology#Field
    - https___climatepub4kg.github.io_ontology#Innovation
    - https___climatepub4kg.github.io_ontology#Method
    - https___climatepub4kg.github.io_ontology#Model
    - https___climatepub4kg.github.io_ontology#Problem
    - https___climatepub4kg.github.io_ontology#Task
    range: string
  https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION:
    name: https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#METHOD_HAS_INNOVATION
    alias: https___climatepub4kg.github.io_ontology#METHOD_HAS_INNOVATION
    owner: https___climatepub4kg.github.io_ontology#Method
    domain_of:
    - https___climatepub4kg.github.io_ontology#Method
    range: https___climatepub4kg.github.io_ontology#Innovation
  https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM:
    name: https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#METHOD_SOLVES_PROBLEM
    alias: https___climatepub4kg.github.io_ontology#METHOD_SOLVES_PROBLEM
    owner: https___climatepub4kg.github.io_ontology#Method
    domain_of:
    - https___climatepub4kg.github.io_ontology#Method
    range: https___climatepub4kg.github.io_ontology#Problem
  https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT:
    name: https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#METHOD_HAS_RESULT
    alias: https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT
    owner: https___climatepub4kg.github.io_ontology#Method
    domain_of:
    - https___climatepub4kg.github.io_ontology#Method
    range: https___climatepub4kg.github.io_ontology#Result
  https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK:
    name: https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#METHOD_WORKS_ON_TASK
    alias: https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK
    owner: https___climatepub4kg.github.io_ontology#Method
    domain_of:
    - https___climatepub4kg.github.io_ontology#Method
    range: https___climatepub4kg.github.io_ontology#Task
  neo4j_name:
    name: neo4j_name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:name
    alias: neo4j_name
    owner: https___climatepub4kg.github.io_ontology#Method
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
  https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET:
    name: https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    alias: https___climatepub4kg.github.io_ontology#METHOD_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    owner: https___climatepub4kg.github.io_ontology#Method
    domain_of:
    - https___climatepub4kg.github.io_ontology#Method
    range: https___climatepub4kg.github.io_ontology#ObservationalDataset
  neo4j_uuid:
    name: neo4j_uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:uuid
    alias: neo4j_uuid
    owner: https___climatepub4kg.github.io_ontology#Method
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
  https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC:
    name: https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#METHOD_USES_METRIC
    alias: https___climatepub4kg.github.io_ontology#METHOD_USES_METRIC
    owner: https___climatepub4kg.github.io_ontology#Method
    domain_of:
    - https___climatepub4kg.github.io_ontology#Method
    range: https___climatepub4kg.github.io_ontology#Metric
  https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL:
    name: https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#METHOD_USES_MODEL
    alias: https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL
    owner: https___climatepub4kg.github.io_ontology#Method
    domain_of:
    - https___climatepub4kg.github.io_ontology#Method
    range: https___climatepub4kg.github.io_ontology#Model
class_uri: https://climatepub4kg.github.io/ontology#Method

```
</details>