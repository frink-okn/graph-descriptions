

# Class: No class name specified (neo4j_Organism)


_No class (type) description specified_





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
| [neo4j_name](../slots/neo4j_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 2 occurrences with subject type neo4j_Environment and object type string.<br/>1426 occurrences with subject type neo4j_SDoH and object type string.<br/>106067 occurrences with subject type neo4j_Location and object type string.<br/>180 occurrences with subject type neo4j_Disease and object type string.<br/>798 occurrences with subject type neo4j_Compound and object type string.<br/>321442 occurrences with subject type neo4j_Organism and object type string. | direct |
| [neo4j_RESPONDS_TO_OrC](../slots/neo4j_RESPONDS_TO_OrC.md) | 0..1 <br/> [Neo4jCompound](../classes/Neo4jCompound.md) | No slot (predicate) description specified <br/> 5138 occurrences with subject type neo4j_Organism and object type neo4j_Compound. | direct |
| [neo4j_identifier](../slots/neo4j_identifier.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 2 occurrences with subject type neo4j_Environment and object type string.<br/>1426 occurrences with subject type neo4j_SDoH and object type string.<br/>106067 occurrences with subject type neo4j_Location and object type string.<br/>180 occurrences with subject type neo4j_Disease and object type string.<br/>798 occurrences with subject type neo4j_Compound and object type string.<br/>321442 occurrences with subject type neo4j_Organism and object type string. | direct |
| [neo4j_sources](../slots/neo4j_sources.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 2 occurrences with subject type neo4j_Environment and object type string.<br/>1426 occurrences with subject type neo4j_SDoH and object type string.<br/>106067 occurrences with subject type neo4j_Location and object type string.<br/>3336 occurrences with subject type neo4j_Compound and object type string.<br/>321442 occurrences with subject type neo4j_Organism and object type string. | direct |
| [neo4j_ISOLATEDIN_OiL](../slots/neo4j_ISOLATEDIN_OiL.md) | 0..1 <br/> [Neo4jLocation](../classes/Neo4jLocation.md) | No slot (predicate) description specified <br/> 321442 occurrences with subject type neo4j_Organism and object type neo4j_Location. | direct |










## Examples

| Value |
| --- |
| neo4j://graph.individuals#105042 |


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
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class name specified
notes:
- Class with 321442 occurrences.
examples:
- value: neo4j://graph.individuals#105042
from_schema: spoke-kg
rank: 1000
slots:
- neo4j_name
- neo4j_RESPONDS_TO_OrC
- neo4j_identifier
- neo4j_sources
- neo4j_ISOLATEDIN_OiL
class_uri: neo4j:Organism

```
</details>

### Induced

<details>
```yaml
name: neo4j_Organism
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class name specified
notes:
- Class with 321442 occurrences.
examples:
- value: neo4j://graph.individuals#105042
from_schema: spoke-kg
rank: 1000
attributes:
  neo4j_name:
    name: neo4j_name
    description: No slot (predicate) description specified
    comments:
    - 2 occurrences with subject type neo4j_Environment and object type string.
    - 1426 occurrences with subject type neo4j_SDoH and object type string.
    - 106067 occurrences with subject type neo4j_Location and object type string.
    - 180 occurrences with subject type neo4j_Disease and object type string.
    - 798 occurrences with subject type neo4j_Compound and object type string.
    - 321442 occurrences with subject type neo4j_Organism and object type string.
    examples:
    - description: neo4j_Environment → string
      object:
        example_object: respirable suspended particulate matter
        example_predicate: neo4j:name
        example_subject: neo4j://graph.individuals#105029
    - description: neo4j_SDoH → string
      object:
        example_object: Social scientist (occupation)
        example_predicate: neo4j:name
        example_subject: neo4j://graph.individuals#119274
    - description: neo4j_Location → string
      object:
        example_object: Outside city limits
        example_predicate: neo4j:name
        example_subject: neo4j://graph.individuals#123229
    - description: neo4j_Disease → string
      object:
        example_object: giant cell glioblastoma
        example_predicate: neo4j:name
        example_subject: neo4j://graph.individuals#142359
    - description: neo4j_Compound → string
      object:
        example_object: Tetracycline
        example_predicate: neo4j:name
        example_subject: neo4j://graph.individuals#1961711
    - description: neo4j_Organism → string
      object:
        example_object: Acetobacter tropicalis strain DmPark25_167
        example_predicate: neo4j:name
        example_subject: neo4j://graph.individuals#105042
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
  neo4j_RESPONDS_TO_OrC:
    name: neo4j_RESPONDS_TO_OrC
    description: No slot (predicate) description specified
    comments:
    - 5138 occurrences with subject type neo4j_Organism and object type neo4j_Compound.
    examples:
    - description: neo4j_Organism → neo4j_Compound
      object:
        example_object: neo4j://graph.individuals#1961711
        example_predicate: neo4j:RESPONDS_TO_OrC
        example_subject: neo4j://graph.individuals#31108418
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
    description: No slot (predicate) description specified
    comments:
    - 2 occurrences with subject type neo4j_Environment and object type string.
    - 1426 occurrences with subject type neo4j_SDoH and object type string.
    - 106067 occurrences with subject type neo4j_Location and object type string.
    - 180 occurrences with subject type neo4j_Disease and object type string.
    - 798 occurrences with subject type neo4j_Compound and object type string.
    - 321442 occurrences with subject type neo4j_Organism and object type string.
    examples:
    - description: neo4j_Environment → string
      object:
        example_object: ENVO_01000405
        example_predicate: neo4j:identifier
        example_subject: neo4j://graph.individuals#105029
    - description: neo4j_SDoH → string
      object:
        example_object: '158928002'
        example_predicate: neo4j:identifier
        example_subject: neo4j://graph.individuals#119274
    - description: neo4j_Location → string
      object:
        example_object: 049999985379
        example_predicate: neo4j:identifier
        example_subject: neo4j://graph.individuals#123229
    - description: neo4j_Disease → string
      object:
        example_object: DOID:3074
        example_predicate: neo4j:identifier
        example_subject: neo4j://graph.individuals#142359
    - description: neo4j_Compound → string
      object:
        example_object: inchikey:NWXMGUDVXFXRIG-WESIUVDSSA-N
        example_predicate: neo4j:identifier
        example_subject: neo4j://graph.individuals#1961711
    - description: neo4j_Organism → string
      object:
        example_object: '104102.36'
        example_predicate: neo4j:identifier
        example_subject: neo4j://graph.individuals#105042
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
  neo4j_sources:
    name: neo4j_sources
    description: No slot (predicate) description specified
    comments:
    - 2 occurrences with subject type neo4j_Environment and object type string.
    - 1426 occurrences with subject type neo4j_SDoH and object type string.
    - 106067 occurrences with subject type neo4j_Location and object type string.
    - 3336 occurrences with subject type neo4j_Compound and object type string.
    - 321442 occurrences with subject type neo4j_Organism and object type string.
    examples:
    - description: neo4j_Environment → string
      object:
        example_object: Environment Ontology
        example_predicate: neo4j:sources
        example_subject: neo4j://graph.individuals#105029
    - description: neo4j_SDoH → string
      object:
        example_object: SNOMED CT
        example_predicate: neo4j:sources
        example_subject: neo4j://graph.individuals#119274
    - description: neo4j_Location → string
      object:
        example_object: UnitedStatesZipcode_database
        example_predicate: neo4j:sources
        example_subject: neo4j://graph.individuals#123229
    - description: neo4j_Compound → string
      object:
        example_object: BioCyc
        example_predicate: neo4j:sources
        example_subject: neo4j://graph.individuals#1961711
    - description: neo4j_Organism → string
      object:
        example_object: BV-BRC
        example_predicate: neo4j:sources
        example_subject: neo4j://graph.individuals#105042
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
  neo4j_ISOLATEDIN_OiL:
    name: neo4j_ISOLATEDIN_OiL
    description: No slot (predicate) description specified
    comments:
    - 321442 occurrences with subject type neo4j_Organism and object type neo4j_Location.
    examples:
    - description: neo4j_Organism → neo4j_Location
      object:
        example_object: neo4j://graph.individuals#80505
        example_predicate: neo4j:ISOLATEDIN_OiL
        example_subject: neo4j://graph.individuals#38641
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:ISOLATEDIN_OiL
    alias: neo4j_ISOLATEDIN_OiL
    owner: neo4j_Organism
    domain_of:
    - neo4j_Organism
    range: neo4j_Location
class_uri: neo4j:Organism

```
</details>