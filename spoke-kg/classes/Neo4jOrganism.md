

# Class: Neo4jOrganism




This class occurs 321442 times.


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

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [neo4j_sources](../slots/neo4j_sources.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 321442 |
| [neo4j_identifier](../slots/neo4j_identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 321442 |
| [neo4j_RESPONDS_TO_OrC](../slots/neo4j_RESPONDS_TO_OrC.md) | 0..1 <br/> [Neo4jCompound](../classes/Neo4jCompound.md) |  <br/>  | direct | 5138 |
| [neo4j_ISOLATEDIN_OiL](../slots/neo4j_ISOLATEDIN_OiL.md) | 0..1 <br/> [Neo4jLocation](../classes/Neo4jLocation.md) |  <br/>  | direct | 321442 |
| [neo4j_name](../slots/neo4j_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 321442 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: neo4j_Organism
from_schema: okns:spoke-kg
rank: 1000
slots:
- neo4j_sources
- neo4j_identifier
- neo4j_RESPONDS_TO_OrC
- neo4j_ISOLATEDIN_OiL
- neo4j_name
class_uri: neo4j:Organism

```
</details>

### Induced

<details>

```yaml
name: neo4j_Organism
from_schema: okns:spoke-kg
rank: 1000
attributes:
  neo4j_sources:
    name: neo4j_sources
    from_schema: okns:spoke-kg
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
  neo4j_identifier:
    name: neo4j_identifier
    from_schema: okns:spoke-kg
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
  neo4j_RESPONDS_TO_OrC:
    name: neo4j_RESPONDS_TO_OrC
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: neo4j:RESPONDS_TO_OrC
    alias: neo4j_RESPONDS_TO_OrC
    owner: neo4j_Organism
    domain_of:
    - neo4j_Organism
    range: neo4j_Compound
  neo4j_ISOLATEDIN_OiL:
    name: neo4j_ISOLATEDIN_OiL
    from_schema: okns:spoke-kg
    rank: 1000
    slot_uri: neo4j:ISOLATEDIN_OiL
    alias: neo4j_ISOLATEDIN_OiL
    owner: neo4j_Organism
    domain_of:
    - neo4j_Organism
    range: neo4j_Location
  neo4j_name:
    name: neo4j_name
    from_schema: okns:spoke-kg
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
class_uri: neo4j:Organism

```
</details>