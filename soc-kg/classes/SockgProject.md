

# Class: TODO -- what's a good name for what this class (type) describes? (sockg_Project)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:Project](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/Project)






```mermaid
 classDiagram
    class SockgProject
    click SockgProject href "../SockgProject"
      SockgProject : sockg_projectName
        
          
    
    
    SockgProject --> "0..1" String : sockg_projectName
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg_projectName](../slots/sockg_projectName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |










## Examples

| Value |
| --- |
| neo4j://graph.individuals#227185 |

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
| self | sockg:Project |
| native | soc-kg/main/:SockgProject |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg_Project
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 9 instances of this class.
examples:
- value: neo4j://graph.individuals#227185
from_schema: soc-kg/main
slots:
- sockg_projectName
class_uri: sockg:Project

```
</details>

### Induced

<details>
```yaml
name: sockg_Project
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 9 instances of this class.
examples:
- value: neo4j://graph.individuals#227185
from_schema: soc-kg/main
attributes:
  sockg_projectName:
    name: sockg_projectName
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
    alias: sockg_projectName
    owner: sockg_Project
    domain_of:
    - sockg_Experiment
    - sockg_Project
    range: string
class_uri: sockg:Project

```
</details>