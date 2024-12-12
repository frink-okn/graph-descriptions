

# Class: TODO -- what's a good name for what this class (type) describes? (sockg_Rotation)


_No type description provided_





URI: [sockg:Rotation](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/Rotation)






```mermaid
 classDiagram
    class SockgRotation
    click SockgRotation href "../SockgRotation"
      SockgRotation : sockg_rotationDescriptor
        
          
    
    
    SockgRotation --> "0..1" String : sockg_rotationDescriptor
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg_rotationDescriptor](../slots/sockg_rotationDescriptor.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SockgTreatment](../classes/SockgTreatment.md) | [sockg_hasRotation](../slots/sockg_hasRotation.md) | range | [SockgRotation](../classes/SockgRotation.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#230629 |

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
| self | sockg:Rotation |
| native | soc-kg/main/:SockgRotation |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg_Rotation
description: No type description provided
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 66 instances of this class.
examples:
- value: neo4j://graph.individuals#230629
from_schema: soc-kg/main
rank: 1000
slots:
- sockg_rotationDescriptor
class_uri: sockg:Rotation

```
</details>

### Induced

<details>
```yaml
name: sockg_Rotation
description: No type description provided
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 66 instances of this class.
examples:
- value: neo4j://graph.individuals#230629
from_schema: soc-kg/main
rank: 1000
attributes:
  sockg_rotationDescriptor:
    name: sockg_rotationDescriptor
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 66 occurrences with subject type sockg:Rotation and object type string.
    examples:
    - value: neo4j://graph.individuals#230661 sockg:rotationDescriptor Forage Soybean,
        Wheat, Corn
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:rotationDescriptor
    alias: sockg_rotationDescriptor
    owner: sockg_Rotation
    domain_of:
    - sockg_Rotation
    range: string
class_uri: sockg:Rotation

```
</details>