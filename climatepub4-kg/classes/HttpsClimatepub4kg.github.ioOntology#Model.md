

# Class: Model (https___climatepub4kg.github.io_ontology#Model)




This class occurs 37 times.


URI: [https://climatepub4kg.github.io/ontology#Model](https://climatepub4kg.github.io/ontology#Model)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#Model
    click HttpsClimatepub4kg.github.ioOntology#Model href "../HttpsClimatepub4kg.github.ioOntology#Model"
      HttpsClimatepub4kg.github.ioOntology#Model : https___climatepub4kg.github.io_ontology#CORRESPONDS_TO
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Model --> "0..1" HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#CORRESPONDS_TO
    click HttpsClimatepub4kg.github.ioOntology#Source href "../HttpsClimatepub4kg.github.ioOntology#Source"

        
      HttpsClimatepub4kg.github.ioOntology#Model : https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Model --> "0..1" HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    click HttpsClimatepub4kg.github.ioOntology#ObservationalDataset href "../HttpsClimatepub4kg.github.ioOntology#ObservationalDataset"

        
      HttpsClimatepub4kg.github.ioOntology#Model : https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Model --> "0..1" HttpsClimatepub4kg.github.ioOntology#Result : https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT
    click HttpsClimatepub4kg.github.ioOntology#Result href "../HttpsClimatepub4kg.github.ioOntology#Result"

        
      HttpsClimatepub4kg.github.ioOntology#Model : https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Model --> "0..1" HttpsClimatepub4kg.github.ioOntology#Problem : https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM
    click HttpsClimatepub4kg.github.ioOntology#Problem href "../HttpsClimatepub4kg.github.ioOntology#Problem"

        
      HttpsClimatepub4kg.github.ioOntology#Model : https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Model --> "0..1" HttpsClimatepub4kg.github.ioOntology#Metric : https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC
    click HttpsClimatepub4kg.github.ioOntology#Metric href "../HttpsClimatepub4kg.github.ioOntology#Metric"

        
      HttpsClimatepub4kg.github.ioOntology#Model : https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Model --> "0..1" HttpsClimatepub4kg.github.ioOntology#Task : https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK
    click HttpsClimatepub4kg.github.ioOntology#Task href "../HttpsClimatepub4kg.github.ioOntology#Task"

        
      HttpsClimatepub4kg.github.ioOntology#Model : https___climatepub4kg.github.io_ontology#name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Model --> "0..1" String : https___climatepub4kg.github.io_ontology#name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Model : https___climatepub4kg.github.io_ontology#paper_id
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Model --> "0..1" String : https___climatepub4kg.github.io_ontology#paper_id
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Model : https___climatepub4kg.github.io_ontology#uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Model --> "0..1" String : https___climatepub4kg.github.io_ontology#uuid
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](../slots/https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#ObservationalDataset](../classes/HttpsClimatepub4kg.github.ioOntology#ObservationalDataset.md) |  <br/>  | direct | 127 |
| [https___climatepub4kg.github.io_ontology#uuid](../slots/https___climatepub4kg.github.io_ontology#uuid.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 37 |
| [https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM](../slots/https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Problem](../classes/HttpsClimatepub4kg.github.ioOntology#Problem.md) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT](../slots/https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Result](../classes/HttpsClimatepub4kg.github.ioOntology#Result.md) |  <br/>  | direct | 669 |
| [https___climatepub4kg.github.io_ontology#paper_id](../slots/https___climatepub4kg.github.io_ontology#paper_id.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 37 |
| [https___climatepub4kg.github.io_ontology#name](../slots/https___climatepub4kg.github.io_ontology#name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 37 |
| [https___climatepub4kg.github.io_ontology#CORRESPONDS_TO](../slots/https___climatepub4kg.github.io_ontology#CORRESPONDS_TO.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |  <br/>  | direct | 15 |
| [https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC](../slots/https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Metric](../classes/HttpsClimatepub4kg.github.ioOntology#Metric.md) |  <br/>  | direct | 438 |
| [https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK](../slots/https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Task](../classes/HttpsClimatepub4kg.github.ioOntology#Task.md) |  <br/>  | direct | 38 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Method](../classes/HttpsClimatepub4kg.github.ioOntology#Method.md) | [https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL](../slots/https___climatepub4kg.github.io_ontology#METHOD_USES_MODEL.md) | range | [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) |
| [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) | [https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](../slots/https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) |
| [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) | [https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM](../slots/https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) |
| [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) | [https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT](../slots/https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) |
| [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) | [https___climatepub4kg.github.io_ontology#CORRESPONDS_TO](../slots/https___climatepub4kg.github.io_ontology#CORRESPONDS_TO.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) |
| [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) | [https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC](../slots/https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) |
| [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) | [https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK](../slots/https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL](../slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL.md) | range | [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Model
title: Model
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
- https___climatepub4kg.github.io_ontology#uuid
- https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM
- https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT
- https___climatepub4kg.github.io_ontology#paper_id
- https___climatepub4kg.github.io_ontology#name
- https___climatepub4kg.github.io_ontology#CORRESPONDS_TO
- https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC
- https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK
class_uri: https://climatepub4kg.github.io/ontology#Model

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Model
title: Model
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET:
    name: https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    title: MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Model
    slot_uri: https://climatepub4kg.github.io/ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    alias: https___climatepub4kg.github.io_ontology#MODEL_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    owner: https___climatepub4kg.github.io_ontology#Model
    domain_of:
    - https___climatepub4kg.github.io_ontology#Model
    range: https___climatepub4kg.github.io_ontology#ObservationalDataset
  https___climatepub4kg.github.io_ontology#uuid:
    name: https___climatepub4kg.github.io_ontology#uuid
    title: uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#uuid
    alias: https___climatepub4kg.github.io_ontology#uuid
    owner: https___climatepub4kg.github.io_ontology#Model
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
    - https___climatepub4kg.github.io_ontology#Platform
    - https___climatepub4kg.github.io_ontology#Realm
    - https___climatepub4kg.github.io_ontology#Task
    - https___climatepub4kg.github.io_ontology#Domain
    - https___climatepub4kg.github.io_ontology#No_Country_Region
    - https___climatepub4kg.github.io_ontology#Ocean_Circulation
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    - https___climatepub4kg.github.io_ontology#Ensemble
    - https___climatepub4kg.github.io_ontology#Model
    - https___climatepub4kg.github.io_ontology#SourceComponent
    - https___climatepub4kg.github.io_ontology#SimulationType
    - https___climatepub4kg.github.io_ontology#Natural_Hazard
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#Metric
    - https___climatepub4kg.github.io_ontology#Problem
    - https___climatepub4kg.github.io_ontology#Weather_Event
    - https___climatepub4kg.github.io_ontology#Member
    - https___climatepub4kg.github.io_ontology#Result
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#PhysicalFeature
    - https___climatepub4kg.github.io_ontology#ObservationalDataset
    - https___climatepub4kg.github.io_ontology#NaturalHazardType
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#Innovation
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#Variable
    - https___climatepub4kg.github.io_ontology#Continent
    - https___climatepub4kg.github.io_ontology#Teleconnection
    - https___climatepub4kg.github.io_ontology#ExperimentFamily
    - https___climatepub4kg.github.io_ontology#SourceType
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Field
    - https___climatepub4kg.github.io_ontology#Method
    - https___climatepub4kg.github.io_ontology#GridLabel
    - https___climatepub4kg.github.io_ontology#SubExperiment
    - https___climatepub4kg.github.io_ontology#Instrument
    - https___climatepub4kg.github.io_ontology#Institute
    - https___climatepub4kg.github.io_ontology#Forcing
    - https___climatepub4kg.github.io_ontology#Paper
    - https___climatepub4kg.github.io_ontology#Resolution
    - https___climatepub4kg.github.io_ontology#MIPEra
    - https___climatepub4kg.github.io_ontology#PhysicalScheme
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Frequency
    - https___climatepub4kg.github.io_ontology#Keyword
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#Project
    range: string
  https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM:
    name: https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM
    title: MODEL_SOLVES_PROBLEM
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Model
    slot_uri: https://climatepub4kg.github.io/ontology#MODEL_SOLVES_PROBLEM
    alias: https___climatepub4kg.github.io_ontology#MODEL_SOLVES_PROBLEM
    owner: https___climatepub4kg.github.io_ontology#Model
    domain_of:
    - https___climatepub4kg.github.io_ontology#Model
    range: https___climatepub4kg.github.io_ontology#Problem
  https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT:
    name: https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT
    title: MODEL_HAS_RESULT
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Model
    slot_uri: https://climatepub4kg.github.io/ontology#MODEL_HAS_RESULT
    alias: https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT
    owner: https___climatepub4kg.github.io_ontology#Model
    domain_of:
    - https___climatepub4kg.github.io_ontology#Model
    range: https___climatepub4kg.github.io_ontology#Result
  https___climatepub4kg.github.io_ontology#paper_id:
    name: https___climatepub4kg.github.io_ontology#paper_id
    title: paper_id
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#paper_id
    alias: https___climatepub4kg.github.io_ontology#paper_id
    owner: https___climatepub4kg.github.io_ontology#Model
    domain_of:
    - https___climatepub4kg.github.io_ontology#Field
    - https___climatepub4kg.github.io_ontology#Innovation
    - https___climatepub4kg.github.io_ontology#Method
    - https___climatepub4kg.github.io_ontology#Model
    - https___climatepub4kg.github.io_ontology#Problem
    - https___climatepub4kg.github.io_ontology#Task
    union_of:
    - https___climatepub4kg.github.io_ontology#Innovation
    - https___climatepub4kg.github.io_ontology#Problem
    - https___climatepub4kg.github.io_ontology#Task
    - https___climatepub4kg.github.io_ontology#Field
    - https___climatepub4kg.github.io_ontology#Method
    - https___climatepub4kg.github.io_ontology#Model
    range: string
  https___climatepub4kg.github.io_ontology#name:
    name: https___climatepub4kg.github.io_ontology#name
    title: name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#name
    alias: https___climatepub4kg.github.io_ontology#name
    owner: https___climatepub4kg.github.io_ontology#Model
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
    - https___climatepub4kg.github.io_ontology#Platform
    - https___climatepub4kg.github.io_ontology#Realm
    - https___climatepub4kg.github.io_ontology#Task
    - https___climatepub4kg.github.io_ontology#Domain
    - https___climatepub4kg.github.io_ontology#No_Country_Region
    - https___climatepub4kg.github.io_ontology#Ocean_Circulation
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    - https___climatepub4kg.github.io_ontology#Ensemble
    - https___climatepub4kg.github.io_ontology#Model
    - https___climatepub4kg.github.io_ontology#SourceComponent
    - https___climatepub4kg.github.io_ontology#SimulationType
    - https___climatepub4kg.github.io_ontology#Natural_Hazard
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#Metric
    - https___climatepub4kg.github.io_ontology#Problem
    - https___climatepub4kg.github.io_ontology#Weather_Event
    - https___climatepub4kg.github.io_ontology#Member
    - https___climatepub4kg.github.io_ontology#Result
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#PhysicalFeature
    - https___climatepub4kg.github.io_ontology#ObservationalDataset
    - https___climatepub4kg.github.io_ontology#NaturalHazardType
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#Innovation
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#Variable
    - https___climatepub4kg.github.io_ontology#Continent
    - https___climatepub4kg.github.io_ontology#Teleconnection
    - https___climatepub4kg.github.io_ontology#ExperimentFamily
    - https___climatepub4kg.github.io_ontology#SourceType
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Field
    - https___climatepub4kg.github.io_ontology#Method
    - https___climatepub4kg.github.io_ontology#GridLabel
    - https___climatepub4kg.github.io_ontology#SubExperiment
    - https___climatepub4kg.github.io_ontology#Instrument
    - https___climatepub4kg.github.io_ontology#Institute
    - https___climatepub4kg.github.io_ontology#Forcing
    - https___climatepub4kg.github.io_ontology#Paper
    - https___climatepub4kg.github.io_ontology#Resolution
    - https___climatepub4kg.github.io_ontology#MIPEra
    - https___climatepub4kg.github.io_ontology#PhysicalScheme
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Frequency
    - https___climatepub4kg.github.io_ontology#Keyword
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#Project
    range: string
  https___climatepub4kg.github.io_ontology#CORRESPONDS_TO:
    name: https___climatepub4kg.github.io_ontology#CORRESPONDS_TO
    title: CORRESPONDS_TO
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Model
    slot_uri: https://climatepub4kg.github.io/ontology#CORRESPONDS_TO
    alias: https___climatepub4kg.github.io_ontology#CORRESPONDS_TO
    owner: https___climatepub4kg.github.io_ontology#Model
    domain_of:
    - https___climatepub4kg.github.io_ontology#Model
    range: https___climatepub4kg.github.io_ontology#Source
  https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC:
    name: https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC
    title: MODEL_USES_METRIC
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Model
    slot_uri: https://climatepub4kg.github.io/ontology#MODEL_USES_METRIC
    alias: https___climatepub4kg.github.io_ontology#MODEL_USES_METRIC
    owner: https___climatepub4kg.github.io_ontology#Model
    domain_of:
    - https___climatepub4kg.github.io_ontology#Model
    range: https___climatepub4kg.github.io_ontology#Metric
  https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK:
    name: https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK
    title: MODEL_WORKS_FOR_TASK
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Model
    slot_uri: https://climatepub4kg.github.io/ontology#MODEL_WORKS_FOR_TASK
    alias: https___climatepub4kg.github.io_ontology#MODEL_WORKS_FOR_TASK
    owner: https___climatepub4kg.github.io_ontology#Model
    domain_of:
    - https___climatepub4kg.github.io_ontology#Model
    range: https___climatepub4kg.github.io_ontology#Task
class_uri: https://climatepub4kg.github.io/ontology#Model

```
</details>