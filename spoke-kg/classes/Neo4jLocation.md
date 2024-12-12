

# Class: TODO -- what's a good name for this class (type)? (neo4j_Location)


_No type description provided_





URI: [neo4j:Location](neo4j://graph.schema#Location)






```mermaid
 classDiagram
    class Neo4jLocation
    click Neo4jLocation href "../Neo4jLocation"
      Neo4jLocation : neo4j_identifier
        
          
    
    
    Neo4jLocation --> "0..1" String : neo4j_identifier
    click String href "../String"

        
      Neo4jLocation : neo4j_name
        
          
    
    
    Neo4jLocation --> "0..1" String : neo4j_name
    click String href "../String"

        
      Neo4jLocation : neo4j_PARTOF_LpL
        
          
    
    
    Neo4jLocation --> "0..1" Neo4jLocation : neo4j_PARTOF_LpL
    click Neo4jLocation href "../Neo4jLocation"

        
      Neo4jLocation : neo4j_sources
        
          
    
    
    Neo4jLocation --> "0..1" String : neo4j_sources
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [neo4j_name](../slots/neo4j_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [neo4j_PARTOF_LpL](../slots/neo4j_PARTOF_LpL.md) | 0..1 <br/> [Neo4jLocation](../classes/Neo4jLocation.md) | No slot description provided | direct |
| [neo4j_identifier](../slots/neo4j_identifier.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [neo4j_sources](../slots/neo4j_sources.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Neo4jCompound](../classes/Neo4jCompound.md) | [neo4j_FOUNDIN_CfL](../slots/neo4j_FOUNDIN_CfL.md) | range | [Neo4jLocation](../classes/Neo4jLocation.md) |
| [Neo4jDisease](../classes/Neo4jDisease.md) | [neo4j_MORTALITY_DmL](../slots/neo4j_MORTALITY_DmL.md) | range | [Neo4jLocation](../classes/Neo4jLocation.md) |
| [Neo4jDisease](../classes/Neo4jDisease.md) | [neo4j_PREVALENCE_DpL](../slots/neo4j_PREVALENCE_DpL.md) | range | [Neo4jLocation](../classes/Neo4jLocation.md) |
| [Neo4jEnvironment](../classes/Neo4jEnvironment.md) | [neo4j_FOUNDIN_EfL](../slots/neo4j_FOUNDIN_EfL.md) | range | [Neo4jLocation](../classes/Neo4jLocation.md) |
| [Neo4jLocation](../classes/Neo4jLocation.md) | [neo4j_PARTOF_LpL](../slots/neo4j_PARTOF_LpL.md) | range | [Neo4jLocation](../classes/Neo4jLocation.md) |
| [Neo4jOrganism](../classes/Neo4jOrganism.md) | [neo4j_ISOLATEDIN_OiL](../slots/neo4j_ISOLATEDIN_OiL.md) | range | [Neo4jLocation](../classes/Neo4jLocation.md) |
| [Neo4jSDoH](../classes/Neo4jSDoH.md) | [neo4j_PREVALENCEIN_SpL](../slots/neo4j_PREVALENCEIN_SpL.md) | range | [Neo4jLocation](../classes/Neo4jLocation.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#123229 |

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
| self | neo4j:Location |
| native | spoke-kg/:Neo4jLocation |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: neo4j_Location
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 106067 occurences.
examples:
- value: neo4j://graph.individuals#123229
from_schema: spoke-kg
rank: 1000
slots:
- neo4j_name
- neo4j_PARTOF_LpL
- neo4j_identifier
- neo4j_sources
class_uri: neo4j:Location

```
</details>

### Induced

<details>
```yaml
name: neo4j_Location
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 106067 occurences.
examples:
- value: neo4j://graph.individuals#123229
from_schema: spoke-kg
rank: 1000
attributes:
  neo4j_name:
    name: neo4j_name
    description: No slot description provided
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
    owner: neo4j_Location
    domain_of:
    - neo4j_Compound
    - neo4j_Disease
    - neo4j_Environment
    - neo4j_Location
    - neo4j_Organism
    - neo4j_SDoH
    range: string
  neo4j_PARTOF_LpL:
    name: neo4j_PARTOF_LpL
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 119810 occurrences with subject type neo4j_Location and object type neo4j_Location.
    examples:
    - value: neo4j://graph.individuals#84571 neo4j:PARTOF_LpL neo4j://graph.individuals#80740
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:PARTOF_LpL
    alias: neo4j_PARTOF_LpL
    owner: neo4j_Location
    domain_of:
    - neo4j_Location
    range: neo4j_Location
  neo4j_identifier:
    name: neo4j_identifier
    description: No slot description provided
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
    owner: neo4j_Location
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
    description: No slot description provided
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
    owner: neo4j_Location
    domain_of:
    - neo4j_Compound
    - neo4j_Environment
    - neo4j_Location
    - neo4j_Organism
    - neo4j_SDoH
    range: string
class_uri: neo4j:Location

```
</details>