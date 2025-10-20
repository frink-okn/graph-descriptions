

# Class: HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair




This class occurs 1032 times.


URI: [http://id.nlm.nih.gov/mesh/vocab#DisallowedDescriptorQualifierPair](http://id.nlm.nih.gov/mesh/vocab#DisallowedDescriptorQualifierPair)






```mermaid
 classDiagram
    class HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair
    click HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair href "../HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair"
      HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair : http___id.nlm.nih.gov_mesh_vocab#active
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair --> "0..1" Boolean : http___id.nlm.nih.gov_mesh_vocab#active
    click Boolean href "../Boolean"

        
      HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair : http___id.nlm.nih.gov_mesh_vocab#hasDescriptor
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair --> "0..1" Any : http___id.nlm.nih.gov_mesh_vocab#hasDescriptor
    click Any href "../Any"

        
      HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair : http___id.nlm.nih.gov_mesh_vocab#hasQualifier
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair --> "0..1" HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#hasQualifier
    click HttpId.nlm.nih.govMeshVocab#Qualifier href "../HttpId.nlm.nih.govMeshVocab#Qualifier"

        
      HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair : http___id.nlm.nih.gov_mesh_vocab#useInstead
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair --> "0..1" Any : http___id.nlm.nih.gov_mesh_vocab#useInstead
    click Any href "../Any"

        
      HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair : rdfs_label
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___id.nlm.nih.gov_mesh_vocab#lastActiveYear](../slots/http___id.nlm.nih.gov_mesh_vocab#lastActiveYear.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 47 |
| [http___id.nlm.nih.gov_mesh_vocab#hasQualifier](../slots/http___id.nlm.nih.gov_mesh_vocab#hasQualifier.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) |  <br/>  | direct | 1032 |
| [http___id.nlm.nih.gov_mesh_vocab#active](../slots/http___id.nlm.nih.gov_mesh_vocab#active.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) |  <br/>  | direct | 1032 |
| [http___id.nlm.nih.gov_mesh_vocab#useInstead](../slots/http___id.nlm.nih.gov_mesh_vocab#useInstead.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md) |  <br/>  | direct | 1032 |
| [http___id.nlm.nih.gov_mesh_vocab#hasDescriptor](../slots/http___id.nlm.nih.gov_mesh_vocab#hasDescriptor.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md) |  <br/>  | direct | 1032 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 1029 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) | [http___id.nlm.nih.gov_mesh_vocab#useInstead](../slots/http___id.nlm.nih.gov_mesh_vocab#useInstead.md) | any_of[range] | [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRChemical](../classes/HttpId.nlm.nih.govMeshVocab#SCRChemical.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo.md) | any_of[range] | [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRChemical](../classes/HttpId.nlm.nih.govMeshVocab#SCRChemical.md) | [http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso](../slots/http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso.md) | any_of[range] | [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRDisease](../classes/HttpId.nlm.nih.govMeshVocab#SCRDisease.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo.md) | any_of[range] | [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRDisease](../classes/HttpId.nlm.nih.govMeshVocab#SCRDisease.md) | [http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso](../slots/http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso.md) | any_of[range] | [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |
| [HttpId.nlm.nih.govMeshVocab#SCROrganism](../classes/HttpId.nlm.nih.govMeshVocab#SCROrganism.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo.md) | any_of[range] | [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |
| [HttpId.nlm.nih.govMeshVocab#SCROrganism](../classes/HttpId.nlm.nih.govMeshVocab#SCROrganism.md) | [http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso](../slots/http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso.md) | any_of[range] | [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRPopulation](../classes/HttpId.nlm.nih.govMeshVocab#SCRPopulation.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo.md) | any_of[range] | [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRProtocol](../classes/HttpId.nlm.nih.govMeshVocab#SCRProtocol.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo.md) | any_of[range] | [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRProtocol](../classes/HttpId.nlm.nih.govMeshVocab#SCRProtocol.md) | [http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso](../slots/http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso.md) | any_of[range] | [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
from_schema: okns:biobricks-mesh-kg
rank: 1000
slots:
- http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
- http___id.nlm.nih.gov_mesh_vocab#hasQualifier
- http___id.nlm.nih.gov_mesh_vocab#active
- http___id.nlm.nih.gov_mesh_vocab#useInstead
- http___id.nlm.nih.gov_mesh_vocab#hasDescriptor
- rdfs_label
class_uri: http://id.nlm.nih.gov/mesh/vocab#DisallowedDescriptorQualifierPair

```
</details>

### Induced

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
from_schema: okns:biobricks-mesh-kg
rank: 1000
attributes:
  http___id.nlm.nih.gov_mesh_vocab#lastActiveYear:
    name: http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#lastActiveYear
    alias: http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    owner: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
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
  http___id.nlm.nih.gov_mesh_vocab#hasQualifier:
    name: http___id.nlm.nih.gov_mesh_vocab#hasQualifier
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#hasQualifier
    alias: http___id.nlm.nih.gov_mesh_vocab#hasQualifier
    owner: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
    - http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    range: http___id.nlm.nih.gov_mesh_vocab#Qualifier
  http___id.nlm.nih.gov_mesh_vocab#active:
    name: http___id.nlm.nih.gov_mesh_vocab#active
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#active
    alias: http___id.nlm.nih.gov_mesh_vocab#active
    owner: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
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
  http___id.nlm.nih.gov_mesh_vocab#useInstead:
    name: http___id.nlm.nih.gov_mesh_vocab#useInstead
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#useInstead
    alias: http___id.nlm.nih.gov_mesh_vocab#useInstead
    owner: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    range: Any
    any_of:
    - range: http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
    - range: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    - range: http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
  http___id.nlm.nih.gov_mesh_vocab#hasDescriptor:
    name: http___id.nlm.nih.gov_mesh_vocab#hasDescriptor
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#hasDescriptor
    alias: http___id.nlm.nih.gov_mesh_vocab#hasDescriptor
    owner: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
    - http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    range: Any
    any_of:
    - range: http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - range: http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
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
class_uri: http://id.nlm.nih.gov/mesh/vocab#DisallowedDescriptorQualifierPair

```
</details>