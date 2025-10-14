

# Class: HttpsClimatepub4kg.github.ioOntology#RCM




This class occurs 42 times.


URI: [https://climatepub4kg.github.io/ontology#RCM](https://climatepub4kg.github.io/ontology#RCM)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#RCM
    click HttpsClimatepub4kg.github.ioOntology#RCM href "../HttpsClimatepub4kg.github.ioOntology#RCM"
      HttpsClimatepub4kg.github.ioOntology#RCM : https___climatepub4kg.github.io_ontology#COVERS_DOMAIN
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#RCM --> "0..1" HttpsClimatepub4kg.github.ioOntology#Domain : https___climatepub4kg.github.io_ontology#COVERS_DOMAIN
    click HttpsClimatepub4kg.github.ioOntology#Domain href "../HttpsClimatepub4kg.github.ioOntology#Domain"

        
      HttpsClimatepub4kg.github.ioOntology#RCM : https___climatepub4kg.github.io_ontology#COVERS_REGION
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#RCM --> "0..1" Any : https___climatepub4kg.github.io_ontology#COVERS_REGION
    click Any href "../Any"

        
      HttpsClimatepub4kg.github.ioOntology#RCM : https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#RCM --> "0..1" HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE
    click HttpsClimatepub4kg.github.ioOntology#Source href "../HttpsClimatepub4kg.github.ioOntology#Source"

        
      HttpsClimatepub4kg.github.ioOntology#RCM : https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#RCM --> "0..1" HttpsClimatepub4kg.github.ioOntology#Project : https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
    click HttpsClimatepub4kg.github.ioOntology#Project href "../HttpsClimatepub4kg.github.ioOntology#Project"

        
      HttpsClimatepub4kg.github.ioOntology#RCM : https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#RCM --> "0..1" HttpsClimatepub4kg.github.ioOntology#Variable : https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE
    click HttpsClimatepub4kg.github.ioOntology#Variable href "../HttpsClimatepub4kg.github.ioOntology#Variable"

        
      HttpsClimatepub4kg.github.ioOntology#RCM : https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#RCM --> "0..1" HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT
    click HttpsClimatepub4kg.github.ioOntology#Experiment href "../HttpsClimatepub4kg.github.ioOntology#Experiment"

        
      HttpsClimatepub4kg.github.ioOntology#RCM : neo4j_name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#RCM --> "0..1" String : neo4j_name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#RCM : neo4j_names
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#RCM --> "0..1" String : neo4j_names
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#RCM : neo4j_rcm_version
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#RCM --> "0..1" String : neo4j_rcm_version
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#RCM : neo4j_uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#RCM --> "0..1" String : neo4j_uuid
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [neo4j_uuid](../slots/neo4j_uuid.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 42 |
| [https___climatepub4kg.github.io_ontology#COVERS_DOMAIN](../slots/https___climatepub4kg.github.io_ontology#COVERS_DOMAIN.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Domain](../classes/HttpsClimatepub4kg.github.ioOntology#Domain.md) |  <br/>  | direct | 83 |
| [neo4j_names](../slots/neo4j_names.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 42 |
| [neo4j_name](../slots/neo4j_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 42 |
| [https___climatepub4kg.github.io_ontology#PART_OF_PROJECT](../slots/https___climatepub4kg.github.io_ontology#PART_OF_PROJECT.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |  <br/>  | direct | 53 |
| [https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT](../slots/https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |  <br/>  | direct | 139 |
| [https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE](../slots/https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Variable](../classes/HttpsClimatepub4kg.github.ioOntology#Variable.md) |  <br/>  | direct | 2392 |
| [https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE](../slots/https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |  <br/>  | direct | 139 |
| [neo4j_rcm_version](../slots/neo4j_rcm_version.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 42 |
| [https___climatepub4kg.github.io_ontology#COVERS_REGION](../slots/https___climatepub4kg.github.io_ontology#COVERS_REGION.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#NoCountryRegion](../classes/HttpsClimatepub4kg.github.ioOntology#NoCountryRegion.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#WaterBodies](../classes/HttpsClimatepub4kg.github.ioOntology#WaterBodies.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Continent](../classes/HttpsClimatepub4kg.github.ioOntology#Continent.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#CountrySubdivision](../classes/HttpsClimatepub4kg.github.ioOntology#CountrySubdivision.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#City](../classes/HttpsClimatepub4kg.github.ioOntology#City.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Country](../classes/HttpsClimatepub4kg.github.ioOntology#Country.md) |  <br/>  | direct | 397621 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#RCM
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- neo4j_uuid
- https___climatepub4kg.github.io_ontology#COVERS_DOMAIN
- neo4j_names
- neo4j_name
- https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
- https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT
- https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE
- https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE
- neo4j_rcm_version
- https___climatepub4kg.github.io_ontology#COVERS_REGION
class_uri: https://climatepub4kg.github.io/ontology#RCM

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#RCM
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  neo4j_uuid:
    name: neo4j_uuid
    title: uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:uuid
    alias: neo4j_uuid
    owner: https___climatepub4kg.github.io_ontology#RCM
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
    - neo4j_Experiment
    - neo4j_Model
    - neo4j_Institute
    - neo4j_ObservationalDataset
    - neo4j_Instrument
    - neo4j_Method
    - neo4j_Metric
    - neo4j_Member
    - neo4j_No_Country_Region
    - neo4j_Natural_Hazard
    - neo4j_Problem
    - neo4j_Water_Bodies
    - neo4j_Country
    - neo4j_GridLabel
    - neo4j_Innovation
    - neo4j_Project
    - neo4j_Ensemble
    - neo4j_SourceType
    - neo4j_ExperimentFamily
    - neo4j_Forcing
    - neo4j_NaturalHazardType
    - neo4j_Ocean_Circulation
    - neo4j_Variable
    - neo4j_Field
    - neo4j_Teleconnection
    - neo4j_City
    - neo4j_RCM
    - neo4j_Keyword
    - neo4j_Continent
    - neo4j_Task
    - neo4j_Domain
    - neo4j_PhysicalScheme
    - neo4j_SubExperiment
    - neo4j_Paper
    - neo4j_MIPEra
    - neo4j_Weather_Event
    - neo4j_Result
    - neo4j_Platform
    - neo4j_Frequency
    - neo4j_Country_Subdivision
    - neo4j_Realm
    - neo4j_SimulationType
    - neo4j_Activity
    - neo4j_Resolution
    - neo4j_PhysicalFeature
    - neo4j_SourceComponent
    - neo4j_Source
    range: string
  https___climatepub4kg.github.io_ontology#COVERS_DOMAIN:
    name: https___climatepub4kg.github.io_ontology#COVERS_DOMAIN
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#COVERS_DOMAIN
    alias: https___climatepub4kg.github.io_ontology#COVERS_DOMAIN
    owner: https___climatepub4kg.github.io_ontology#RCM
    domain_of:
    - https___climatepub4kg.github.io_ontology#Project
    - https___climatepub4kg.github.io_ontology#RCM
    range: https___climatepub4kg.github.io_ontology#Domain
  neo4j_names:
    name: neo4j_names
    title: names
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:names
    alias: neo4j_names
    owner: https___climatepub4kg.github.io_ontology#RCM
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
  neo4j_name:
    name: neo4j_name
    title: name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:name
    alias: neo4j_name
    owner: https___climatepub4kg.github.io_ontology#RCM
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
    - neo4j_Experiment
    - neo4j_Model
    - neo4j_Institute
    - neo4j_ObservationalDataset
    - neo4j_Instrument
    - neo4j_Method
    - neo4j_Metric
    - neo4j_Member
    - neo4j_No_Country_Region
    - neo4j_Natural_Hazard
    - neo4j_Problem
    - neo4j_Water_Bodies
    - neo4j_Country
    - neo4j_GridLabel
    - neo4j_Innovation
    - neo4j_Project
    - neo4j_Ensemble
    - neo4j_SourceType
    - neo4j_ExperimentFamily
    - neo4j_Forcing
    - neo4j_NaturalHazardType
    - neo4j_Ocean_Circulation
    - neo4j_Variable
    - neo4j_Field
    - neo4j_Teleconnection
    - neo4j_City
    - neo4j_RCM
    - neo4j_Keyword
    - neo4j_Continent
    - neo4j_Task
    - neo4j_Domain
    - neo4j_PhysicalScheme
    - neo4j_SubExperiment
    - neo4j_Paper
    - neo4j_MIPEra
    - neo4j_Weather_Event
    - neo4j_Result
    - neo4j_Platform
    - neo4j_Frequency
    - neo4j_Country_Subdivision
    - neo4j_Realm
    - neo4j_SimulationType
    - neo4j_Activity
    - neo4j_Resolution
    - neo4j_PhysicalFeature
    - neo4j_SourceComponent
    - neo4j_Source
    range: string
  https___climatepub4kg.github.io_ontology#PART_OF_PROJECT:
    name: https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#PART_OF_PROJECT
    alias: https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
    owner: https___climatepub4kg.github.io_ontology#RCM
    domain_of:
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Project
  https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT:
    name: https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#USED_IN_EXPERIMENT
    alias: https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT
    owner: https___climatepub4kg.github.io_ontology#RCM
    domain_of:
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Experiment
  https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE:
    name: https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#PRODUCES_VARIABLE
    alias: https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE
    owner: https___climatepub4kg.github.io_ontology#RCM
    domain_of:
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    range: https___climatepub4kg.github.io_ontology#Variable
  https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE:
    name: https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#DRIVEN_BY_SOURCE
    alias: https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE
    owner: https___climatepub4kg.github.io_ontology#RCM
    domain_of:
    - https___climatepub4kg.github.io_ontology#RCM
    range: https___climatepub4kg.github.io_ontology#Source
  neo4j_rcm_version:
    name: neo4j_rcm_version
    title: rcm_version
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: neo4j_RCM
    slot_uri: neo4j:rcm_version
    alias: neo4j_rcm_version
    owner: https___climatepub4kg.github.io_ontology#RCM
    domain_of:
    - https___climatepub4kg.github.io_ontology#RCM
    range: string
  https___climatepub4kg.github.io_ontology#COVERS_REGION:
    name: https___climatepub4kg.github.io_ontology#COVERS_REGION
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#COVERS_REGION
    alias: https___climatepub4kg.github.io_ontology#COVERS_REGION
    owner: https___climatepub4kg.github.io_ontology#RCM
    domain_of:
    - https___climatepub4kg.github.io_ontology#RCM
    range: Any
    any_of:
    - range: https___climatepub4kg.github.io_ontology#No_Country_Region
    - range: https___climatepub4kg.github.io_ontology#Water_Bodies
    - range: https___climatepub4kg.github.io_ontology#Continent
    - range: https___climatepub4kg.github.io_ontology#Country_Subdivision
    - range: https___climatepub4kg.github.io_ontology#City
    - range: https___climatepub4kg.github.io_ontology#Country
class_uri: https://climatepub4kg.github.io/ontology#RCM

```
</details>