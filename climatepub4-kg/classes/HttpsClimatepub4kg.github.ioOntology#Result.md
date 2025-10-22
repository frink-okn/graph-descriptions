

# Class: Result (https___climatepub4kg.github.io_ontology#Result)




This class occurs 607 times.


URI: [https://climatepub4kg.github.io/ontology#Result](https://climatepub4kg.github.io/ontology#Result)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#Result
    click HttpsClimatepub4kg.github.ioOntology#Result href "../HttpsClimatepub4kg.github.ioOntology#Result"
      HttpsClimatepub4kg.github.ioOntology#Result : https___climatepub4kg.github.io_ontology#name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Result --> "0..1" String : https___climatepub4kg.github.io_ontology#name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Result : https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Result --> "0..1" HttpsClimatepub4kg.github.ioOntology#Metric : https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC
    click HttpsClimatepub4kg.github.ioOntology#Metric href "../HttpsClimatepub4kg.github.ioOntology#Metric"

        
      HttpsClimatepub4kg.github.ioOntology#Result : https___climatepub4kg.github.io_ontology#uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Result --> "0..1" String : https___climatepub4kg.github.io_ontology#uuid
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC](../slots/https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Metric](../classes/HttpsClimatepub4kg.github.ioOntology#Metric.md) |  <br/>  | direct | 724 |
| [https___climatepub4kg.github.io_ontology#uuid](../slots/https___climatepub4kg.github.io_ontology#uuid.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 607 |
| [https___climatepub4kg.github.io_ontology#name](../slots/https___climatepub4kg.github.io_ontology#name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 607 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Method](../classes/HttpsClimatepub4kg.github.ioOntology#Method.md) | [https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT](../slots/https___climatepub4kg.github.io_ontology#METHOD_HAS_RESULT.md) | range | [HttpsClimatepub4kg.github.ioOntology#Result](../classes/HttpsClimatepub4kg.github.ioOntology#Result.md) |
| [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) | [https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT](../slots/https___climatepub4kg.github.io_ontology#MODEL_HAS_RESULT.md) | range | [HttpsClimatepub4kg.github.ioOntology#Result](../classes/HttpsClimatepub4kg.github.ioOntology#Result.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT](../slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT.md) | range | [HttpsClimatepub4kg.github.ioOntology#Result](../classes/HttpsClimatepub4kg.github.ioOntology#Result.md) |
| [HttpsClimatepub4kg.github.ioOntology#Result](../classes/HttpsClimatepub4kg.github.ioOntology#Result.md) | [https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC](../slots/https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Result](../classes/HttpsClimatepub4kg.github.ioOntology#Result.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Result
title: Result
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC
- https___climatepub4kg.github.io_ontology#uuid
- https___climatepub4kg.github.io_ontology#name
class_uri: https://climatepub4kg.github.io/ontology#Result

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Result
title: Result
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC:
    name: https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC
    title: RESULT_HAS_METRIC
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Result
    slot_uri: https://climatepub4kg.github.io/ontology#RESULT_HAS_METRIC
    alias: https___climatepub4kg.github.io_ontology#RESULT_HAS_METRIC
    owner: https___climatepub4kg.github.io_ontology#Result
    domain_of:
    - https___climatepub4kg.github.io_ontology#Result
    range: https___climatepub4kg.github.io_ontology#Metric
  https___climatepub4kg.github.io_ontology#uuid:
    name: https___climatepub4kg.github.io_ontology#uuid
    title: uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#uuid
    alias: https___climatepub4kg.github.io_ontology#uuid
    owner: https___climatepub4kg.github.io_ontology#Result
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
    - https___climatepub4kg.github.io_ontology#Member
    - https___climatepub4kg.github.io_ontology#ExperimentFamily
    - https___climatepub4kg.github.io_ontology#Problem
    - https___climatepub4kg.github.io_ontology#Domain
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#ObservationalDataset
    - https___climatepub4kg.github.io_ontology#Forcing
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#Result
    - https___climatepub4kg.github.io_ontology#Weather_Event
    - https___climatepub4kg.github.io_ontology#Model
    - https___climatepub4kg.github.io_ontology#Resolution
    - https___climatepub4kg.github.io_ontology#Task
    - https___climatepub4kg.github.io_ontology#Method
    - https___climatepub4kg.github.io_ontology#Variable
    - https___climatepub4kg.github.io_ontology#Natural_Hazard
    - https___climatepub4kg.github.io_ontology#Ocean_Circulation
    - https___climatepub4kg.github.io_ontology#PhysicalFeature
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Instrument
    - https___climatepub4kg.github.io_ontology#Teleconnection
    - https___climatepub4kg.github.io_ontology#Platform
    - https___climatepub4kg.github.io_ontology#MIPEra
    - https___climatepub4kg.github.io_ontology#Keyword
    - https___climatepub4kg.github.io_ontology#Metric
    - https___climatepub4kg.github.io_ontology#Realm
    - https___climatepub4kg.github.io_ontology#SourceComponent
    - https___climatepub4kg.github.io_ontology#SubExperiment
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#Frequency
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    - https___climatepub4kg.github.io_ontology#Project
    - https___climatepub4kg.github.io_ontology#Field
    - https___climatepub4kg.github.io_ontology#Paper
    - https___climatepub4kg.github.io_ontology#SourceType
    - https___climatepub4kg.github.io_ontology#GridLabel
    - https___climatepub4kg.github.io_ontology#Ensemble
    - https___climatepub4kg.github.io_ontology#Innovation
    - https___climatepub4kg.github.io_ontology#NaturalHazardType
    - https___climatepub4kg.github.io_ontology#No_Country_Region
    - https___climatepub4kg.github.io_ontology#PhysicalScheme
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#Institute
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#Continent
    - https___climatepub4kg.github.io_ontology#SimulationType
    range: string
  https___climatepub4kg.github.io_ontology#name:
    name: https___climatepub4kg.github.io_ontology#name
    title: name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#name
    alias: https___climatepub4kg.github.io_ontology#name
    owner: https___climatepub4kg.github.io_ontology#Result
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
    - https___climatepub4kg.github.io_ontology#Member
    - https___climatepub4kg.github.io_ontology#ExperimentFamily
    - https___climatepub4kg.github.io_ontology#Problem
    - https___climatepub4kg.github.io_ontology#Domain
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#ObservationalDataset
    - https___climatepub4kg.github.io_ontology#Forcing
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#Result
    - https___climatepub4kg.github.io_ontology#Weather_Event
    - https___climatepub4kg.github.io_ontology#Model
    - https___climatepub4kg.github.io_ontology#Resolution
    - https___climatepub4kg.github.io_ontology#Task
    - https___climatepub4kg.github.io_ontology#Method
    - https___climatepub4kg.github.io_ontology#Variable
    - https___climatepub4kg.github.io_ontology#Natural_Hazard
    - https___climatepub4kg.github.io_ontology#Ocean_Circulation
    - https___climatepub4kg.github.io_ontology#PhysicalFeature
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Instrument
    - https___climatepub4kg.github.io_ontology#Teleconnection
    - https___climatepub4kg.github.io_ontology#Platform
    - https___climatepub4kg.github.io_ontology#MIPEra
    - https___climatepub4kg.github.io_ontology#Keyword
    - https___climatepub4kg.github.io_ontology#Metric
    - https___climatepub4kg.github.io_ontology#Realm
    - https___climatepub4kg.github.io_ontology#SourceComponent
    - https___climatepub4kg.github.io_ontology#SubExperiment
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#Frequency
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    - https___climatepub4kg.github.io_ontology#Project
    - https___climatepub4kg.github.io_ontology#Field
    - https___climatepub4kg.github.io_ontology#Paper
    - https___climatepub4kg.github.io_ontology#SourceType
    - https___climatepub4kg.github.io_ontology#GridLabel
    - https___climatepub4kg.github.io_ontology#Ensemble
    - https___climatepub4kg.github.io_ontology#Innovation
    - https___climatepub4kg.github.io_ontology#NaturalHazardType
    - https___climatepub4kg.github.io_ontology#No_Country_Region
    - https___climatepub4kg.github.io_ontology#PhysicalScheme
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#Institute
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#Continent
    - https___climatepub4kg.github.io_ontology#SimulationType
    range: string
class_uri: https://climatepub4kg.github.io/ontology#Result

```
</details>