

# Class: HttpId.nlm.nih.govMeshVocab#TreeNumber




This class occurs 80096 times.


URI: [http://id.nlm.nih.gov/mesh/vocab#TreeNumber](http://id.nlm.nih.gov/mesh/vocab#TreeNumber)






```mermaid
 classDiagram
    class HttpId.nlm.nih.govMeshVocab#TreeNumber
    click HttpId.nlm.nih.govMeshVocab#TreeNumber href "../HttpId.nlm.nih.govMeshVocab#TreeNumber"
      HttpId.nlm.nih.govMeshVocab#TreeNumber : http___id.nlm.nih.gov_mesh_vocab#active
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#TreeNumber --> "0..1" Boolean : http___id.nlm.nih.gov_mesh_vocab#active
    click Boolean href "../Boolean"

        
      HttpId.nlm.nih.govMeshVocab#TreeNumber : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#TreeNumber --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#TreeNumber : http___id.nlm.nih.gov_mesh_vocab#parentTreeNumber
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#TreeNumber --> "0..1" HttpId.nlm.nih.govMeshVocab#TreeNumber : http___id.nlm.nih.gov_mesh_vocab#parentTreeNumber
    click HttpId.nlm.nih.govMeshVocab#TreeNumber href "../HttpId.nlm.nih.govMeshVocab#TreeNumber"

        
      HttpId.nlm.nih.govMeshVocab#TreeNumber : rdfs_label
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#TreeNumber --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___id.nlm.nih.gov_mesh_vocab#parentTreeNumber](../slots/http___id.nlm.nih.gov_mesh_vocab#parentTreeNumber.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#TreeNumber](../classes/HttpId.nlm.nih.govMeshVocab#TreeNumber.md) |  <br/>  | direct | 79955 |
| [http___id.nlm.nih.gov_mesh_vocab#lastActiveYear](../slots/http___id.nlm.nih.gov_mesh_vocab#lastActiveYear.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 16951 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 80096 |
| [http___id.nlm.nih.gov_mesh_vocab#active](../slots/http___id.nlm.nih.gov_mesh_vocab#active.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) |  <br/>  | direct | 80096 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor.md) | [http___id.nlm.nih.gov_mesh_vocab#treeNumber](../slots/http___id.nlm.nih.gov_mesh_vocab#treeNumber.md) | range | [HttpId.nlm.nih.govMeshVocab#TreeNumber](../classes/HttpId.nlm.nih.govMeshVocab#TreeNumber.md) |
| [HttpId.nlm.nih.govMeshVocab#PublicationType](../classes/HttpId.nlm.nih.govMeshVocab#PublicationType.md) | [http___id.nlm.nih.gov_mesh_vocab#treeNumber](../slots/http___id.nlm.nih.gov_mesh_vocab#treeNumber.md) | range | [HttpId.nlm.nih.govMeshVocab#TreeNumber](../classes/HttpId.nlm.nih.govMeshVocab#TreeNumber.md) |
| [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) | [http___id.nlm.nih.gov_mesh_vocab#treeNumber](../slots/http___id.nlm.nih.gov_mesh_vocab#treeNumber.md) | range | [HttpId.nlm.nih.govMeshVocab#TreeNumber](../classes/HttpId.nlm.nih.govMeshVocab#TreeNumber.md) |
| [HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md) | [http___id.nlm.nih.gov_mesh_vocab#treeNumber](../slots/http___id.nlm.nih.gov_mesh_vocab#treeNumber.md) | range | [HttpId.nlm.nih.govMeshVocab#TreeNumber](../classes/HttpId.nlm.nih.govMeshVocab#TreeNumber.md) |
| [HttpId.nlm.nih.govMeshVocab#TreeNumber](../classes/HttpId.nlm.nih.govMeshVocab#TreeNumber.md) | [http___id.nlm.nih.gov_mesh_vocab#parentTreeNumber](../slots/http___id.nlm.nih.gov_mesh_vocab#parentTreeNumber.md) | range | [HttpId.nlm.nih.govMeshVocab#TreeNumber](../classes/HttpId.nlm.nih.govMeshVocab#TreeNumber.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#TreeNumber
from_schema: okns:biobricks-mesh-kg
rank: 1000
slots:
- http___id.nlm.nih.gov_mesh_vocab#parentTreeNumber
- http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
- rdfs_label
- http___id.nlm.nih.gov_mesh_vocab#active
class_uri: http://id.nlm.nih.gov/mesh/vocab#TreeNumber

```
</details>

### Induced

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#TreeNumber
from_schema: okns:biobricks-mesh-kg
rank: 1000
attributes:
  http___id.nlm.nih.gov_mesh_vocab#parentTreeNumber:
    name: http___id.nlm.nih.gov_mesh_vocab#parentTreeNumber
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#parentTreeNumber
    alias: http___id.nlm.nih.gov_mesh_vocab#parentTreeNumber
    owner: http___id.nlm.nih.gov_mesh_vocab#TreeNumber
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#TreeNumber
    range: http___id.nlm.nih.gov_mesh_vocab#TreeNumber
  http___id.nlm.nih.gov_mesh_vocab#lastActiveYear:
    name: http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#lastActiveYear
    alias: http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    owner: http___id.nlm.nih.gov_mesh_vocab#TreeNumber
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    - http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    - http___id.nlm.nih.gov_mesh_vocab#Term
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#TreeNumber
    range: string
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___id.nlm.nih.gov_mesh_vocab#TreeNumber
    domain_of:
    - rdf_List
    - rdfs_Datatype
    - http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
    - http___id.nlm.nih.gov_mesh_vocab#CheckTag
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    - http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#PublicationType
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Population
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#TreeNumber
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
  http___id.nlm.nih.gov_mesh_vocab#active:
    name: http___id.nlm.nih.gov_mesh_vocab#active
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#active
    alias: http___id.nlm.nih.gov_mesh_vocab#active
    owner: http___id.nlm.nih.gov_mesh_vocab#TreeNumber
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
    - http___id.nlm.nih.gov_mesh_vocab#CheckTag
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    - http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#PublicationType
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Population
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    - http___id.nlm.nih.gov_mesh_vocab#Term
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#TreeNumber
    range: boolean
class_uri: http://id.nlm.nih.gov/mesh/vocab#TreeNumber

```
</details>