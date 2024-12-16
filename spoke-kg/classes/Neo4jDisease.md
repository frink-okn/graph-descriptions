

# Class: No class name specified (neo4j_Disease)


_No class (type) description specified_





URI: [neo4j:Disease](neo4j://graph.schema#Disease)






```mermaid
 classDiagram
    class Neo4jDisease
    click Neo4jDisease href "../Neo4jDisease"
      Neo4jDisease : neo4j_identifier
        
          
    
    
    Neo4jDisease --> "0..1" String : neo4j_identifier
    click String href "../String"

        
      Neo4jDisease : neo4j_ISA_DiD
        
          
    
    
    Neo4jDisease --> "0..1" Neo4jDisease : neo4j_ISA_DiD
    click Neo4jDisease href "../Neo4jDisease"

        
      Neo4jDisease : neo4j_MORTALITY_DmL
        
          
    
    
    Neo4jDisease --> "0..1" Neo4jLocation : neo4j_MORTALITY_DmL
    click Neo4jLocation href "../Neo4jLocation"

        
      Neo4jDisease : neo4j_name
        
          
    
    
    Neo4jDisease --> "0..1" String : neo4j_name
    click String href "../String"

        
      Neo4jDisease : neo4j_PREVALENCE_DpL
        
          
    
    
    Neo4jDisease --> "0..1" Neo4jLocation : neo4j_PREVALENCE_DpL
    click Neo4jLocation href "../Neo4jLocation"

        
      Neo4jDisease : neo4j_RESEMBLES_DrD
        
          
    
    
    Neo4jDisease --> "0..1" Neo4jDisease : neo4j_RESEMBLES_DrD
    click Neo4jDisease href "../Neo4jDisease"

        
      Neo4jDisease : neo4j_source
        
          
    
    
    Neo4jDisease --> "0..1" String : neo4j_source
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [neo4j_name](../slots/neo4j_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 2 occurrences with subject type neo4j_Environment and object type string.<br/>1426 occurrences with subject type neo4j_SDoH and object type string.<br/>106067 occurrences with subject type neo4j_Location and object type string.<br/>180 occurrences with subject type neo4j_Disease and object type string.<br/>798 occurrences with subject type neo4j_Compound and object type string.<br/>321442 occurrences with subject type neo4j_Organism and object type string. | direct |
| [neo4j_MORTALITY_DmL](../slots/neo4j_MORTALITY_DmL.md) | 0..1 <br/> [Neo4jLocation](../classes/Neo4jLocation.md) | No slot (predicate) description specified <br/> 10802 occurrences with subject type neo4j_Disease and object type neo4j_Location. | direct |
| [neo4j_ISA_DiD](../slots/neo4j_ISA_DiD.md) | 0..1 <br/> [Neo4jDisease](../classes/Neo4jDisease.md) | No slot (predicate) description specified <br/> 41 occurrences with subject type neo4j_Disease and object type neo4j_Disease. | direct |
| [neo4j_RESEMBLES_DrD](../slots/neo4j_RESEMBLES_DrD.md) | 0..1 <br/> [Neo4jDisease](../classes/Neo4jDisease.md) | No slot (predicate) description specified <br/> 67 occurrences with subject type neo4j_Disease and object type neo4j_Disease. | direct |
| [neo4j_PREVALENCE_DpL](../slots/neo4j_PREVALENCE_DpL.md) | 0..1 <br/> [Neo4jLocation](../classes/Neo4jLocation.md) | No slot (predicate) description specified <br/> 275085 occurrences with subject type neo4j_Disease and object type neo4j_Location. | direct |
| [neo4j_identifier](../slots/neo4j_identifier.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 2 occurrences with subject type neo4j_Environment and object type string.<br/>1426 occurrences with subject type neo4j_SDoH and object type string.<br/>106067 occurrences with subject type neo4j_Location and object type string.<br/>180 occurrences with subject type neo4j_Disease and object type string.<br/>798 occurrences with subject type neo4j_Compound and object type string.<br/>321442 occurrences with subject type neo4j_Organism and object type string. | direct |
| [neo4j_source](../slots/neo4j_source.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 180 occurrences with subject type neo4j_Disease and object type string. | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Neo4jCompound](../classes/Neo4jCompound.md) | [neo4j_CONTRAINDICATES_CcD](../slots/neo4j_CONTRAINDICATES_CcD.md) | range | [Neo4jDisease](../classes/Neo4jDisease.md) |
| [Neo4jCompound](../classes/Neo4jCompound.md) | [neo4j_TREATS_CtD](../slots/neo4j_TREATS_CtD.md) | range | [Neo4jDisease](../classes/Neo4jDisease.md) |
| [Neo4jDisease](../classes/Neo4jDisease.md) | [neo4j_ISA_DiD](../slots/neo4j_ISA_DiD.md) | range | [Neo4jDisease](../classes/Neo4jDisease.md) |
| [Neo4jDisease](../classes/Neo4jDisease.md) | [neo4j_RESEMBLES_DrD](../slots/neo4j_RESEMBLES_DrD.md) | range | [Neo4jDisease](../classes/Neo4jDisease.md) |
| [Neo4jSDoH](../classes/Neo4jSDoH.md) | [neo4j_ASSOCIATES_SaD](../slots/neo4j_ASSOCIATES_SaD.md) | range | [Neo4jDisease](../classes/Neo4jDisease.md) |







## Examples

| Value |
| --- |
| neo4j://graph.individuals#142359 |


## Identifier and Mapping Information







### Schema Source


* from schema: spoke-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | neo4j:Disease |
| native | spoke-kg/:Neo4jDisease |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: neo4j_Disease
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class name specified
notes:
- Class with 180 occurrences.
examples:
- value: neo4j://graph.individuals#142359
from_schema: spoke-kg
rank: 1000
slots:
- neo4j_name
- neo4j_MORTALITY_DmL
- neo4j_ISA_DiD
- neo4j_RESEMBLES_DrD
- neo4j_PREVALENCE_DpL
- neo4j_identifier
- neo4j_source
class_uri: neo4j:Disease

```
</details>

### Induced

<details>
```yaml
name: neo4j_Disease
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class name specified
notes:
- Class with 180 occurrences.
examples:
- value: neo4j://graph.individuals#142359
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
    owner: neo4j_Disease
    domain_of:
    - neo4j_Compound
    - neo4j_Disease
    - neo4j_Environment
    - neo4j_Location
    - neo4j_Organism
    - neo4j_SDoH
    range: string
  neo4j_MORTALITY_DmL:
    name: neo4j_MORTALITY_DmL
    description: No slot (predicate) description specified
    comments:
    - 10802 occurrences with subject type neo4j_Disease and object type neo4j_Location.
    examples:
    - description: neo4j_Disease → neo4j_Location
      object:
        example_object: neo4j://graph.individuals#80756
        example_predicate: neo4j:MORTALITY_DmL
        example_subject: neo4j://graph.individuals#152579
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:MORTALITY_DmL
    alias: neo4j_MORTALITY_DmL
    owner: neo4j_Disease
    domain_of:
    - neo4j_Disease
    range: neo4j_Location
  neo4j_ISA_DiD:
    name: neo4j_ISA_DiD
    description: No slot (predicate) description specified
    comments:
    - 41 occurrences with subject type neo4j_Disease and object type neo4j_Disease.
    examples:
    - description: neo4j_Disease → neo4j_Disease
      object:
        example_object: neo4j://graph.individuals#152053
        example_predicate: neo4j:ISA_DiD
        example_subject: neo4j://graph.individuals#152421
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:ISA_DiD
    alias: neo4j_ISA_DiD
    owner: neo4j_Disease
    domain_of:
    - neo4j_Disease
    range: neo4j_Disease
  neo4j_RESEMBLES_DrD:
    name: neo4j_RESEMBLES_DrD
    description: No slot (predicate) description specified
    comments:
    - 67 occurrences with subject type neo4j_Disease and object type neo4j_Disease.
    examples:
    - description: neo4j_Disease → neo4j_Disease
      object:
        example_object: neo4j://graph.individuals#144201
        example_predicate: neo4j:RESEMBLES_DrD
        example_subject: neo4j://graph.individuals#152554
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:RESEMBLES_DrD
    alias: neo4j_RESEMBLES_DrD
    owner: neo4j_Disease
    domain_of:
    - neo4j_Disease
    range: neo4j_Disease
  neo4j_PREVALENCE_DpL:
    name: neo4j_PREVALENCE_DpL
    description: No slot (predicate) description specified
    comments:
    - 275085 occurrences with subject type neo4j_Disease and object type neo4j_Location.
    examples:
    - description: neo4j_Disease → neo4j_Location
      object:
        example_object: neo4j://graph.individuals#80756
        example_predicate: neo4j:PREVALENCE_DpL
        example_subject: neo4j://graph.individuals#153323
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:PREVALENCE_DpL
    alias: neo4j_PREVALENCE_DpL
    owner: neo4j_Disease
    domain_of:
    - neo4j_Disease
    range: neo4j_Location
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
    owner: neo4j_Disease
    domain_of:
    - neo4j_Compound
    - neo4j_Disease
    - neo4j_Environment
    - neo4j_Location
    - neo4j_Organism
    - neo4j_SDoH
    range: string
  neo4j_source:
    name: neo4j_source
    description: No slot (predicate) description specified
    comments:
    - 180 occurrences with subject type neo4j_Disease and object type string.
    examples:
    - description: neo4j_Disease → string
      object:
        example_object: Disease Ontology
        example_predicate: neo4j:source
        example_subject: neo4j://graph.individuals#142359
    from_schema: spoke-kg
    rank: 1000
    slot_uri: neo4j:source
    alias: neo4j_source
    owner: neo4j_Disease
    domain_of:
    - neo4j_Disease
    range: string
class_uri: neo4j:Disease

```
</details>