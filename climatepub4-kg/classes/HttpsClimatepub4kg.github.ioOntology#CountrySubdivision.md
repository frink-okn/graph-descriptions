

# Class: Country_Subdivision (https___climatepub4kg.github.io_ontology#Country_Subdivision)




This class occurs 3893 times.


URI: [https://climatepub4kg.github.io/ontology#Country_Subdivision](https://climatepub4kg.github.io/ontology#Country_Subdivision)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#CountrySubdivision
    click HttpsClimatepub4kg.github.ioOntology#CountrySubdivision href "../HttpsClimatepub4kg.github.ioOntology#CountrySubdivision"
      HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : https___climatepub4kg.github.io_ontology#asciiname
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#CountrySubdivision --> "0..1" String : https___climatepub4kg.github.io_ontology#asciiname
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : https___climatepub4kg.github.io_ontology#code
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#CountrySubdivision --> "0..1" String : https___climatepub4kg.github.io_ontology#code
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : https___climatepub4kg.github.io_ontology#east
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#CountrySubdivision --> "0..1" String : https___climatepub4kg.github.io_ontology#east
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : https___climatepub4kg.github.io_ontology#geonameid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#CountrySubdivision --> "0..1" String : https___climatepub4kg.github.io_ontology#geonameid
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : https___climatepub4kg.github.io_ontology#IN_COUNTRY
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#CountrySubdivision --> "0..1" HttpsClimatepub4kg.github.ioOntology#Country : https___climatepub4kg.github.io_ontology#IN_COUNTRY
    click HttpsClimatepub4kg.github.ioOntology#Country href "../HttpsClimatepub4kg.github.ioOntology#Country"

        
      HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : https___climatepub4kg.github.io_ontology#name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#CountrySubdivision --> "0..1" String : https___climatepub4kg.github.io_ontology#name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : https___climatepub4kg.github.io_ontology#north
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#CountrySubdivision --> "0..1" String : https___climatepub4kg.github.io_ontology#north
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : https___climatepub4kg.github.io_ontology#south
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#CountrySubdivision --> "0..1" String : https___climatepub4kg.github.io_ontology#south
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : https___climatepub4kg.github.io_ontology#uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#CountrySubdivision --> "0..1" String : https___climatepub4kg.github.io_ontology#uuid
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#CountrySubdivision : https___climatepub4kg.github.io_ontology#west
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#CountrySubdivision --> "0..1" String : https___climatepub4kg.github.io_ontology#west
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___climatepub4kg.github.io_ontology#asciiname](../slots/https___climatepub4kg.github.io_ontology#asciiname.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 3893 |
| [https___climatepub4kg.github.io_ontology#geonameid](../slots/https___climatepub4kg.github.io_ontology#geonameid.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 3893 |
| [https___climatepub4kg.github.io_ontology#south](../slots/https___climatepub4kg.github.io_ontology#south.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 3893 |
| [https___climatepub4kg.github.io_ontology#code](../slots/https___climatepub4kg.github.io_ontology#code.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 3893 |
| [https___climatepub4kg.github.io_ontology#north](../slots/https___climatepub4kg.github.io_ontology#north.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 3893 |
| [https___climatepub4kg.github.io_ontology#east](../slots/https___climatepub4kg.github.io_ontology#east.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 3893 |
| [https___climatepub4kg.github.io_ontology#IN_COUNTRY](../slots/https___climatepub4kg.github.io_ontology#IN_COUNTRY.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Country](../classes/HttpsClimatepub4kg.github.ioOntology#Country.md) |  <br/>  | direct | 3879 |
| [https___climatepub4kg.github.io_ontology#name](../slots/https___climatepub4kg.github.io_ontology#name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 3893 |
| [https___climatepub4kg.github.io_ontology#west](../slots/https___climatepub4kg.github.io_ontology#west.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 3893 |
| [https___climatepub4kg.github.io_ontology#uuid](../slots/https___climatepub4kg.github.io_ontology#uuid.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 3893 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#CountrySubdivision](../classes/HttpsClimatepub4kg.github.ioOntology#CountrySubdivision.md) | [https___climatepub4kg.github.io_ontology#code](../slots/https___climatepub4kg.github.io_ontology#code.md) | domain | [HttpsClimatepub4kg.github.ioOntology#CountrySubdivision](../classes/HttpsClimatepub4kg.github.ioOntology#CountrySubdivision.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_MENTIONS](../slots/https___climatepub4kg.github.io_ontology#PAPER_MENTIONS.md) | any_of[range] | [HttpsClimatepub4kg.github.ioOntology#CountrySubdivision](../classes/HttpsClimatepub4kg.github.ioOntology#CountrySubdivision.md) |
| [HttpsClimatepub4kg.github.ioOntology#RCM](../classes/HttpsClimatepub4kg.github.ioOntology#RCM.md) | [https___climatepub4kg.github.io_ontology#COVERS_REGION](../slots/https___climatepub4kg.github.io_ontology#COVERS_REGION.md) | any_of[range] | [HttpsClimatepub4kg.github.ioOntology#CountrySubdivision](../classes/HttpsClimatepub4kg.github.ioOntology#CountrySubdivision.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Country_Subdivision
title: Country_Subdivision
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- https___climatepub4kg.github.io_ontology#asciiname
- https___climatepub4kg.github.io_ontology#geonameid
- https___climatepub4kg.github.io_ontology#south
- https___climatepub4kg.github.io_ontology#code
- https___climatepub4kg.github.io_ontology#north
- https___climatepub4kg.github.io_ontology#east
- https___climatepub4kg.github.io_ontology#IN_COUNTRY
- https___climatepub4kg.github.io_ontology#name
- https___climatepub4kg.github.io_ontology#west
- https___climatepub4kg.github.io_ontology#uuid
class_uri: https://climatepub4kg.github.io/ontology#Country_Subdivision

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Country_Subdivision
title: Country_Subdivision
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  https___climatepub4kg.github.io_ontology#asciiname:
    name: https___climatepub4kg.github.io_ontology#asciiname
    title: asciiname
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#asciiname
    alias: https___climatepub4kg.github.io_ontology#asciiname
    owner: https___climatepub4kg.github.io_ontology#Country_Subdivision
    domain_of:
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#No_Country_Region
    union_of:
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#No_Country_Region
    range: string
  https___climatepub4kg.github.io_ontology#geonameid:
    name: https___climatepub4kg.github.io_ontology#geonameid
    title: geonameid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#geonameid
    alias: https___climatepub4kg.github.io_ontology#geonameid
    owner: https___climatepub4kg.github.io_ontology#Country_Subdivision
    domain_of:
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#Continent
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#No_Country_Region
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    union_of:
    - https___climatepub4kg.github.io_ontology#Continent
    - https___climatepub4kg.github.io_ontology#No_Country_Region
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    - https___climatepub4kg.github.io_ontology#Country
    range: string
  https___climatepub4kg.github.io_ontology#south:
    name: https___climatepub4kg.github.io_ontology#south
    title: south
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#south
    alias: https___climatepub4kg.github.io_ontology#south
    owner: https___climatepub4kg.github.io_ontology#Country_Subdivision
    domain_of:
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    union_of:
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    range: string
  https___climatepub4kg.github.io_ontology#code:
    name: https___climatepub4kg.github.io_ontology#code
    title: code
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Country_Subdivision
    slot_uri: https://climatepub4kg.github.io/ontology#code
    alias: https___climatepub4kg.github.io_ontology#code
    owner: https___climatepub4kg.github.io_ontology#Country_Subdivision
    domain_of:
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    range: string
  https___climatepub4kg.github.io_ontology#north:
    name: https___climatepub4kg.github.io_ontology#north
    title: north
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#north
    alias: https___climatepub4kg.github.io_ontology#north
    owner: https___climatepub4kg.github.io_ontology#Country_Subdivision
    domain_of:
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    union_of:
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    range: string
  https___climatepub4kg.github.io_ontology#east:
    name: https___climatepub4kg.github.io_ontology#east
    title: east
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#east
    alias: https___climatepub4kg.github.io_ontology#east
    owner: https___climatepub4kg.github.io_ontology#Country_Subdivision
    domain_of:
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    union_of:
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    range: string
  https___climatepub4kg.github.io_ontology#IN_COUNTRY:
    name: https___climatepub4kg.github.io_ontology#IN_COUNTRY
    title: IN_COUNTRY
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#IN_COUNTRY
    alias: https___climatepub4kg.github.io_ontology#IN_COUNTRY
    owner: https___climatepub4kg.github.io_ontology#Country_Subdivision
    domain_of:
    - https___climatepub4kg.github.io_ontology#City
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    union_of:
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#City
    range: https___climatepub4kg.github.io_ontology#Country
  https___climatepub4kg.github.io_ontology#name:
    name: https___climatepub4kg.github.io_ontology#name
    title: name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#name
    alias: https___climatepub4kg.github.io_ontology#name
    owner: https___climatepub4kg.github.io_ontology#Country_Subdivision
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
  https___climatepub4kg.github.io_ontology#west:
    name: https___climatepub4kg.github.io_ontology#west
    title: west
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#west
    alias: https___climatepub4kg.github.io_ontology#west
    owner: https___climatepub4kg.github.io_ontology#Country_Subdivision
    domain_of:
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    union_of:
    - https___climatepub4kg.github.io_ontology#Water_Bodies
    - https___climatepub4kg.github.io_ontology#Country
    - https___climatepub4kg.github.io_ontology#Country_Subdivision
    range: string
  https___climatepub4kg.github.io_ontology#uuid:
    name: https___climatepub4kg.github.io_ontology#uuid
    title: uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#uuid
    alias: https___climatepub4kg.github.io_ontology#uuid
    owner: https___climatepub4kg.github.io_ontology#Country_Subdivision
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
class_uri: https://climatepub4kg.github.io/ontology#Country_Subdivision

```
</details>