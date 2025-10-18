

# Class: Institute (https___climatepub4kg.github.io_ontology#Institute)




This class occurs 132 times.


URI: [https://climatepub4kg.github.io/ontology#Institute](https://climatepub4kg.github.io/ontology#Institute)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#Institute
    click HttpsClimatepub4kg.github.ioOntology#Institute href "../HttpsClimatepub4kg.github.ioOntology#Institute"
      HttpsClimatepub4kg.github.ioOntology#Institute : https___climatepub4kg.github.io_ontology#name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Institute --> "0..1" String : https___climatepub4kg.github.io_ontology#name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Institute : https___climatepub4kg.github.io_ontology#names
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Institute --> "0..1" String : https___climatepub4kg.github.io_ontology#names
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Institute : https___climatepub4kg.github.io_ontology#PARTICIPATED_IN
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Institute --> "0..1" HttpsClimatepub4kg.github.ioOntology#Project : https___climatepub4kg.github.io_ontology#PARTICIPATED_IN
    click HttpsClimatepub4kg.github.ioOntology#Project href "../HttpsClimatepub4kg.github.ioOntology#Project"

        
      HttpsClimatepub4kg.github.ioOntology#Institute : https___climatepub4kg.github.io_ontology#uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Institute --> "0..1" String : https___climatepub4kg.github.io_ontology#uuid
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___climatepub4kg.github.io_ontology#names](../slots/https___climatepub4kg.github.io_ontology#names.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 132 |
| [https___climatepub4kg.github.io_ontology#PARTICIPATED_IN](../slots/https___climatepub4kg.github.io_ontology#PARTICIPATED_IN.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |  <br/>  | direct | 213 |
| [https___climatepub4kg.github.io_ontology#uuid](../slots/https___climatepub4kg.github.io_ontology#uuid.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 132 |
| [https___climatepub4kg.github.io_ontology#name](../slots/https___climatepub4kg.github.io_ontology#name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 132 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) | [https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE](../slots/https___climatepub4kg.github.io_ontology#PERFORMED_BY_INSTITUTE.md) | range | [HttpsClimatepub4kg.github.ioOntology#Institute](../classes/HttpsClimatepub4kg.github.ioOntology#Institute.md) |
| [HttpsClimatepub4kg.github.ioOntology#Institute](../classes/HttpsClimatepub4kg.github.ioOntology#Institute.md) | [https___climatepub4kg.github.io_ontology#PARTICIPATED_IN](../slots/https___climatepub4kg.github.io_ontology#PARTICIPATED_IN.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Institute](../classes/HttpsClimatepub4kg.github.ioOntology#Institute.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_MENTIONS](../slots/https___climatepub4kg.github.io_ontology#PAPER_MENTIONS.md) | any_of[range] | [HttpsClimatepub4kg.github.ioOntology#Institute](../classes/HttpsClimatepub4kg.github.ioOntology#Institute.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE](../slots/https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE.md) | range | [HttpsClimatepub4kg.github.ioOntology#Institute](../classes/HttpsClimatepub4kg.github.ioOntology#Institute.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Institute
title: Institute
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- https___climatepub4kg.github.io_ontology#names
- https___climatepub4kg.github.io_ontology#PARTICIPATED_IN
- https___climatepub4kg.github.io_ontology#uuid
- https___climatepub4kg.github.io_ontology#name
class_uri: https://climatepub4kg.github.io/ontology#Institute

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Institute
title: Institute
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  https___climatepub4kg.github.io_ontology#names:
    name: https___climatepub4kg.github.io_ontology#names
    title: names
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#names
    alias: https___climatepub4kg.github.io_ontology#names
    owner: https___climatepub4kg.github.io_ontology#Institute
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
  https___climatepub4kg.github.io_ontology#PARTICIPATED_IN:
    name: https___climatepub4kg.github.io_ontology#PARTICIPATED_IN
    title: PARTICIPATED_IN
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Institute
    slot_uri: https://climatepub4kg.github.io/ontology#PARTICIPATED_IN
    alias: https___climatepub4kg.github.io_ontology#PARTICIPATED_IN
    owner: https___climatepub4kg.github.io_ontology#Institute
    domain_of:
    - https___climatepub4kg.github.io_ontology#Institute
    range: https___climatepub4kg.github.io_ontology#Project
  https___climatepub4kg.github.io_ontology#uuid:
    name: https___climatepub4kg.github.io_ontology#uuid
    title: uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#uuid
    alias: https___climatepub4kg.github.io_ontology#uuid
    owner: https___climatepub4kg.github.io_ontology#Institute
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
  https___climatepub4kg.github.io_ontology#name:
    name: https___climatepub4kg.github.io_ontology#name
    title: name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#name
    alias: https___climatepub4kg.github.io_ontology#name
    owner: https___climatepub4kg.github.io_ontology#Institute
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
class_uri: https://climatepub4kg.github.io/ontology#Institute

```
</details>