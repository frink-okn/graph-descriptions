

# Class: TODO -- what's a good name for what this class (type) describes? (sockg:Experiment)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:Experiment](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/Experiment)






```mermaid
 classDiagram
    class Sockg:Experiment
    click Sockg:Experiment href "../Sockg:Experiment"
      Sockg:Experiment : sockg:endDate
        
          
    
    
    Sockg:Experiment --> "0..1" Any : sockg:endDate
    click Any href "../Any"

        
      Sockg:Experiment : sockg:experimentName
        
          
    
    
    Sockg:Experiment --> "0..1" String : sockg:experimentName
    click String href "../String"

        
      Sockg:Experiment : sockg:happenedInSite
        
          
    
    
    Sockg:Experiment --> "0..1" Sockg:Site : sockg:happenedInSite
    click Sockg:Site href "../Sockg:Site"

        
      Sockg:Experiment : sockg:hasTreatment
        
          
    
    
    Sockg:Experiment --> "0..1" Sockg:Treatment : sockg:hasTreatment
    click Sockg:Treatment href "../Sockg:Treatment"

        
      Sockg:Experiment : sockg:projectName
        
          
    
    
    Sockg:Experiment --> "0..1" String : sockg:projectName
    click String href "../String"

        
      Sockg:Experiment : sockg:startDate
        
          
    
    
    Sockg:Experiment --> "0..1" Any : sockg:startDate
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg:hasTreatment](../slots/sockg:hasTreatment.md) | 0..1 <br/> [Sockg:Treatment](../classes/Sockg:Treatment.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:happenedInSite](../slots/sockg:happenedInSite.md) | 0..1 <br/> [Sockg:Site](../classes/Sockg:Site.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:startDate](../slots/sockg:startDate.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:experimentName](../slots/sockg:experimentName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:endDate](../slots/sockg:endDate.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:projectName](../slots/sockg:projectName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Sockg:Organization](../classes/Sockg:Organization.md) | [sockg:fundsExperiment](../slots/sockg:fundsExperiment.md) | range | [Sockg:Experiment](../classes/Sockg:Experiment.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#51720 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: soc-kg/main




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sockg:Experiment |
| native | soc-kg/main/:Sockg:Experiment |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg:Experiment
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 55 instances of this class.
examples:
- value: neo4j://graph.individuals#51720
from_schema: soc-kg/main
slots:
- sockg:hasTreatment
- sockg:happenedInSite
- sockg:startDate
- sockg:experimentName
- sockg:endDate
- sockg:projectName
class_uri: sockg:Experiment

```
</details>

### Induced

<details>
```yaml
name: sockg:Experiment
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 55 instances of this class.
examples:
- value: neo4j://graph.individuals#51720
from_schema: soc-kg/main
attributes:
  sockg:hasTreatment:
    name: sockg:hasTreatment
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 741 occurrences with subject type sockg:Experiment and object type sockg:Treatment.
    examples:
    - value: neo4j://graph.individuals#51716 sockg:hasTreatment neo4j://graph.individuals#359530
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasTreatment
    alias: sockg:hasTreatment
    owner: sockg:Experiment
    domain_of:
    - sockg:Experiment
    range: sockg:Treatment
  sockg:happenedInSite:
    name: sockg:happenedInSite
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 61 occurrences with subject type sockg:Experiment and object type sockg:Site.
    examples:
    - value: neo4j://graph.individuals#51698 sockg:happenedInSite neo4j://graph.individuals#230697
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:happenedInSite
    alias: sockg:happenedInSite
    owner: sockg:Experiment
    domain_of:
    - sockg:Experiment
    range: sockg:Site
  sockg:startDate:
    name: sockg:startDate
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:Amendment and object type string.
    - 3178 occurrences with subject type sockg:ExperimentalUnit and object type string.
    - 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
      string.
    - 631 occurrences with subject type sockg:ExperimentalUnit and object type xsd:double.
    - 55 occurrences with subject type sockg:Experiment and object type string.
    examples:
    - value: neo4j://graph.individuals#6073 sockg:startDate 2010-04-23
    - value: neo4j://graph.individuals#52263 sockg:startDate 2004-04-01
    - value: neo4j://graph.individuals#172393 sockg:startDate 1996-08-15
    - value: neo4j://graph.individuals#54995 sockg:startDate nan
    - value: neo4j://graph.individuals#51687 sockg:startDate 2009-01-01
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:startDate
    alias: sockg:startDate
    owner: sockg:Experiment
    domain_of:
    - sockg:Amendment
    - sockg:Experiment
    - sockg:ExperimentalUnit
    - sockg:GrazingManagementEvent
    range: Any
    any_of:
    - range: string
    - range: double
  sockg:experimentName:
    name: sockg:experimentName
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 55 occurrences with subject type sockg:Experiment and object type string.
    examples:
    - value: neo4j://graph.individuals#51733 sockg:experimentName Barnyard experiment
        of gas emissions, and nutrient concentrations in leachate and runoff from
        dairy cattle lots with different surface materials
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:experimentName
    alias: sockg:experimentName
    owner: sockg:Experiment
    domain_of:
    - sockg:Experiment
    range: string
  sockg:endDate:
    name: sockg:endDate
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 37796 occurrences with subject type sockg:Amendment and object type xsd:double.
    - 2026 occurrences with subject type sockg:ExperimentalUnit and object type xsd:double.
    - 1783 occurrences with subject type sockg:ExperimentalUnit and object type string.
    - 1951 occurrences with subject type sockg:GrazingManagementEvent and object type
      string.
    - 55 occurrences with subject type sockg:Experiment and object type string.
    examples:
    - value: neo4j://graph.individuals#11898 sockg:endDate nan
    - value: neo4j://graph.individuals#52943 sockg:endDate nan
    - value: neo4j://graph.individuals#52582 sockg:endDate 2009-11-11
    - value: neo4j://graph.individuals#172114 sockg:endDate 2005-08-08
    - value: neo4j://graph.individuals#51722 sockg:endDate 2011-05-18
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:endDate
    alias: sockg:endDate
    owner: sockg:Experiment
    domain_of:
    - sockg:Amendment
    - sockg:Experiment
    - sockg:ExperimentalUnit
    - sockg:GrazingManagementEvent
    range: Any
    any_of:
    - range: double
    - range: string
  sockg:projectName:
    name: sockg:projectName
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 55 occurrences with subject type sockg:Experiment and object type string.
    - 9 occurrences with subject type sockg:Project and object type string.
    examples:
    - value: neo4j://graph.individuals#51735 sockg:projectName NUOnet
    - value: neo4j://graph.individuals#227188 sockg:projectName NUOnet Alumbre, Ecuador,
        Phase 1
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:projectName
    alias: sockg:projectName
    owner: sockg:Experiment
    domain_of:
    - sockg:Experiment
    - sockg:Project
    range: string
class_uri: sockg:Experiment

```
</details>