

# Class: Experiment (https___climatepub4kg.github.io_ontology#Experiment)




This class occurs 481 times.


URI: [https://climatepub4kg.github.io/ontology#Experiment](https://climatepub4kg.github.io/ontology#Experiment)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#Experiment
    click HttpsClimatepub4kg.github.ioOntology#Experiment href "../HttpsClimatepub4kg.github.ioOntology#Experiment"
      HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Experiment --> "0..1" HttpsClimatepub4kg.github.ioOntology#Realm : https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM
    click HttpsClimatepub4kg.github.ioOntology#Realm href "../HttpsClimatepub4kg.github.ioOntology#Realm"

        
      HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#experiment_title
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Experiment --> "0..1" String : https___climatepub4kg.github.io_ontology#experiment_title
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Experiment --> "0..1" HttpsClimatepub4kg.github.ioOntology#Resolution : https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION
    click HttpsClimatepub4kg.github.ioOntology#Resolution href "../HttpsClimatepub4kg.github.ioOntology#Resolution"

        
      HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Experiment --> "0..1" HttpsClimatepub4kg.github.ioOntology#SubExperiment : https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT
    click HttpsClimatepub4kg.github.ioOntology#SubExperiment href "../HttpsClimatepub4kg.github.ioOntology#SubExperiment"

        
      HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Experiment --> "0..1" HttpsClimatepub4kg.github.ioOntology#Ensemble : https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER
    click HttpsClimatepub4kg.github.ioOntology#Ensemble href "../HttpsClimatepub4kg.github.ioOntology#Ensemble"

        
      HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Experiment --> "0..1" String : https___climatepub4kg.github.io_ontology#name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#names
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Experiment --> "0..1" String : https___climatepub4kg.github.io_ontology#names
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Experiment --> "0..1" HttpsClimatepub4kg.github.ioOntology#Project : https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
    click HttpsClimatepub4kg.github.ioOntology#Project href "../HttpsClimatepub4kg.github.ioOntology#Project"

        
      HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Experiment --> "0..1" HttpsClimatepub4kg.github.ioOntology#Institute : https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE
    click HttpsClimatepub4kg.github.ioOntology#Institute href "../HttpsClimatepub4kg.github.ioOntology#Institute"

        
      HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#USES_FORCING
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Experiment --> "0..1" HttpsClimatepub4kg.github.ioOntology#Forcing : https___climatepub4kg.github.io_ontology#USES_FORCING
    click HttpsClimatepub4kg.github.ioOntology#Forcing href "../HttpsClimatepub4kg.github.ioOntology#Forcing"

        
      HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Experiment --> "0..1" String : https___climatepub4kg.github.io_ontology#uuid
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION](../slots/https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Resolution](../classes/HttpsClimatepub4kg.github.ioOntology#Resolution.md) |  <br/>  | direct | 856 |
| [https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT](../slots/https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#SubExperiment](../classes/HttpsClimatepub4kg.github.ioOntology#SubExperiment.md) |  <br/>  | direct | 72 |
| [https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM](../slots/https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Realm](../classes/HttpsClimatepub4kg.github.ioOntology#Realm.md) |  <br/>  | direct | 2635 |
| [https___climatepub4kg.github.io_ontology#name](../slots/https___climatepub4kg.github.io_ontology#name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 481 |
| [https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER](../slots/https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Ensemble](../classes/HttpsClimatepub4kg.github.ioOntology#Ensemble.md) |  <br/>  | direct | 3069 |
| [https___climatepub4kg.github.io_ontology#USES_FORCING](../slots/https___climatepub4kg.github.io_ontology#USES_FORCING.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Forcing](../classes/HttpsClimatepub4kg.github.ioOntology#Forcing.md) |  <br/>  | direct | 986 |
| [https___climatepub4kg.github.io_ontology#experiment_title](../slots/https___climatepub4kg.github.io_ontology#experiment_title.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 261 |
| [https___climatepub4kg.github.io_ontology#names](../slots/https___climatepub4kg.github.io_ontology#names.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 481 |
| [https___climatepub4kg.github.io_ontology#PART_OF_PROJECT](../slots/https___climatepub4kg.github.io_ontology#PART_OF_PROJECT.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |  <br/>  | direct | 544 |
| [https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE](../slots/https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Institute](../classes/HttpsClimatepub4kg.github.ioOntology#Institute.md) |  <br/>  | direct | 2762 |
| [https___climatepub4kg.github.io_ontology#uuid](../slots/https___climatepub4kg.github.io_ontology#uuid.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 481 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) | [https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT](../slots/https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |
| [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) | [https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER](../slots/https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |
| [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) | [https___climatepub4kg.github.io_ontology#USES_FORCING](../slots/https___climatepub4kg.github.io_ontology#USES_FORCING.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |
| [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) | [https___climatepub4kg.github.io_ontology#experiment_title](../slots/https___climatepub4kg.github.io_ontology#experiment_title.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |
| [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) | [https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE](../slots/https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |
| [HttpsClimatepub4kg.github.ioOntology#ExperimentFamily](../classes/HttpsClimatepub4kg.github.ioOntology#ExperimentFamily.md) | [https___climatepub4kg.github.io_ontology#INCLUDES_EXPERIMENT](../slots/https___climatepub4kg.github.io_ontology#INCLUDES_EXPERIMENT.md) | range | [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_MENTIONS](../slots/https___climatepub4kg.github.io_ontology#PAPER_MENTIONS.md) | any_of[range] | [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |
| [HttpsClimatepub4kg.github.ioOntology#RCM](../classes/HttpsClimatepub4kg.github.ioOntology#RCM.md) | [https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT](../slots/https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT.md) | range | [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT](../slots/https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT.md) | range | [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Experiment
title: Experiment
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION
- https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT
- https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM
- https___climatepub4kg.github.io_ontology#name
- https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER
- https___climatepub4kg.github.io_ontology#USES_FORCING
- https___climatepub4kg.github.io_ontology#experiment_title
- https___climatepub4kg.github.io_ontology#names
- https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
- https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE
- https___climatepub4kg.github.io_ontology#uuid
class_uri: https://climatepub4kg.github.io/ontology#Experiment

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Experiment
title: Experiment
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION:
    name: https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION
    title: HAS_SPATIAL_RESOLUTION
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#HAS_SPATIAL_RESOLUTION
    alias: https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION
    owner: https___climatepub4kg.github.io_ontology#Experiment
    domain_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#Variable
    union_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#Variable
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Resolution
  https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT:
    name: https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT
    title: HAS_SUB_EXPERIMENT
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Experiment
    slot_uri: https://climatepub4kg.github.io/ontology#HAS_SUB_EXPERIMENT
    alias: https___climatepub4kg.github.io_ontology#HAS_SUB_EXPERIMENT
    owner: https___climatepub4kg.github.io_ontology#Experiment
    domain_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    range: https___climatepub4kg.github.io_ontology#SubExperiment
  https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM:
    name: https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM
    title: APPLIES_TO_REALM
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#APPLIES_TO_REALM
    alias: https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM
    owner: https___climatepub4kg.github.io_ontology#Experiment
    domain_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    union_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#SourceComponent
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Realm
  https___climatepub4kg.github.io_ontology#name:
    name: https___climatepub4kg.github.io_ontology#name
    title: name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#name
    alias: https___climatepub4kg.github.io_ontology#name
    owner: https___climatepub4kg.github.io_ontology#Experiment
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
  https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER:
    name: https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER
    title: INCLUDES_ENSEMBLE_MEMBER
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Experiment
    slot_uri: https://climatepub4kg.github.io/ontology#INCLUDES_ENSEMBLE_MEMBER
    alias: https___climatepub4kg.github.io_ontology#INCLUDES_ENSEMBLE_MEMBER
    owner: https___climatepub4kg.github.io_ontology#Experiment
    domain_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    range: https___climatepub4kg.github.io_ontology#Ensemble
  https___climatepub4kg.github.io_ontology#USES_FORCING:
    name: https___climatepub4kg.github.io_ontology#USES_FORCING
    title: USES_FORCING
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Experiment
    slot_uri: https://climatepub4kg.github.io/ontology#USES_FORCING
    alias: https___climatepub4kg.github.io_ontology#USES_FORCING
    owner: https___climatepub4kg.github.io_ontology#Experiment
    domain_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    range: https___climatepub4kg.github.io_ontology#Forcing
  https___climatepub4kg.github.io_ontology#experiment_title:
    name: https___climatepub4kg.github.io_ontology#experiment_title
    title: experiment_title
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Experiment
    slot_uri: https://climatepub4kg.github.io/ontology#experiment_title
    alias: https___climatepub4kg.github.io_ontology#experiment_title
    owner: https___climatepub4kg.github.io_ontology#Experiment
    domain_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    range: string
  https___climatepub4kg.github.io_ontology#names:
    name: https___climatepub4kg.github.io_ontology#names
    title: names
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#names
    alias: https___climatepub4kg.github.io_ontology#names
    owner: https___climatepub4kg.github.io_ontology#Experiment
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
    - https___climatepub4kg.github.io_ontology#Realm
    - https___climatepub4kg.github.io_ontology#Domain
    - https___climatepub4kg.github.io_ontology#Ensemble
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#Member
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#Variable
    - https___climatepub4kg.github.io_ontology#ExperimentFamily
    - https___climatepub4kg.github.io_ontology#SourceType
    - https___climatepub4kg.github.io_ontology#GridLabel
    - https___climatepub4kg.github.io_ontology#SubExperiment
    - https___climatepub4kg.github.io_ontology#Institute
    - https___climatepub4kg.github.io_ontology#Resolution
    - https___climatepub4kg.github.io_ontology#Forcing
    - https___climatepub4kg.github.io_ontology#MIPEra
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Frequency
    - https___climatepub4kg.github.io_ontology#Project
    range: string
  https___climatepub4kg.github.io_ontology#PART_OF_PROJECT:
    name: https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
    title: PART_OF_PROJECT
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#PART_OF_PROJECT
    alias: https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
    owner: https___climatepub4kg.github.io_ontology#Experiment
    domain_of:
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Source
    union_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#Activity
    range: https___climatepub4kg.github.io_ontology#Project
  https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE:
    name: https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE
    title: PERFORMED_BY_INSTITUTE
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Experiment
    slot_uri: https://climatepub4kg.github.io/ontology#PERFORMED_BY_INSTITUTE
    alias: https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE
    owner: https___climatepub4kg.github.io_ontology#Experiment
    domain_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    range: https___climatepub4kg.github.io_ontology#Institute
  https___climatepub4kg.github.io_ontology#uuid:
    name: https___climatepub4kg.github.io_ontology#uuid
    title: uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#uuid
    alias: https___climatepub4kg.github.io_ontology#uuid
    owner: https___climatepub4kg.github.io_ontology#Experiment
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
class_uri: https://climatepub4kg.github.io/ontology#Experiment

```
</details>