

# Class: TODO -- what's a good name for what this class (type) describes? (sockg:County)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:County](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/County)






```mermaid
 classDiagram
    class Sockg:County
    click Sockg:County href "../Sockg:County"
      Sockg:County : sockg:countyName
        
          
    
    
    Sockg:County --> "0..1" String : sockg:countyName
    click String href "../String"

        
      Sockg:County : sockg:hasCity
        
          
    
    
    Sockg:County --> "0..1" Sockg:City : sockg:hasCity
    click Sockg:City href "../Sockg:City"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg:hasCity](../slots/sockg:hasCity.md) | 0..1 <br/> [Sockg:City](../classes/Sockg:City.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sockg:countyName](../slots/sockg:countyName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Sockg:Site](../classes/Sockg:Site.md) | [sockg:locatedInCounty](../slots/sockg:locatedInCounty.md) | range | [Sockg:County](../classes/Sockg:County.md) |
| [Sockg:State](../classes/Sockg:State.md) | [sockg:hasCounty](../slots/sockg:hasCounty.md) | range | [Sockg:County](../classes/Sockg:County.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#46730 |

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
| self | sockg:County |
| native | soc-kg/main/:Sockg:County |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg:County
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 33 instances of this class.
examples:
- value: neo4j://graph.individuals#46730
from_schema: soc-kg/main
slots:
- sockg:hasCity
- sockg:countyName
class_uri: sockg:County

```
</details>

### Induced

<details>
```yaml
name: sockg:County
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 33 instances of this class.
examples:
- value: neo4j://graph.individuals#46730
from_schema: soc-kg/main
attributes:
  sockg:hasCity:
    name: sockg:hasCity
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 33 occurrences with subject type sockg:County and object type sockg:City.
    examples:
    - value: neo4j://graph.individuals#46724 sockg:hasCity neo4j://graph.individuals#46688
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:hasCity
    alias: sockg:hasCity
    owner: sockg:County
    domain_of:
    - sockg:County
    range: sockg:City
  sockg:countyName:
    name: sockg:countyName
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 33 occurrences with subject type sockg:County and object type string.
    examples:
    - value: neo4j://graph.individuals#46740 sockg:countyName Brookings
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:countyName
    alias: sockg:countyName
    owner: sockg:County
    domain_of:
    - sockg:County
    range: string
class_uri: sockg:County

```
</details>