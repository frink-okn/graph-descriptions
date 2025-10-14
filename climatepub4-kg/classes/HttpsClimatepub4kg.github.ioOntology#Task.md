

# Class: HttpsClimatepub4kg.github.ioOntology#Task




This class occurs 38 times.


URI: [https://climatepub4kg.github.io/ontology#Task](https://climatepub4kg.github.io/ontology#Task)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#Task
    click HttpsClimatepub4kg.github.ioOntology#Task href "../HttpsClimatepub4kg.github.ioOntology#Task"
      HttpsClimatepub4kg.github.ioOntology#Task : https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Task --> "0..1" HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    click HttpsClimatepub4kg.github.ioOntology#ObservationalDataset href "../HttpsClimatepub4kg.github.ioOntology#ObservationalDataset"

        
      HttpsClimatepub4kg.github.ioOntology#Task : https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Task --> "0..1" HttpsClimatepub4kg.github.ioOntology#Problem : https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM
    click HttpsClimatepub4kg.github.ioOntology#Problem href "../HttpsClimatepub4kg.github.ioOntology#Problem"

        
      HttpsClimatepub4kg.github.ioOntology#Task : https___climatepub4kg.github.io_ontology#TASK_USES_METRIC
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Task --> "0..1" HttpsClimatepub4kg.github.ioOntology#Metric : https___climatepub4kg.github.io_ontology#TASK_USES_METRIC
    click HttpsClimatepub4kg.github.ioOntology#Metric href "../HttpsClimatepub4kg.github.ioOntology#Metric"

        
      HttpsClimatepub4kg.github.ioOntology#Task : neo4j_name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Task --> "0..1" String : neo4j_name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Task : neo4j_paper_id
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Task --> "0..1" String : neo4j_paper_id
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Task : neo4j_uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Task --> "0..1" String : neo4j_uuid
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM](../slots/https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Problem](../classes/HttpsClimatepub4kg.github.ioOntology#Problem.md) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#TASK_USES_METRIC](../slots/https___climatepub4kg.github.io_ontology#TASK_USES_METRIC.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Metric](../classes/HttpsClimatepub4kg.github.ioOntology#Metric.md) |  <br/>  | direct | 438 |
| [neo4j_name](../slots/neo4j_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](../slots/https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#ObservationalDataset](../classes/HttpsClimatepub4kg.github.ioOntology#ObservationalDataset.md) |  <br/>  | direct | 127 |
| [neo4j_uuid](../slots/neo4j_uuid.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 38 |
| [neo4j_paper_id](../slots/neo4j_paper_id.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 38 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Method](../classes/HttpsClimatepub4kg.github.ioOntology#Method.md) | [https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK](../slots/https___climatepub4kg.github.io_ontology#METHOD_WORKS_ON_TASK.md) | range | [HttpsClimatepub4kg.github.ioOntology#Task](../classes/HttpsClimatepub4kg.github.ioOntology#Task.md) |
| [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) | [https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK](../slots/https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK.md) | range | [HttpsClimatepub4kg.github.ioOntology#Task](../classes/HttpsClimatepub4kg.github.ioOntology#Task.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK](../slots/https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK.md) | range | [HttpsClimatepub4kg.github.ioOntology#Task](../classes/HttpsClimatepub4kg.github.ioOntology#Task.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Task
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM
- https___climatepub4kg.github.io_ontology#TASK_USES_METRIC
- neo4j_name
- https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
- neo4j_uuid
- neo4j_paper_id
class_uri: https://climatepub4kg.github.io/ontology#Task

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Task
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM:
    name: https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#TASK_FACES_PROBLEM
    alias: https___climatepub4kg.github.io_ontology#TASK_FACES_PROBLEM
    owner: https___climatepub4kg.github.io_ontology#Task
    domain_of:
    - https___climatepub4kg.github.io_ontology#Task
    range: https___climatepub4kg.github.io_ontology#Problem
  https___climatepub4kg.github.io_ontology#TASK_USES_METRIC:
    name: https___climatepub4kg.github.io_ontology#TASK_USES_METRIC
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#TASK_USES_METRIC
    alias: https___climatepub4kg.github.io_ontology#TASK_USES_METRIC
    owner: https___climatepub4kg.github.io_ontology#Task
    domain_of:
    - https___climatepub4kg.github.io_ontology#Task
    range: https___climatepub4kg.github.io_ontology#Metric
  neo4j_name:
    name: neo4j_name
    title: name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:name
    alias: neo4j_name
    owner: https___climatepub4kg.github.io_ontology#Task
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
    union_of:
    - neo4j_Forcing
    - neo4j_Variable
    - neo4j_Keyword
    - neo4j_RCM
    - neo4j_Ocean_Circulation
    - neo4j_Country
    - neo4j_Source
    - neo4j_SourceType
    - neo4j_PhysicalScheme
    - neo4j_No_Country_Region
    - neo4j_Paper
    - neo4j_Realm
    - neo4j_MIPEra
    - neo4j_Domain
    - neo4j_Teleconnection
    - neo4j_SubExperiment
    - neo4j_Resolution
    - neo4j_Activity
    - neo4j_Result
    - neo4j_Task
    - neo4j_Problem
    - neo4j_ExperimentFamily
    - neo4j_Method
    - neo4j_Metric
    - neo4j_SourceComponent
    - neo4j_Innovation
    - neo4j_Ensemble
    - neo4j_Platform
    - neo4j_ObservationalDataset
    - neo4j_Frequency
    - neo4j_GridLabel
    - neo4j_Member
    - neo4j_SimulationType
    - neo4j_Continent
    - neo4j_Weather_Event
    - neo4j_Model
    - neo4j_Natural_Hazard
    - neo4j_City
    - neo4j_Instrument
    - neo4j_PhysicalFeature
    - neo4j_Field
    - neo4j_Water_Bodies
    - neo4j_Experiment
    - neo4j_Country_Subdivision
    - neo4j_Institute
    - neo4j_NaturalHazardType
    - neo4j_Project
    range: string
  https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET:
    name: https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    alias: https___climatepub4kg.github.io_ontology#TASK_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    owner: https___climatepub4kg.github.io_ontology#Task
    domain_of:
    - https___climatepub4kg.github.io_ontology#Task
    range: https___climatepub4kg.github.io_ontology#ObservationalDataset
  neo4j_uuid:
    name: neo4j_uuid
    title: uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:uuid
    alias: neo4j_uuid
    owner: https___climatepub4kg.github.io_ontology#Task
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
    union_of:
    - neo4j_Forcing
    - neo4j_Variable
    - neo4j_Keyword
    - neo4j_RCM
    - neo4j_Ocean_Circulation
    - neo4j_Country
    - neo4j_Source
    - neo4j_SourceType
    - neo4j_PhysicalScheme
    - neo4j_No_Country_Region
    - neo4j_Paper
    - neo4j_Realm
    - neo4j_MIPEra
    - neo4j_Domain
    - neo4j_Teleconnection
    - neo4j_SubExperiment
    - neo4j_Resolution
    - neo4j_Activity
    - neo4j_Result
    - neo4j_Task
    - neo4j_Problem
    - neo4j_ExperimentFamily
    - neo4j_Method
    - neo4j_Metric
    - neo4j_SourceComponent
    - neo4j_Innovation
    - neo4j_Ensemble
    - neo4j_Platform
    - neo4j_ObservationalDataset
    - neo4j_Frequency
    - neo4j_GridLabel
    - neo4j_Member
    - neo4j_SimulationType
    - neo4j_Continent
    - neo4j_Weather_Event
    - neo4j_Model
    - neo4j_Natural_Hazard
    - neo4j_City
    - neo4j_Instrument
    - neo4j_PhysicalFeature
    - neo4j_Field
    - neo4j_Water_Bodies
    - neo4j_Experiment
    - neo4j_Country_Subdivision
    - neo4j_Institute
    - neo4j_NaturalHazardType
    - neo4j_Project
    range: string
  neo4j_paper_id:
    name: neo4j_paper_id
    title: paper_id
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:paper_id
    alias: neo4j_paper_id
    owner: https___climatepub4kg.github.io_ontology#Task
    domain_of:
    - https___climatepub4kg.github.io_ontology#Field
    - https___climatepub4kg.github.io_ontology#Innovation
    - https___climatepub4kg.github.io_ontology#Method
    - https___climatepub4kg.github.io_ontology#Model
    - https___climatepub4kg.github.io_ontology#Problem
    - https___climatepub4kg.github.io_ontology#Task
    union_of:
    - neo4j_Innovation
    - neo4j_Model
    - neo4j_Field
    - neo4j_Task
    - neo4j_Problem
    - neo4j_Method
    range: string
class_uri: https://climatepub4kg.github.io/ontology#Task

```
</details>