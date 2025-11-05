

# Class: Source (https___climatepub4kg.github.io_ontology#Source)




This class occurs 394 times.


URI: [https://climatepub4kg.github.io/ontology#Source](https://climatepub4kg.github.io/ontology#Source)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#Source
    click HttpsClimatepub4kg.github.ioOntology#Source href "../HttpsClimatepub4kg.github.ioOntology#Source"
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Realm : https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM
    click HttpsClimatepub4kg.github.ioOntology#Realm href "../HttpsClimatepub4kg.github.ioOntology#Realm"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Member : https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER
    click HttpsClimatepub4kg.github.ioOntology#Member href "../HttpsClimatepub4kg.github.ioOntology#Member"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#MIPEra : https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA
    click HttpsClimatepub4kg.github.ioOntology#MIPEra href "../HttpsClimatepub4kg.github.ioOntology#MIPEra"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Activity : https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY
    click HttpsClimatepub4kg.github.ioOntology#Activity href "../HttpsClimatepub4kg.github.ioOntology#Activity"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#HAS_METRIC
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Metric : https___climatepub4kg.github.io_ontology#HAS_METRIC
    click HttpsClimatepub4kg.github.ioOntology#Metric href "../HttpsClimatepub4kg.github.ioOntology#Metric"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#PhysicalFeature : https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE
    click HttpsClimatepub4kg.github.ioOntology#PhysicalFeature href "../HttpsClimatepub4kg.github.ioOntology#PhysicalFeature"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#SimulationType : https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE
    click HttpsClimatepub4kg.github.ioOntology#SimulationType href "../HttpsClimatepub4kg.github.ioOntology#SimulationType"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#SourceComponent : https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT
    click HttpsClimatepub4kg.github.ioOntology#SourceComponent href "../HttpsClimatepub4kg.github.ioOntology#SourceComponent"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Resolution : https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION
    click HttpsClimatepub4kg.github.ioOntology#Resolution href "../HttpsClimatepub4kg.github.ioOntology#Resolution"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" Any : https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION
    click Any href "../Any"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#INHERITED_FROM
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#INHERITED_FROM
    click HttpsClimatepub4kg.github.ioOntology#Source href "../HttpsClimatepub4kg.github.ioOntology#Source"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#IS_OF_TYPE
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#SourceType : https___climatepub4kg.github.io_ontology#IS_OF_TYPE
    click HttpsClimatepub4kg.github.ioOntology#SourceType href "../HttpsClimatepub4kg.github.ioOntology#SourceType"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" String : https___climatepub4kg.github.io_ontology#name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#names
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" String : https___climatepub4kg.github.io_ontology#names
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Ensemble : https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE
    click HttpsClimatepub4kg.github.ioOntology#Ensemble href "../HttpsClimatepub4kg.github.ioOntology#Ensemble"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Project : https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
    click HttpsClimatepub4kg.github.ioOntology#Project href "../HttpsClimatepub4kg.github.ioOntology#Project"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Institute : https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE
    click HttpsClimatepub4kg.github.ioOntology#Institute href "../HttpsClimatepub4kg.github.ioOntology#Institute"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Variable : https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE
    click HttpsClimatepub4kg.github.ioOntology#Variable href "../HttpsClimatepub4kg.github.ioOntology#Variable"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Frequency : https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY
    click HttpsClimatepub4kg.github.ioOntology#Frequency href "../HttpsClimatepub4kg.github.ioOntology#Frequency"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#Experiment : https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT
    click HttpsClimatepub4kg.github.ioOntology#Experiment href "../HttpsClimatepub4kg.github.ioOntology#Experiment"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" HttpsClimatepub4kg.github.ioOntology#PhysicalScheme : https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME
    click HttpsClimatepub4kg.github.ioOntology#PhysicalScheme href "../HttpsClimatepub4kg.github.ioOntology#PhysicalScheme"

        
      HttpsClimatepub4kg.github.ioOntology#Source : https___climatepub4kg.github.io_ontology#uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Source --> "0..1" String : https___climatepub4kg.github.io_ontology#uuid
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___climatepub4kg.github.io_ontology#name](../slots/https___climatepub4kg.github.io_ontology#name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 394 |
| [https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA](../slots/https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#MIPEra](../classes/HttpsClimatepub4kg.github.ioOntology#MIPEra.md) |  <br/>  | direct | 318 |
| [https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE](../slots/https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Variable](../classes/HttpsClimatepub4kg.github.ioOntology#Variable.md) |  <br/>  | direct | 28337 |
| [https___climatepub4kg.github.io_ontology#IS_OF_TYPE](../slots/https___climatepub4kg.github.io_ontology#IS_OF_TYPE.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#SourceType](../classes/HttpsClimatepub4kg.github.ioOntology#SourceType.md) |  <br/>  | direct | 295 |
| [https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE](../slots/https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Ensemble](../classes/HttpsClimatepub4kg.github.ioOntology#Ensemble.md) |  <br/>  | direct | 53 |
| [https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME](../slots/https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#PhysicalScheme](../classes/HttpsClimatepub4kg.github.ioOntology#PhysicalScheme.md) |  <br/>  | direct | 89 |
| [https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT](../slots/https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md) |  <br/>  | direct | 1880 |
| [https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY](../slots/https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Frequency](../classes/HttpsClimatepub4kg.github.ioOntology#Frequency.md) |  <br/>  | direct | 828 |
| [https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE](../slots/https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#PhysicalFeature](../classes/HttpsClimatepub4kg.github.ioOntology#PhysicalFeature.md) |  <br/>  | direct | 43 |
| [https___climatepub4kg.github.io_ontology#uuid](../slots/https___climatepub4kg.github.io_ontology#uuid.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 394 |
| [https___climatepub4kg.github.io_ontology#HAS_METRIC](../slots/https___climatepub4kg.github.io_ontology#HAS_METRIC.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Metric](../classes/HttpsClimatepub4kg.github.ioOntology#Metric.md) |  <br/>  | direct | 49 |
| [https___climatepub4kg.github.io_ontology#PART_OF_PROJECT](../slots/https___climatepub4kg.github.io_ontology#PART_OF_PROJECT.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |  <br/>  | direct | 423 |
| [https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION](../slots/https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Resolution](../classes/HttpsClimatepub4kg.github.ioOntology#Resolution.md) |  <br/>  | direct | 432 |
| [https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT](../slots/https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#SourceComponent](../classes/HttpsClimatepub4kg.github.ioOntology#SourceComponent.md) |  <br/>  | direct | 475 |
| [https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION](../slots/https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#SourceComponent](../classes/HttpsClimatepub4kg.github.ioOntology#SourceComponent.md) |  <br/>  | direct | 1 |
| [https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM](../slots/https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Realm](../classes/HttpsClimatepub4kg.github.ioOntology#Realm.md) |  <br/>  | direct | 905 |
| [https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER](../slots/https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Member](../classes/HttpsClimatepub4kg.github.ioOntology#Member.md) |  <br/>  | direct | 11903 |
| [https___climatepub4kg.github.io_ontology#INHERITED_FROM](../slots/https___climatepub4kg.github.io_ontology#INHERITED_FROM.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |  <br/>  | direct | 2 |
| [https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE](../slots/https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#SimulationType](../classes/HttpsClimatepub4kg.github.ioOntology#SimulationType.md) |  <br/>  | direct | 37 |
| [https___climatepub4kg.github.io_ontology#names](../slots/https___climatepub4kg.github.io_ontology#names.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 394 |
| [https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY](../slots/https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Activity](../classes/HttpsClimatepub4kg.github.ioOntology#Activity.md) |  <br/>  | direct | 623 |
| [https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE](../slots/https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Institute](../classes/HttpsClimatepub4kg.github.ioOntology#Institute.md) |  <br/>  | direct | 503 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) | [https___climatepub4kg.github.io_ontology#CORRESPONDS_TO](../slots/https___climatepub4kg.github.io_ontology#CORRESPONDS_TO.md) | range | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_MENTIONS](../slots/https___climatepub4kg.github.io_ontology#PAPER_MENTIONS.md) | any_of[range] | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#RCM](../classes/HttpsClimatepub4kg.github.ioOntology#RCM.md) | [https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE](../slots/https___climatepub4kg.github.io_ontology#DRIVEN_BY_SOURCE.md) | range | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA](../slots/https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#IS_OF_TYPE](../slots/https___climatepub4kg.github.io_ontology#IS_OF_TYPE.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE](../slots/https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME](../slots/https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY](../slots/https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE](../slots/https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#HAS_METRIC](../slots/https___climatepub4kg.github.io_ontology#HAS_METRIC.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION](../slots/https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION.md) | any_of[range] | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER](../slots/https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#INHERITED_FROM](../slots/https___climatepub4kg.github.io_ontology#INHERITED_FROM.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#INHERITED_FROM](../slots/https___climatepub4kg.github.io_ontology#INHERITED_FROM.md) | range | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE](../slots/https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY](../slots/https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) | [https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE](../slots/https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |
| [HttpsClimatepub4kg.github.ioOntology#SourceComponent](../classes/HttpsClimatepub4kg.github.ioOntology#SourceComponent.md) | [https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION](../slots/https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION.md) | any_of[range] | [HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Source
title: Source
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- https___climatepub4kg.github.io_ontology#name
- https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA
- https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE
- https___climatepub4kg.github.io_ontology#IS_OF_TYPE
- https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE
- https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME
- https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT
- https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY
- https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE
- https___climatepub4kg.github.io_ontology#uuid
- https___climatepub4kg.github.io_ontology#HAS_METRIC
- https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
- https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION
- https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT
- https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION
- https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM
- https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER
- https___climatepub4kg.github.io_ontology#INHERITED_FROM
- https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE
- https___climatepub4kg.github.io_ontology#names
- https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY
- https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE
class_uri: https://climatepub4kg.github.io/ontology#Source

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Source
title: Source
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  https___climatepub4kg.github.io_ontology#name:
    name: https___climatepub4kg.github.io_ontology#name
    title: name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#name
    alias: https___climatepub4kg.github.io_ontology#name
    owner: https___climatepub4kg.github.io_ontology#Source
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
  https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA:
    name: https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA
    title: BELONGS_TO_MIP_ERA
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#BELONGS_TO_MIP_ERA
    alias: https___climatepub4kg.github.io_ontology#BELONGS_TO_MIP_ERA
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#MIPEra
  https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE:
    name: https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE
    title: PRODUCES_VARIABLE
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#PRODUCES_VARIABLE
    alias: https___climatepub4kg.github.io_ontology#PRODUCES_VARIABLE
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    union_of:
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    range: https___climatepub4kg.github.io_ontology#Variable
  https___climatepub4kg.github.io_ontology#IS_OF_TYPE:
    name: https___climatepub4kg.github.io_ontology#IS_OF_TYPE
    title: IS_OF_TYPE
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#IS_OF_TYPE
    alias: https___climatepub4kg.github.io_ontology#IS_OF_TYPE
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#SourceType
  https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE:
    name: https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE
    title: PART_OF_ENSEMBLE
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#PART_OF_ENSEMBLE
    alias: https___climatepub4kg.github.io_ontology#PART_OF_ENSEMBLE
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Ensemble
  https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME:
    name: https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME
    title: USES_PHYSICAL_SCHEME
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#USES_PHYSICAL_SCHEME
    alias: https___climatepub4kg.github.io_ontology#USES_PHYSICAL_SCHEME
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#PhysicalScheme
  https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT:
    name: https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT
    title: USED_IN_EXPERIMENT
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#USED_IN_EXPERIMENT
    alias: https___climatepub4kg.github.io_ontology#USED_IN_EXPERIMENT
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Source
    union_of:
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Experiment
  https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY:
    name: https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY
    title: SAMPLED_AT_FREQUENCY
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#SAMPLED_AT_FREQUENCY
    alias: https___climatepub4kg.github.io_ontology#SAMPLED_AT_FREQUENCY
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Frequency
  https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE:
    name: https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE
    title: HAS_PHYSICAL_FEATURE
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#HAS_PHYSICAL_FEATURE
    alias: https___climatepub4kg.github.io_ontology#HAS_PHYSICAL_FEATURE
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#PhysicalFeature
  https___climatepub4kg.github.io_ontology#uuid:
    name: https___climatepub4kg.github.io_ontology#uuid
    title: uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#uuid
    alias: https___climatepub4kg.github.io_ontology#uuid
    owner: https___climatepub4kg.github.io_ontology#Source
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
  https___climatepub4kg.github.io_ontology#HAS_METRIC:
    name: https___climatepub4kg.github.io_ontology#HAS_METRIC
    title: HAS_METRIC
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#HAS_METRIC
    alias: https___climatepub4kg.github.io_ontology#HAS_METRIC
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Metric
  https___climatepub4kg.github.io_ontology#PART_OF_PROJECT:
    name: https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
    title: PART_OF_PROJECT
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#PART_OF_PROJECT
    alias: https___climatepub4kg.github.io_ontology#PART_OF_PROJECT
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Source
    union_of:
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#Experiment
    range: https___climatepub4kg.github.io_ontology#Project
  https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION:
    name: https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION
    title: HAS_SPATIAL_RESOLUTION
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#HAS_SPATIAL_RESOLUTION
    alias: https___climatepub4kg.github.io_ontology#HAS_SPATIAL_RESOLUTION
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#Variable
    union_of:
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#Variable
    - https___climatepub4kg.github.io_ontology#Experiment
    range: https___climatepub4kg.github.io_ontology#Resolution
  https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT:
    name: https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT
    title: HAS_SOURCE_COMPONENT
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#HAS_SOURCE_COMPONENT
    alias: https___climatepub4kg.github.io_ontology#HAS_SOURCE_COMPONENT
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    union_of:
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    range: https___climatepub4kg.github.io_ontology#SourceComponent
  https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION:
    name: https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION
    title: HAS_SUBSEQUENT_VERSION
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#HAS_SUBSEQUENT_VERSION
    alias: https___climatepub4kg.github.io_ontology#HAS_SUBSEQUENT_VERSION
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    union_of:
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    range: Any
    any_of:
    - range: https___climatepub4kg.github.io_ontology#Source
    - range: https___climatepub4kg.github.io_ontology#SourceComponent
  https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM:
    name: https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM
    title: APPLIES_TO_REALM
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#APPLIES_TO_REALM
    alias: https___climatepub4kg.github.io_ontology#APPLIES_TO_REALM
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Experiment
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    union_of:
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#SourceComponent
    - https___climatepub4kg.github.io_ontology#Experiment
    range: https___climatepub4kg.github.io_ontology#Realm
  https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER:
    name: https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER
    title: ASSOCIATED_WITH_MEMBER
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#ASSOCIATED_WITH_MEMBER
    alias: https___climatepub4kg.github.io_ontology#ASSOCIATED_WITH_MEMBER
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Member
  https___climatepub4kg.github.io_ontology#INHERITED_FROM:
    name: https___climatepub4kg.github.io_ontology#INHERITED_FROM
    title: INHERITED_FROM
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#INHERITED_FROM
    alias: https___climatepub4kg.github.io_ontology#INHERITED_FROM
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Source
  https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE:
    name: https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE
    title: HAS_SIMULATION_TYPE
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#HAS_SIMULATION_TYPE
    alias: https___climatepub4kg.github.io_ontology#HAS_SIMULATION_TYPE
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#SimulationType
  https___climatepub4kg.github.io_ontology#names:
    name: https___climatepub4kg.github.io_ontology#names
    title: names
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#names
    alias: https___climatepub4kg.github.io_ontology#names
    owner: https___climatepub4kg.github.io_ontology#Source
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
    - https___climatepub4kg.github.io_ontology#Member
    - https___climatepub4kg.github.io_ontology#ExperimentFamily
    - https___climatepub4kg.github.io_ontology#Domain
    - https___climatepub4kg.github.io_ontology#RCM
    - https___climatepub4kg.github.io_ontology#Forcing
    - https___climatepub4kg.github.io_ontology#Activity
    - https___climatepub4kg.github.io_ontology#Resolution
    - https___climatepub4kg.github.io_ontology#Variable
    - https___climatepub4kg.github.io_ontology#MIPEra
    - https___climatepub4kg.github.io_ontology#Realm
    - https___climatepub4kg.github.io_ontology#SubExperiment
    - https___climatepub4kg.github.io_ontology#Source
    - https___climatepub4kg.github.io_ontology#Frequency
    - https___climatepub4kg.github.io_ontology#Project
    - https___climatepub4kg.github.io_ontology#SourceType
    - https___climatepub4kg.github.io_ontology#GridLabel
    - https___climatepub4kg.github.io_ontology#Ensemble
    - https___climatepub4kg.github.io_ontology#Institute
    - https___climatepub4kg.github.io_ontology#Experiment
    range: string
  https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY:
    name: https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY
    title: GENERATED_BY_ACTIVITY
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#GENERATED_BY_ACTIVITY
    alias: https___climatepub4kg.github.io_ontology#GENERATED_BY_ACTIVITY
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Activity
  https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE:
    name: https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE
    title: PRODUCED_BY_INSTITUTE
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Source
    slot_uri: https://climatepub4kg.github.io/ontology#PRODUCED_BY_INSTITUTE
    alias: https___climatepub4kg.github.io_ontology#PRODUCED_BY_INSTITUTE
    owner: https___climatepub4kg.github.io_ontology#Source
    domain_of:
    - https___climatepub4kg.github.io_ontology#Source
    range: https___climatepub4kg.github.io_ontology#Institute
class_uri: https://climatepub4kg.github.io/ontology#Source

```
</details>