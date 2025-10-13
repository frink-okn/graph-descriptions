

# Class: HttpsClimatepub4kg.github.ioOntology#WaterBodies




This class occurs 123 times.


URI: [https://climatepub4kg.github.io/ontology#Water_Bodies](https://climatepub4kg.github.io/ontology#Water_Bodies)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#WaterBodies
    click HttpsClimatepub4kg.github.ioOntology#WaterBodies href "../HttpsClimatepub4kg.github.ioOntology#WaterBodies"
      HttpsClimatepub4kg.github.ioOntology#WaterBodies : neo4j_east
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#WaterBodies --> "0..1" String : neo4j_east
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#WaterBodies : neo4j_geonameid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#WaterBodies --> "0..1" String : neo4j_geonameid
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#WaterBodies : neo4j_name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#WaterBodies --> "0..1" String : neo4j_name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#WaterBodies : neo4j_Name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#WaterBodies --> "0..1" String : neo4j_Name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#WaterBodies : neo4j_north
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#WaterBodies --> "0..1" String : neo4j_north
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#WaterBodies : neo4j_south
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#WaterBodies --> "0..1" String : neo4j_south
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#WaterBodies : neo4j_uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#WaterBodies --> "0..1" String : neo4j_uuid
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#WaterBodies : neo4j_west
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#WaterBodies --> "0..1" String : neo4j_west
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [neo4j_east](../slots/neo4j_east.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 123 |
| [neo4j_south](../slots/neo4j_south.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 123 |
| [neo4j_geonameid](../slots/neo4j_geonameid.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 123 |
| [neo4j_west](../slots/neo4j_west.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 123 |
| [neo4j_name](../slots/neo4j_name.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 123 |
| [neo4j_uuid](../slots/neo4j_uuid.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 123 |
| [neo4j_Name](../slots/neo4j_Name.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 123 |
| [neo4j_north](../slots/neo4j_north.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 123 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_MENTIONS](../slots/https___climatepub4kg.github.io_ontology#PAPER_MENTIONS.md) | any_of[range] | [HttpsClimatepub4kg.github.ioOntology#WaterBodies](../classes/HttpsClimatepub4kg.github.ioOntology#WaterBodies.md) |
| [HttpsClimatepub4kg.github.ioOntology#RCM](../classes/HttpsClimatepub4kg.github.ioOntology#RCM.md) | [https___climatepub4kg.github.io_ontology#COVERS_REGION](../slots/https___climatepub4kg.github.io_ontology#COVERS_REGION.md) | any_of[range] | [HttpsClimatepub4kg.github.ioOntology#WaterBodies](../classes/HttpsClimatepub4kg.github.ioOntology#WaterBodies.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Water_Bodies
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- neo4j_east
- neo4j_south
- neo4j_geonameid
- neo4j_west
- neo4j_name
- neo4j_uuid
- neo4j_Name
- neo4j_north
class_uri: https://climatepub4kg.github.io/ontology#Water_Bodies

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Water_Bodies
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  neo4j_east:
    name: neo4j_east
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:east
    alias: neo4j_east
    owner: https___climatepub4kg.github.io_ontology#Water_Bodies
    domain_of:
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    range: string
  neo4j_south:
    name: neo4j_south
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:south
    alias: neo4j_south
    owner: https___climatepub4kg.github.io_ontology#Water_Bodies
    domain_of:
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    range: string
  neo4j_geonameid:
    name: neo4j_geonameid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:geonameid
    alias: neo4j_geonameid
    owner: https___climatepub4kg.github.io_ontology#Water_Bodies
    domain_of:
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#Continent
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#No_Country_Region
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    range: string
  neo4j_west:
    name: neo4j_west
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:west
    alias: neo4j_west
    owner: https___climatepub4kg.github.io_ontology#Water_Bodies
    domain_of:
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    range: string
  neo4j_name:
    name: neo4j_name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:name
    alias: neo4j_name
    owner: https___climatepub4kg.github.io_ontology#Water_Bodies
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
  neo4j_uuid:
    name: neo4j_uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:uuid
    alias: neo4j_uuid
    owner: https___climatepub4kg.github.io_ontology#Water_Bodies
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
  neo4j_Name:
    name: neo4j_Name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:Name
    alias: neo4j_Name
    owner: https___climatepub4kg.github.io_ontology#Water_Bodies
    domain_of:
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    range: string
  neo4j_north:
    name: neo4j_north
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: neo4j:north
    alias: neo4j_north
    owner: https___climatepub4kg.github.io_ontology#Water_Bodies
    domain_of:
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    range: string
class_uri: https://climatepub4kg.github.io/ontology#Water_Bodies

```
</details>