

# Class: TODO -- what's a good name for what this class (type) describes? (sockg_Tillage)


_TODO -- tell the world what this class (type) describes._





URI: [sockg:Tillage](http://www.semanticweb.org/sockg/ontologies/2024/0/soil-carbon-ontology/Tillage)






```mermaid
 classDiagram
    class SockgTillage
    click SockgTillage href "../SockgTillage"
      SockgTillage : sockg_mgtTillage_UID
        
          
    
    
    SockgTillage --> "0..1" String : sockg_mgtTillage_UID
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sockg_mgtTillage_UID](../slots/sockg_mgtTillage_UID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SockgExperimentalUnit](../classes/SockgExperimentalUnit.md) | [sockg_hasTillage](../slots/sockg_hasTillage.md) | range | [SockgTillage](../classes/SockgTillage.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#348771 |

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
| self | sockg:Tillage |
| native | soc-kg/main/:SockgTillage |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sockg_Tillage
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 27137 instances of this class.
examples:
- value: neo4j://graph.individuals#348771
from_schema: soc-kg/main
slots:
- sockg_mgtTillage_UID
class_uri: sockg:Tillage

```
</details>

### Induced

<details>
```yaml
name: sockg_Tillage
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 27137 instances of this class.
examples:
- value: neo4j://graph.individuals#348771
from_schema: soc-kg/main
attributes:
  sockg_mgtTillage_UID:
    name: sockg_mgtTillage_UID
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 27137 occurrences with subject type sockg:Tillage and object type string.
    examples:
    - value: neo4j://graph.individuals#347758 sockg:mgtTillage_UID AgCros_MNSPReap_202LA_2008-01-01_Zea_mays_Corn_
    from_schema: soc-kg/main
    rank: 1000
    slot_uri: sockg:mgtTillage_UID
    alias: sockg_mgtTillage_UID
    owner: sockg_Tillage
    domain_of:
    - sockg_Tillage
    range: string
class_uri: sockg:Tillage

```
</details>