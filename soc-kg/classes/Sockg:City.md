

# Class: TODO -- what's a good name for what this class (type) describes? (sockg:City)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:City](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/City)






```mermaid
 classDiagram
    class Sockg:City
    click Sockg:City href "../Sockg:City"
      Sockg:City : sockg:cityName
        
          
    
    
    Sockg:City --> "0..1" String : sockg:cityName
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg:cityName](../slots/sockg:cityName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Sockg:County](../classes/Sockg:County.md) | [sockg:hasCity](../slots/sockg:hasCity.md) | range | [Sockg:City](../classes/Sockg:City.md) |
| [Sockg:Site](../classes/Sockg:Site.md) | [sockg:locatedInCity](../slots/sockg:locatedInCity.md) | range | [Sockg:City](../classes/Sockg:City.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#46716 |

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
| self | sockg:City |
| native | soc-kg/main/:Sockg:City |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg:City
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 33 instances of this class.
examples:
- value: neo4j://graph.individuals#46716
from_schema: soc-kg/main
slots:
- sockg:cityName
class_uri: sockg:City

```
</details>

### Induced

<details>
```yaml
name: sockg:City
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 33 instances of this class.
examples:
- value: neo4j://graph.individuals#46716
from_schema: soc-kg/main
attributes:
  sockg:cityName:
    name: sockg:cityName
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 33 occurrences with subject type sockg:City and object type string.
    examples:
    - value: neo4j://graph.individuals#46703 sockg:cityName University Park
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:cityName
    alias: sockg:cityName
    owner: sockg:City
    domain_of:
    - sockg:City
    range: string
class_uri: sockg:City

```
</details>