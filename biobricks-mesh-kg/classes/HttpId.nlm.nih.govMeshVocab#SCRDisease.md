

# Class: HttpId.nlm.nih.govMeshVocab#SCRDisease




This class occurs 6750 times.


URI: [http://id.nlm.nih.gov/mesh/vocab#SCR_Disease](http://id.nlm.nih.gov/mesh/vocab#SCR_Disease)






```mermaid
 classDiagram
    class HttpId.nlm.nih.govMeshVocab#SCRDisease
    click HttpId.nlm.nih.govMeshVocab#SCRDisease href "../HttpId.nlm.nih.govMeshVocab#SCRDisease"
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#active
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" Boolean : http___id.nlm.nih.gov_mesh_vocab#active
    click Boolean href "../Boolean"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#concept
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#concept
    click HttpId.nlm.nih.govMeshVocab#Concept href "../HttpId.nlm.nih.govMeshVocab#Concept"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#dateCreated
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" Date : http___id.nlm.nih.gov_mesh_vocab#dateCreated
    click Date href "../Date"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#dateRevised
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" Date : http___id.nlm.nih.gov_mesh_vocab#dateRevised
    click Date href "../Date"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#frequency
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" Int32 : http___id.nlm.nih.gov_mesh_vocab#frequency
    click Int32 href "../Int32"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#identifier
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#identifier
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" Any : http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso
    click Any href "../Any"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#mappedTo
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" Any : http___id.nlm.nih.gov_mesh_vocab#mappedTo
    click Any href "../Any"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#note
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#note
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#preferredConcept
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#preferredConcept
    click HttpId.nlm.nih.govMeshVocab#Concept href "../HttpId.nlm.nih.govMeshVocab#Concept"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" Any : http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo
    click Any href "../Any"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#preferredTerm
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#preferredTerm
    click HttpId.nlm.nih.govMeshVocab#Term href "../HttpId.nlm.nih.govMeshVocab#Term"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#previousIndexing
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#previousIndexing
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : http___id.nlm.nih.gov_mesh_vocab#source
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#source
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#SCRDisease : rdfs_label
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#SCRDisease --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___id.nlm.nih.gov_mesh_vocab#dateCreated](../slots/http___id.nlm.nih.gov_mesh_vocab#dateCreated.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 6750 |
| [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |  <br/>  | direct | 6750 |
| [http___id.nlm.nih.gov_mesh_vocab#lastActiveYear](../slots/http___id.nlm.nih.gov_mesh_vocab#lastActiveYear.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 214 |
| [http___id.nlm.nih.gov_mesh_vocab#concept](../slots/http___id.nlm.nih.gov_mesh_vocab#concept.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |  <br/>  | direct | 601 |
| [http___id.nlm.nih.gov_mesh_vocab#dateRevised](../slots/http___id.nlm.nih.gov_mesh_vocab#dateRevised.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 3814 |
| [http___id.nlm.nih.gov_mesh_vocab#identifier](../slots/http___id.nlm.nih.gov_mesh_vocab#identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 6750 |
| [http___id.nlm.nih.gov_mesh_vocab#source](../slots/http___id.nlm.nih.gov_mesh_vocab#source.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 97 |
| [http___id.nlm.nih.gov_mesh_vocab#frequency](../slots/http___id.nlm.nih.gov_mesh_vocab#frequency.md) | 0..1 <br/> [Int32](../types/Int32.md) |  <br/>  | direct | 6748 |
| [http___id.nlm.nih.gov_mesh_vocab#active](../slots/http___id.nlm.nih.gov_mesh_vocab#active.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) |  <br/>  | direct | 6750 |
| [http___id.nlm.nih.gov_mesh_vocab#mappedTo](../slots/http___id.nlm.nih.gov_mesh_vocab#mappedTo.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md) |  <br/>  | direct | 395 |
| [http___id.nlm.nih.gov_mesh_vocab#note](../slots/http___id.nlm.nih.gov_mesh_vocab#note.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 2102 |
| [http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md) |  <br/>  | direct | 13619 |
| [http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso](../slots/http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md)&nbsp;or&nbsp;<br />[HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md) |  <br/>  | direct | 49 |
| [http___id.nlm.nih.gov_mesh_vocab#previousIndexing](../slots/http___id.nlm.nih.gov_mesh_vocab#previousIndexing.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 111 |
| [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |  <br/>  | direct | 6750 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 6750 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
from_schema: okns:biobricks-mesh-kg
rank: 1000
slots:
- http___id.nlm.nih.gov_mesh_vocab#dateCreated
- http___id.nlm.nih.gov_mesh_vocab#preferredTerm
- http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
- http___id.nlm.nih.gov_mesh_vocab#concept
- http___id.nlm.nih.gov_mesh_vocab#dateRevised
- http___id.nlm.nih.gov_mesh_vocab#identifier
- http___id.nlm.nih.gov_mesh_vocab#source
- http___id.nlm.nih.gov_mesh_vocab#frequency
- http___id.nlm.nih.gov_mesh_vocab#active
- http___id.nlm.nih.gov_mesh_vocab#mappedTo
- http___id.nlm.nih.gov_mesh_vocab#note
- http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo
- http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso
- http___id.nlm.nih.gov_mesh_vocab#previousIndexing
- http___id.nlm.nih.gov_mesh_vocab#preferredConcept
- rdfs_label
class_uri: http://id.nlm.nih.gov/mesh/vocab#SCR_Disease

```
</details>

### Induced

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
from_schema: okns:biobricks-mesh-kg
rank: 1000
attributes:
  http___id.nlm.nih.gov_mesh_vocab#dateCreated:
    name: http___id.nlm.nih.gov_mesh_vocab#dateCreated
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#dateCreated
    alias: http___id.nlm.nih.gov_mesh_vocab#dateCreated
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#CheckTag
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
    range: date
  http___id.nlm.nih.gov_mesh_vocab#preferredTerm:
    name: http___id.nlm.nih.gov_mesh_vocab#preferredTerm
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#preferredTerm
    alias: http___id.nlm.nih.gov_mesh_vocab#preferredTerm
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#CheckTag
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#PublicationType
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Population
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    range: http___id.nlm.nih.gov_mesh_vocab#Term
  http___id.nlm.nih.gov_mesh_vocab#lastActiveYear:
    name: http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#lastActiveYear
    alias: http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
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
  http___id.nlm.nih.gov_mesh_vocab#concept:
    name: http___id.nlm.nih.gov_mesh_vocab#concept
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#concept
    alias: http___id.nlm.nih.gov_mesh_vocab#concept
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#PublicationType
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Population
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    range: http___id.nlm.nih.gov_mesh_vocab#Concept
  http___id.nlm.nih.gov_mesh_vocab#dateRevised:
    name: http___id.nlm.nih.gov_mesh_vocab#dateRevised
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#dateRevised
    alias: http___id.nlm.nih.gov_mesh_vocab#dateRevised
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#CheckTag
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#PublicationType
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Population
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    range: date
  http___id.nlm.nih.gov_mesh_vocab#identifier:
    name: http___id.nlm.nih.gov_mesh_vocab#identifier
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#identifier
    alias: http___id.nlm.nih.gov_mesh_vocab#identifier
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#CheckTag
    - http___id.nlm.nih.gov_mesh_vocab#Concept
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
    range: string
  http___id.nlm.nih.gov_mesh_vocab#source:
    name: http___id.nlm.nih.gov_mesh_vocab#source
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#source
    alias: http___id.nlm.nih.gov_mesh_vocab#source
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    range: string
  http___id.nlm.nih.gov_mesh_vocab#frequency:
    name: http___id.nlm.nih.gov_mesh_vocab#frequency
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#frequency
    alias: http___id.nlm.nih.gov_mesh_vocab#frequency
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Population
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    range: int32
  http___id.nlm.nih.gov_mesh_vocab#active:
    name: http___id.nlm.nih.gov_mesh_vocab#active
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#active
    alias: http___id.nlm.nih.gov_mesh_vocab#active
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
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
  http___id.nlm.nih.gov_mesh_vocab#mappedTo:
    name: http___id.nlm.nih.gov_mesh_vocab#mappedTo
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#mappedTo
    alias: http___id.nlm.nih.gov_mesh_vocab#mappedTo
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Population
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    range: Any
    any_of:
    - range: http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
    - range: http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
  http___id.nlm.nih.gov_mesh_vocab#note:
    name: http___id.nlm.nih.gov_mesh_vocab#note
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#note
    alias: http___id.nlm.nih.gov_mesh_vocab#note
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    range: string
  http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo:
    name: http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#preferredMappedTo
    alias: http___id.nlm.nih.gov_mesh_vocab#preferredMappedTo
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Population
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    range: Any
    any_of:
    - range: http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
    - range: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    - range: http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
  http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso:
    name: http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#indexerConsiderAlso
    alias: http___id.nlm.nih.gov_mesh_vocab#indexerConsiderAlso
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    range: Any
    any_of:
    - range: http___id.nlm.nih.gov_mesh_vocab#AllowedDescriptorQualifierPair
    - range: uri
    - range: http___id.nlm.nih.gov_mesh_vocab#DisallowedDescriptorQualifierPair
    - range: http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
  http___id.nlm.nih.gov_mesh_vocab#previousIndexing:
    name: http___id.nlm.nih.gov_mesh_vocab#previousIndexing
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#previousIndexing
    alias: http___id.nlm.nih.gov_mesh_vocab#previousIndexing
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#PublicationType
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    range: string
  http___id.nlm.nih.gov_mesh_vocab#preferredConcept:
    name: http___id.nlm.nih.gov_mesh_vocab#preferredConcept
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#preferredConcept
    alias: http___id.nlm.nih.gov_mesh_vocab#preferredConcept
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#CheckTag
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#PublicationType
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Chemical
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Organism
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Population
    - http___id.nlm.nih.gov_mesh_vocab#SCR_Protocol
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    range: http___id.nlm.nih.gov_mesh_vocab#Concept
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___id.nlm.nih.gov_mesh_vocab#SCR_Disease
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
class_uri: http://id.nlm.nih.gov/mesh/vocab#SCR_Disease

```
</details>