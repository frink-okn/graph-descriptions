

# Class: Neo4jSDoH




This class occurs 1426 times.


URI: [neo4j:SDoH](neo4j://graph.schema#SDoH)






```mermaid
 classDiagram
    class Neo4jSDoH
    click Neo4jSDoH href "../Neo4jSDoH"
      Neo4jSDoH : neo4j_ASSOCIATES_SaD
        
          
    
    
    Neo4jSDoH --> "0..1" Neo4jDisease : neo4j_ASSOCIATES_SaD
    click Neo4jDisease href "../Neo4jDisease"

        
      Neo4jSDoH : neo4j_identifier
        
          
    
    
    Neo4jSDoH --> "0..1" String : neo4j_identifier
    click String href "../String"

        
      Neo4jSDoH : neo4j_ISA_SiS
        
          
    
    
    Neo4jSDoH --> "0..1" Neo4jSDoH : neo4j_ISA_SiS
    click Neo4jSDoH href "../Neo4jSDoH"

        
      Neo4jSDoH : neo4j_name
        
          
    
    
    Neo4jSDoH --> "0..1" String : neo4j_name
    click String href "../String"

        
      Neo4jSDoH : neo4j_PREVALENCEIN_SpL
        
          
    
    
    Neo4jSDoH --> "0..1" Neo4jLocation : neo4j_PREVALENCEIN_SpL
    click Neo4jLocation href "../Neo4jLocation"

        
      Neo4jSDoH : neo4j_sources
        
          
    
    
    Neo4jSDoH --> "0..1" String : neo4j_sources
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [neo4j_sources](../slots/neo4j_sources.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 1426 |
| [neo4j_ISA_SiS](../slots/neo4j_ISA_SiS.md) | 0..1 <br/> [Neo4jSDoH](../classes/Neo4jSDoH.md) |  <br/>  | direct | 999 |
| [neo4j_PREVALENCEIN_SpL](../slots/neo4j_PREVALENCEIN_SpL.md) | 0..1 <br/> [Neo4jLocation](../classes/Neo4jLocation.md) |  <br/>  | direct | 2999117 |
| [neo4j_identifier](../slots/neo4j_identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 1426 |
| [neo4j_ASSOCIATES_SaD](../slots/neo4j_ASSOCIATES_SaD.md) | 0..1 <br/> [Neo4jDisease](../classes/Neo4jDisease.md) |  <br/>  | direct | 39 |
| [neo4j_name](../slots/neo4j_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 1426 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [Neo4jSDoH](../classes/Neo4jSDoH.md) | [neo4j_ISA_SiS](../slots/neo4j_ISA_SiS.md) | range | [Neo4jSDoH](../classes/Neo4jSDoH.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: neo4j_SDoH
from_schema: okns:spoke-kg
rank: 1000
slots:
- neo4j_sources
- neo4j_ISA_SiS
- neo4j_PREVALENCEIN_SpL
- neo4j_identifier
- neo4j_ASSOCIATES_SaD
- neo4j_name
class_uri: neo4j:SDoH

```
</details>

### Induced

<details>

```yaml
name: neo4j_SDoH
from_schema: okns:spoke-kg
rank: 1000
attributes:
  neo4j_sources:
    name: neo4j_sources
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: neo4j:sources
    alias: neo4j_sources
    owner: neo4j_SDoH
    domain_of:
    - neo4j_Compound
    - neo4j_Environment
    - neo4j_Location
    - neo4j_Organism
    - neo4j_SDoH
    range: string
  neo4j_ISA_SiS:
    name: neo4j_ISA_SiS
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: neo4j:ISA_SiS
    alias: neo4j_ISA_SiS
    owner: neo4j_SDoH
    domain_of:
    - neo4j_SDoH
    range: neo4j_SDoH
  neo4j_PREVALENCEIN_SpL:
    name: neo4j_PREVALENCEIN_SpL
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: neo4j:PREVALENCEIN_SpL
    alias: neo4j_PREVALENCEIN_SpL
    owner: neo4j_SDoH
    domain_of:
    - neo4j_SDoH
    range: neo4j_Location
  neo4j_identifier:
    name: neo4j_identifier
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: neo4j:identifier
    alias: neo4j_identifier
    owner: neo4j_SDoH
    domain_of:
    - neo4j_Compound
    - neo4j_Disease
    - neo4j_Environment
    - neo4j_Location
    - neo4j_Organism
    - neo4j_SDoH
    range: string
  neo4j_ASSOCIATES_SaD:
    name: neo4j_ASSOCIATES_SaD
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: neo4j:ASSOCIATES_SaD
    alias: neo4j_ASSOCIATES_SaD
    owner: neo4j_SDoH
    domain_of:
    - neo4j_SDoH
    range: neo4j_Disease
  neo4j_name:
    name: neo4j_name
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: neo4j:name
    alias: neo4j_name
    owner: neo4j_SDoH
    domain_of:
    - neo4j_Compound
    - neo4j_Disease
    - neo4j_Environment
    - neo4j_Location
    - neo4j_Organism
    - neo4j_SDoH
    range: string
class_uri: neo4j:SDoH

```
</details>