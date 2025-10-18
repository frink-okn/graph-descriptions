

# Class: Paper (https___climatepub4kg.github.io_ontology#Paper)




This class occurs 38 times.


URI: [https://climatepub4kg.github.io/ontology#Paper](https://climatepub4kg.github.io/ontology#Paper)






```mermaid
 classDiagram
    class HttpsClimatepub4kg.github.ioOntology#Paper
    click HttpsClimatepub4kg.github.ioOntology#Paper href "../HttpsClimatepub4kg.github.ioOntology#Paper"
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#id
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" String : https___climatepub4kg.github.io_ontology#id
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#name
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" String : https___climatepub4kg.github.io_ontology#name
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" HttpsClimatepub4kg.github.ioOntology#Method : https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD
    click HttpsClimatepub4kg.github.ioOntology#Method href "../HttpsClimatepub4kg.github.ioOntology#Method"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" HttpsClimatepub4kg.github.ioOntology#Field : https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD
    click HttpsClimatepub4kg.github.ioOntology#Field href "../HttpsClimatepub4kg.github.ioOntology#Field"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" HttpsClimatepub4kg.github.ioOntology#ObservationalDataset : https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    click HttpsClimatepub4kg.github.ioOntology#ObservationalDataset href "../HttpsClimatepub4kg.github.ioOntology#ObservationalDataset"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" HttpsClimatepub4kg.github.ioOntology#Innovation : https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION
    click HttpsClimatepub4kg.github.ioOntology#Innovation href "../HttpsClimatepub4kg.github.ioOntology#Innovation"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" HttpsClimatepub4kg.github.ioOntology#Keyword : https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD
    click HttpsClimatepub4kg.github.ioOntology#Keyword href "../HttpsClimatepub4kg.github.ioOntology#Keyword"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" HttpsClimatepub4kg.github.ioOntology#Model : https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL
    click HttpsClimatepub4kg.github.ioOntology#Model href "../HttpsClimatepub4kg.github.ioOntology#Model"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" HttpsClimatepub4kg.github.ioOntology#Result : https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT
    click HttpsClimatepub4kg.github.ioOntology#Result href "../HttpsClimatepub4kg.github.ioOntology#Result"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#PAPER_MENTIONS
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" Any : https___climatepub4kg.github.io_ontology#PAPER_MENTIONS
    click Any href "../Any"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" HttpsClimatepub4kg.github.ioOntology#Problem : https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM
    click HttpsClimatepub4kg.github.ioOntology#Problem href "../HttpsClimatepub4kg.github.ioOntology#Problem"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" HttpsClimatepub4kg.github.ioOntology#Metric : https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC
    click HttpsClimatepub4kg.github.ioOntology#Metric href "../HttpsClimatepub4kg.github.ioOntology#Metric"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" HttpsClimatepub4kg.github.ioOntology#Task : https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK
    click HttpsClimatepub4kg.github.ioOntology#Task href "../HttpsClimatepub4kg.github.ioOntology#Task"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#title
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" String : https___climatepub4kg.github.io_ontology#title
    click String href "../String"

        
      HttpsClimatepub4kg.github.ioOntology#Paper : https___climatepub4kg.github.io_ontology#uuid
        
          
    
    
    HttpsClimatepub4kg.github.ioOntology#Paper --> "0..1" String : https___climatepub4kg.github.io_ontology#uuid
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD](../slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Keyword](../classes/HttpsClimatepub4kg.github.ioOntology#Keyword.md) |  <br/>  | direct | 176 |
| [https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD](../slots/https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Field](../classes/HttpsClimatepub4kg.github.ioOntology#Field.md) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](../slots/https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#ObservationalDataset](../classes/HttpsClimatepub4kg.github.ioOntology#ObservationalDataset.md) |  <br/>  | direct | 127 |
| [https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC](../slots/https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Metric](../classes/HttpsClimatepub4kg.github.ioOntology#Metric.md) |  <br/>  | direct | 438 |
| [https___climatepub4kg.github.io_ontology#name](../slots/https___climatepub4kg.github.io_ontology#name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT](../slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Result](../classes/HttpsClimatepub4kg.github.ioOntology#Result.md) |  <br/>  | direct | 669 |
| [https___climatepub4kg.github.io_ontology#PAPER_MENTIONS](../slots/https___climatepub4kg.github.io_ontology#PAPER_MENTIONS.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Platform](../classes/HttpsClimatepub4kg.github.ioOntology#Platform.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Realm](../classes/HttpsClimatepub4kg.github.ioOntology#Realm.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#NoCountryRegion](../classes/HttpsClimatepub4kg.github.ioOntology#NoCountryRegion.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#OceanCirculation](../classes/HttpsClimatepub4kg.github.ioOntology#OceanCirculation.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#WaterBodies](../classes/HttpsClimatepub4kg.github.ioOntology#WaterBodies.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#SourceComponent](../classes/HttpsClimatepub4kg.github.ioOntology#SourceComponent.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#SimulationType](../classes/HttpsClimatepub4kg.github.ioOntology#SimulationType.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#NaturalHazard](../classes/HttpsClimatepub4kg.github.ioOntology#NaturalHazard.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Source](../classes/HttpsClimatepub4kg.github.ioOntology#Source.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Metric](../classes/HttpsClimatepub4kg.github.ioOntology#Metric.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#WeatherEvent](../classes/HttpsClimatepub4kg.github.ioOntology#WeatherEvent.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Member](../classes/HttpsClimatepub4kg.github.ioOntology#Member.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Country](../classes/HttpsClimatepub4kg.github.ioOntology#Country.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#PhysicalFeature](../classes/HttpsClimatepub4kg.github.ioOntology#PhysicalFeature.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Activity](../classes/HttpsClimatepub4kg.github.ioOntology#Activity.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Experiment](../classes/HttpsClimatepub4kg.github.ioOntology#Experiment.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Variable](../classes/HttpsClimatepub4kg.github.ioOntology#Variable.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Continent](../classes/HttpsClimatepub4kg.github.ioOntology#Continent.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Teleconnection](../classes/HttpsClimatepub4kg.github.ioOntology#Teleconnection.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#ExperimentFamily](../classes/HttpsClimatepub4kg.github.ioOntology#ExperimentFamily.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#SourceType](../classes/HttpsClimatepub4kg.github.ioOntology#SourceType.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#CountrySubdivision](../classes/HttpsClimatepub4kg.github.ioOntology#CountrySubdivision.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Instrument](../classes/HttpsClimatepub4kg.github.ioOntology#Instrument.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Institute](../classes/HttpsClimatepub4kg.github.ioOntology#Institute.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Resolution](../classes/HttpsClimatepub4kg.github.ioOntology#Resolution.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#MIPEra](../classes/HttpsClimatepub4kg.github.ioOntology#MIPEra.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#PhysicalScheme](../classes/HttpsClimatepub4kg.github.ioOntology#PhysicalScheme.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#City](../classes/HttpsClimatepub4kg.github.ioOntology#City.md)&nbsp;or&nbsp;<br />[HttpsClimatepub4kg.github.ioOntology#Project](../classes/HttpsClimatepub4kg.github.ioOntology#Project.md) |  <br/>  | direct | 4462 |
| [https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION](../slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Innovation](../classes/HttpsClimatepub4kg.github.ioOntology#Innovation.md) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD](../slots/https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Method](../classes/HttpsClimatepub4kg.github.ioOntology#Method.md) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#id](../slots/https___climatepub4kg.github.io_ontology#id.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM](../slots/https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Problem](../classes/HttpsClimatepub4kg.github.ioOntology#Problem.md) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL](../slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Model](../classes/HttpsClimatepub4kg.github.ioOntology#Model.md) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#title](../slots/https___climatepub4kg.github.io_ontology#title.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK](../slots/https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK.md) | 0..1 <br/> [HttpsClimatepub4kg.github.ioOntology#Task](../classes/HttpsClimatepub4kg.github.ioOntology#Task.md) |  <br/>  | direct | 38 |
| [https___climatepub4kg.github.io_ontology#uuid](../slots/https___climatepub4kg.github.io_ontology#uuid.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 38 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD](../slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD](../slots/https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET](../slots/https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC](../slots/https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT](../slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_MENTIONS](../slots/https___climatepub4kg.github.io_ontology#PAPER_MENTIONS.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION](../slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD](../slots/https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#id](../slots/https___climatepub4kg.github.io_ontology#id.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM](../slots/https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL](../slots/https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#title](../slots/https___climatepub4kg.github.io_ontology#title.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |
| [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) | [https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK](../slots/https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK.md) | domain | [HttpsClimatepub4kg.github.ioOntology#Paper](../classes/HttpsClimatepub4kg.github.ioOntology#Paper.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Paper
title: Paper
from_schema: okns:climatepub4-kg
rank: 1000
slots:
- https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD
- https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD
- https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
- https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC
- https___climatepub4kg.github.io_ontology#name
- https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT
- https___climatepub4kg.github.io_ontology#PAPER_MENTIONS
- https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION
- https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD
- https___climatepub4kg.github.io_ontology#id
- https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM
- https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL
- https___climatepub4kg.github.io_ontology#title
- https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK
- https___climatepub4kg.github.io_ontology#uuid
class_uri: https://climatepub4kg.github.io/ontology#Paper

```
</details>

### Induced

<details>

```yaml
name: https___climatepub4kg.github.io_ontology#Paper
title: Paper
from_schema: okns:climatepub4-kg
rank: 1000
attributes:
  https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD:
    name: https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD
    title: PAPER_HAS_KEYWORD
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#PAPER_HAS_KEYWORD
    alias: https___climatepub4kg.github.io_ontology#PAPER_HAS_KEYWORD
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: https___climatepub4kg.github.io_ontology#Keyword
  https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD:
    name: https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD
    title: PAPER_BELONGS_TO_FIELD
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#PAPER_BELONGS_TO_FIELD
    alias: https___climatepub4kg.github.io_ontology#PAPER_BELONGS_TO_FIELD
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: https___climatepub4kg.github.io_ontology#Field
  https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET:
    name: https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    title: PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    alias: https___climatepub4kg.github.io_ontology#PAPER_EXPERIMENTS_ON_OBSERVATIONAL_DATASET
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: https___climatepub4kg.github.io_ontology#ObservationalDataset
  https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC:
    name: https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC
    title: PAPER_USES_METRIC
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#PAPER_USES_METRIC
    alias: https___climatepub4kg.github.io_ontology#PAPER_USES_METRIC
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: https___climatepub4kg.github.io_ontology#Metric
  https___climatepub4kg.github.io_ontology#name:
    name: https___climatepub4kg.github.io_ontology#name
    title: name
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#name
    alias: https___climatepub4kg.github.io_ontology#name
    owner: https___climatepub4kg.github.io_ontology#Paper
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
  https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT:
    name: https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT
    title: PAPER_HAS_RESULT
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#PAPER_HAS_RESULT
    alias: https___climatepub4kg.github.io_ontology#PAPER_HAS_RESULT
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: https___climatepub4kg.github.io_ontology#Result
  https___climatepub4kg.github.io_ontology#PAPER_MENTIONS:
    name: https___climatepub4kg.github.io_ontology#PAPER_MENTIONS
    title: PAPER_MENTIONS
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#PAPER_MENTIONS
    alias: https___climatepub4kg.github.io_ontology#PAPER_MENTIONS
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: Any
    any_of:
    - range: https___climatepub4kg.github.io_ontology#Platform
    - range: https___climatepub4kg.github.io_ontology#Realm
    - range: https___climatepub4kg.github.io_ontology#No_Country_Region
    - range: https___climatepub4kg.github.io_ontology#Ocean_Circulation
    - range: https___climatepub4kg.github.io_ontology#Water_Bodies
    - range: https___climatepub4kg.github.io_ontology#SourceComponent
    - range: https___climatepub4kg.github.io_ontology#SimulationType
    - range: https___climatepub4kg.github.io_ontology#Natural_Hazard
    - range: https___climatepub4kg.github.io_ontology#Source
    - range: https___climatepub4kg.github.io_ontology#Metric
    - range: https___climatepub4kg.github.io_ontology#Weather_Event
    - range: https___climatepub4kg.github.io_ontology#Member
    - range: https___climatepub4kg.github.io_ontology#Country
    - range: https___climatepub4kg.github.io_ontology#PhysicalFeature
    - range: https___climatepub4kg.github.io_ontology#Activity
    - range: https___climatepub4kg.github.io_ontology#Experiment
    - range: https___climatepub4kg.github.io_ontology#Variable
    - range: https___climatepub4kg.github.io_ontology#Continent
    - range: https___climatepub4kg.github.io_ontology#Teleconnection
    - range: https___climatepub4kg.github.io_ontology#ExperimentFamily
    - range: https___climatepub4kg.github.io_ontology#SourceType
    - range: https___climatepub4kg.github.io_ontology#Country_Subdivision
    - range: https___climatepub4kg.github.io_ontology#Instrument
    - range: https___climatepub4kg.github.io_ontology#Institute
    - range: https___climatepub4kg.github.io_ontology#Resolution
    - range: https___climatepub4kg.github.io_ontology#MIPEra
    - range: https___climatepub4kg.github.io_ontology#PhysicalScheme
    - range: https___climatepub4kg.github.io_ontology#City
    - range: https___climatepub4kg.github.io_ontology#Project
  https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION:
    name: https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION
    title: PAPER_HAS_INNOVATION
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#PAPER_HAS_INNOVATION
    alias: https___climatepub4kg.github.io_ontology#PAPER_HAS_INNOVATION
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: https___climatepub4kg.github.io_ontology#Innovation
  https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD:
    name: https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD
    title: PAPER_APPLIES_METHOD
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#PAPER_APPLIES_METHOD
    alias: https___climatepub4kg.github.io_ontology#PAPER_APPLIES_METHOD
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: https___climatepub4kg.github.io_ontology#Method
  https___climatepub4kg.github.io_ontology#id:
    name: https___climatepub4kg.github.io_ontology#id
    title: id
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#id
    alias: https___climatepub4kg.github.io_ontology#id
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: string
  https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM:
    name: https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM
    title: PAPER_SOLVES_PROBLEM
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#PAPER_SOLVES_PROBLEM
    alias: https___climatepub4kg.github.io_ontology#PAPER_SOLVES_PROBLEM
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: https___climatepub4kg.github.io_ontology#Problem
  https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL:
    name: https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL
    title: PAPER_HAS_MODEL
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#PAPER_HAS_MODEL
    alias: https___climatepub4kg.github.io_ontology#PAPER_HAS_MODEL
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: https___climatepub4kg.github.io_ontology#Model
  https___climatepub4kg.github.io_ontology#title:
    name: https___climatepub4kg.github.io_ontology#title
    title: title
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#title
    alias: https___climatepub4kg.github.io_ontology#title
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: string
  https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK:
    name: https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK
    title: PAPER_WORKS_ON_TASK
    from_schema: okns:climatepub4-kg
    rank: 1000
    domain: https___climatepub4kg.github.io_ontology#Paper
    slot_uri: https://climatepub4kg.github.io/ontology#PAPER_WORKS_ON_TASK
    alias: https___climatepub4kg.github.io_ontology#PAPER_WORKS_ON_TASK
    owner: https___climatepub4kg.github.io_ontology#Paper
    domain_of:
    - https___climatepub4kg.github.io_ontology#Paper
    range: https___climatepub4kg.github.io_ontology#Task
  https___climatepub4kg.github.io_ontology#uuid:
    name: https___climatepub4kg.github.io_ontology#uuid
    title: uuid
    from_schema: okns:climatepub4-kg
    rank: 1000
    slot_uri: https://climatepub4kg.github.io/ontology#uuid
    alias: https___climatepub4kg.github.io_ontology#uuid
    owner: https___climatepub4kg.github.io_ontology#Paper
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
class_uri: https://climatepub4kg.github.io/ontology#Paper

```
</details>