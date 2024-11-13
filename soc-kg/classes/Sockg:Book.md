

# Class: TODO -- what's a good name for what this class (type) describes? (sockg:Book)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:Book](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/Book)






```mermaid
 classDiagram
    class Sockg:Book
    click Sockg:Book href "../Sockg:Book"
      Sockg:Book : sockg:bookName
        
          
    
    
    Sockg:Book --> "0..1" String : sockg:bookName
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg:bookName](../slots/sockg:bookName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |










## Examples

| Value |
| --- |
| neo4j://graph.individuals#46685 |

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
| self | sockg:Book |
| native | soc-kg/main/:Sockg:Book |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg:Book
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 2 instances of this class.
examples:
- value: neo4j://graph.individuals#46685
from_schema: soc-kg/main
slots:
- sockg:bookName
class_uri: sockg:Book

```
</details>

### Induced

<details>
```yaml
name: sockg:Book
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 2 instances of this class.
examples:
- value: neo4j://graph.individuals#46685
from_schema: soc-kg/main
attributes:
  sockg:bookName:
    name: sockg:bookName
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 2 occurrences with subject type sockg:Book and object type string.
    examples:
    - value: neo4j://graph.individuals#46685 sockg:bookName Fractal Frontiers
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:bookName
    alias: sockg:bookName
    owner: sockg:Book
    domain_of:
    - sockg:Book
    range: string
class_uri: sockg:Book

```
</details>