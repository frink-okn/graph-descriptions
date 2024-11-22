

# Class: TODO -- what's a good name for this class (type)? (neo4j_Organism)


_TODO -- tell the world what this class (type) describes._





URI: [neo4j:Organism](neo4j://graph.schema#Organism)






```mermaid
 classDiagram
    class Neo4jOrganism
    click Neo4jOrganism href "../Neo4jOrganism"
      Neo4jOrganism : neo4j_identifier
        
          
    
    
    Neo4jOrganism --> "0..1" String : neo4j_identifier
    click String href "../String"

        
      Neo4jOrganism : neo4j_ISOLATEDIN_OiL
        
          
    
    
    Neo4jOrganism --> "0..1" Neo4jLocation : neo4j_ISOLATEDIN_OiL
    click Neo4jLocation href "../Neo4jLocation"

        
      Neo4jOrganism : neo4j_name
        
          
    
    
    Neo4jOrganism --> "0..1" String : neo4j_name
    click String href "../String"

        
      Neo4jOrganism : neo4j_RESPONDS_TO_OrC
        
          
    
    
    Neo4jOrganism --> "0..1" Neo4jCompound : neo4j_RESPONDS_TO_OrC
    click Neo4jCompound href "../Neo4jCompound"

        
      Neo4jOrganism : neo4j_sources
        
          
    
    
    Neo4jOrganism --> "0..1" String : neo4j_sources
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [neo4j_ISOLATEDIN_OiL](../slots/neo4j_ISOLATEDIN_OiL.md) | 0..1 <br/> [Neo4jLocation](../classes/Neo4jLocation.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [neo4j_RESPONDS_TO_OrC](../slots/neo4j_RESPONDS_TO_OrC.md) | 0..1 <br/> [Neo4jCompound](../classes/Neo4jCompound.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [neo4j_identifier](../slots/neo4j_identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [neo4j_name](../slots/neo4j_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [neo4j_sources](../slots/neo4j_sources.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |










## Examples

| Value |
| --- |
| neo4j://graph.individuals#105042 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:Organism |
| native | spoke-kg/:Neo4jOrganism |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: neo4j_Organism
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 321442 occurences.
examples:
- value: neo4j://graph.individuals#105042
from_schema: spoke-kg
slots:
- neo4j_ISOLATEDIN_OiL
- neo4j_RESPONDS_TO_OrC
- neo4j_identifier
- neo4j_name
- neo4j_sources
class_uri: neo4j:Organism

```
</details>

### Induced

<details>
```yaml
name: neo4j_Organism
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 321442 occurences.
examples:
- value: neo4j://graph.individuals#105042
from_schema: spoke-kg
attributes:
  neo4j_ISOLATEDIN_OiL:
    name: neo4j_ISOLATEDIN_OiL
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 321442 occurrences with subject type neo4j_Organism and object type neo4j_Location.
    examples:
    - value: neo4j://graph.individuals#38641 neo4j:ISOLATEDIN_OiL neo4j://graph.individuals#80505
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:ISOLATEDIN_OiL
    alias: neo4j_ISOLATEDIN_OiL
    owner: neo4j_Organism
    domain_of:
    - neo4j_Organism
    range: neo4j_Location
  neo4j_RESPONDS_TO_OrC:
    name: neo4j_RESPONDS_TO_OrC
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 5138 occurrences with subject type neo4j_Organism and object type neo4j_Compound.
    examples:
    - value: neo4j://graph.individuals#31108418 neo4j:RESPONDS_TO_OrC neo4j://graph.individuals#1961711
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:RESPONDS_TO_OrC
    alias: neo4j_RESPONDS_TO_OrC
    owner: neo4j_Organism
    domain_of:
    - neo4j_Organism
    range: neo4j_Compound
  neo4j_identifier:
    name: neo4j_identifier
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 2 occurrences with subject type neo4j_Environment and object type string.
    - 1426 occurrences with subject type neo4j_SDoH and object type string.
    - 106067 occurrences with subject type neo4j_Location and object type string.
    - 180 occurrences with subject type neo4j_Disease and object type string.
    - 798 occurrences with subject type neo4j_Compound and object type string.
    - 321442 occurrences with subject type neo4j_Organism and object type string.
    examples:
    - value: neo4j://graph.individuals#105029 neo4j:identifier ENVO_01000405
    - value: neo4j://graph.individuals#119274 neo4j:identifier 158928002
    - value: neo4j://graph.individuals#123229 neo4j:identifier 049999985379
    - value: neo4j://graph.individuals#142359 neo4j:identifier DOID:3074
    - value: neo4j://graph.individuals#1961711 neo4j:identifier inchikey:NWXMGUDVXFXRIG-WESIUVDSSA-N
    - value: neo4j://graph.individuals#105042 neo4j:identifier 104102.36
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:identifier
    alias: neo4j_identifier
    owner: neo4j_Organism
    domain_of:
    - neo4j_Compound
    - neo4j_Disease
    - neo4j_Environment
    - neo4j_Location
    - neo4j_Organism
    - neo4j_SDoH
    range: string
  neo4j_name:
    name: neo4j_name
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 2 occurrences with subject type neo4j_Environment and object type string.
    - 1426 occurrences with subject type neo4j_SDoH and object type string.
    - 106067 occurrences with subject type neo4j_Location and object type string.
    - 180 occurrences with subject type neo4j_Disease and object type string.
    - 798 occurrences with subject type neo4j_Compound and object type string.
    - 321442 occurrences with subject type neo4j_Organism and object type string.
    examples:
    - value: neo4j://graph.individuals#105029 neo4j:name respirable suspended particulate
        matter
    - value: neo4j://graph.individuals#119274 neo4j:name Social scientist (occupation)
    - value: neo4j://graph.individuals#123229 neo4j:name Outside city limits
    - value: neo4j://graph.individuals#142359 neo4j:name giant cell glioblastoma
    - value: neo4j://graph.individuals#1961711 neo4j:name Tetracycline
    - value: neo4j://graph.individuals#105042 neo4j:name Acetobacter tropicalis strain
        DmPark25_167
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:name
    alias: neo4j_name
    owner: neo4j_Organism
    domain_of:
    - neo4j_Compound
    - neo4j_Disease
    - neo4j_Environment
    - neo4j_Location
    - neo4j_Organism
    - neo4j_SDoH
    range: string
  neo4j_sources:
    name: neo4j_sources
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 2 occurrences with subject type neo4j_Environment and object type string.
    - 1426 occurrences with subject type neo4j_SDoH and object type string.
    - 106067 occurrences with subject type neo4j_Location and object type string.
    - 3336 occurrences with subject type neo4j_Compound and object type string.
    - 321442 occurrences with subject type neo4j_Organism and object type string.
    examples:
    - value: neo4j://graph.individuals#105029 neo4j:sources Environment Ontology
    - value: neo4j://graph.individuals#119274 neo4j:sources SNOMED CT
    - value: neo4j://graph.individuals#123229 neo4j:sources UnitedStatesZipcode_database
    - value: neo4j://graph.individuals#1961711 neo4j:sources BioCyc
    - value: neo4j://graph.individuals#105042 neo4j:sources BV-BRC
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:sources
    alias: neo4j_sources
    owner: neo4j_Organism
    domain_of:
    - neo4j_Compound
    - neo4j_Environment
    - neo4j_Location
    - neo4j_Organism
    - neo4j_SDoH
    range: string
class_uri: neo4j:Organism

```
</details>