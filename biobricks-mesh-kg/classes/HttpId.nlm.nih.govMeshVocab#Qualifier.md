

# Class: HttpId.nlm.nih.govMeshVocab#Qualifier




This class occurs 84 times.


URI: [http://id.nlm.nih.gov/mesh/vocab#Qualifier](http://id.nlm.nih.gov/mesh/vocab#Qualifier)






```mermaid
 classDiagram
    class HttpId.nlm.nih.govMeshVocab#Qualifier
    click HttpId.nlm.nih.govMeshVocab#Qualifier href "../HttpId.nlm.nih.govMeshVocab#Qualifier"
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#active
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" Boolean : http___id.nlm.nih.gov_mesh_vocab#active
    click Boolean href "../Boolean"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#annotation
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#annotation
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#broaderQualifier
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#broaderQualifier
    click HttpId.nlm.nih.govMeshVocab#Qualifier href "../HttpId.nlm.nih.govMeshVocab#Qualifier"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#concept
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#concept
    click HttpId.nlm.nih.govMeshVocab#Concept href "../HttpId.nlm.nih.govMeshVocab#Concept"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#dateCreated
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" Date : http___id.nlm.nih.gov_mesh_vocab#dateCreated
    click Date href "../Date"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#dateEstablished
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" Date : http___id.nlm.nih.gov_mesh_vocab#dateEstablished
    click Date href "../Date"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#dateRevised
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" Date : http___id.nlm.nih.gov_mesh_vocab#dateRevised
    click Date href "../Date"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#historyNote
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#historyNote
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#identifier
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#identifier
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#onlineNote
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#onlineNote
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#preferredConcept
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#preferredConcept
    click HttpId.nlm.nih.govMeshVocab#Concept href "../HttpId.nlm.nih.govMeshVocab#Concept"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#preferredTerm
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#preferredTerm
    click HttpId.nlm.nih.govMeshVocab#Term href "../HttpId.nlm.nih.govMeshVocab#Term"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : http___id.nlm.nih.gov_mesh_vocab#treeNumber
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" HttpId.nlm.nih.govMeshVocab#TreeNumber : http___id.nlm.nih.gov_mesh_vocab#treeNumber
    click HttpId.nlm.nih.govMeshVocab#TreeNumber href "../HttpId.nlm.nih.govMeshVocab#TreeNumber"

        
      HttpId.nlm.nih.govMeshVocab#Qualifier : rdfs_label
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Qualifier --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___id.nlm.nih.gov_mesh_vocab#dateCreated](../slots/http___id.nlm.nih.gov_mesh_vocab#dateCreated.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 84 |
| [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |  <br/>  | direct | 84 |
| [http___id.nlm.nih.gov_mesh_vocab#historyNote](../slots/http___id.nlm.nih.gov_mesh_vocab#historyNote.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 84 |
| [http___id.nlm.nih.gov_mesh_vocab#lastActiveYear](../slots/http___id.nlm.nih.gov_mesh_vocab#lastActiveYear.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 8 |
| [http___id.nlm.nih.gov_mesh_vocab#concept](../slots/http___id.nlm.nih.gov_mesh_vocab#concept.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |  <br/>  | direct | 156 |
| [http___id.nlm.nih.gov_mesh_vocab#broaderQualifier](../slots/http___id.nlm.nih.gov_mesh_vocab#broaderQualifier.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) |  <br/>  | direct | 76 |
| [http___id.nlm.nih.gov_mesh_vocab#dateRevised](../slots/http___id.nlm.nih.gov_mesh_vocab#dateRevised.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 84 |
| [http___id.nlm.nih.gov_mesh_vocab#identifier](../slots/http___id.nlm.nih.gov_mesh_vocab#identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 84 |
| [http___id.nlm.nih.gov_mesh_vocab#annotation](../slots/http___id.nlm.nih.gov_mesh_vocab#annotation.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 84 |
| [http___id.nlm.nih.gov_mesh_vocab#active](../slots/http___id.nlm.nih.gov_mesh_vocab#active.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) |  <br/>  | direct | 84 |
| [http___id.nlm.nih.gov_mesh_vocab#treeNumber](../slots/http___id.nlm.nih.gov_mesh_vocab#treeNumber.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#TreeNumber](../classes/HttpId.nlm.nih.govMeshVocab#TreeNumber.md) |  <br/>  | direct | 99 |
| [http___id.nlm.nih.gov_mesh_vocab#dateEstablished](../slots/http___id.nlm.nih.gov_mesh_vocab#dateEstablished.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 84 |
| [http___id.nlm.nih.gov_mesh_vocab#onlineNote](../slots/http___id.nlm.nih.gov_mesh_vocab#onlineNote.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 82 |
| [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |  <br/>  | direct | 84 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 84 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#AllowedDescriptorQualifierPair.md) | [http___id.nlm.nih.gov_mesh_vocab#hasQualifier](../slots/http___id.nlm.nih.gov_mesh_vocab#hasQualifier.md) | range | [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) |
| [HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair](../classes/HttpId.nlm.nih.govMeshVocab#DisallowedDescriptorQualifierPair.md) | [http___id.nlm.nih.gov_mesh_vocab#hasQualifier](../slots/http___id.nlm.nih.gov_mesh_vocab#hasQualifier.md) | range | [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) |
| [HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor.md) | [http___id.nlm.nih.gov_mesh_vocab#allowableQualifier](../slots/http___id.nlm.nih.gov_mesh_vocab#allowableQualifier.md) | range | [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) |
| [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) | [http___id.nlm.nih.gov_mesh_vocab#broaderQualifier](../slots/http___id.nlm.nih.gov_mesh_vocab#broaderQualifier.md) | range | [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) |
| [HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md) | [http___id.nlm.nih.gov_mesh_vocab#allowableQualifier](../slots/http___id.nlm.nih.gov_mesh_vocab#allowableQualifier.md) | range | [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#Qualifier
from_schema: okns:biobricks-mesh-kg
rank: 1000
slots:
- http___id.nlm.nih.gov_mesh_vocab#dateCreated
- http___id.nlm.nih.gov_mesh_vocab#preferredTerm
- http___id.nlm.nih.gov_mesh_vocab#historyNote
- http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
- http___id.nlm.nih.gov_mesh_vocab#concept
- http___id.nlm.nih.gov_mesh_vocab#broaderQualifier
- http___id.nlm.nih.gov_mesh_vocab#dateRevised
- http___id.nlm.nih.gov_mesh_vocab#identifier
- http___id.nlm.nih.gov_mesh_vocab#annotation
- http___id.nlm.nih.gov_mesh_vocab#active
- http___id.nlm.nih.gov_mesh_vocab#treeNumber
- http___id.nlm.nih.gov_mesh_vocab#dateEstablished
- http___id.nlm.nih.gov_mesh_vocab#onlineNote
- http___id.nlm.nih.gov_mesh_vocab#preferredConcept
- rdfs_label
class_uri: http://id.nlm.nih.gov/mesh/vocab#Qualifier

```
</details>

### Induced

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#Qualifier
from_schema: okns:biobricks-mesh-kg
rank: 1000
attributes:
  http___id.nlm.nih.gov_mesh_vocab#dateCreated:
    name: http___id.nlm.nih.gov_mesh_vocab#dateCreated
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#dateCreated
    alias: http___id.nlm.nih.gov_mesh_vocab#dateCreated
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
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
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
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
  http___id.nlm.nih.gov_mesh_vocab#historyNote:
    name: http___id.nlm.nih.gov_mesh_vocab#historyNote
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#historyNote
    alias: http___id.nlm.nih.gov_mesh_vocab#historyNote
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#CheckTag
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#PublicationType
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    range: string
  http___id.nlm.nih.gov_mesh_vocab#lastActiveYear:
    name: http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#lastActiveYear
    alias: http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
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
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
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
  http___id.nlm.nih.gov_mesh_vocab#broaderQualifier:
    name: http___id.nlm.nih.gov_mesh_vocab#broaderQualifier
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#broaderQualifier
    alias: http___id.nlm.nih.gov_mesh_vocab#broaderQualifier
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    range: http___id.nlm.nih.gov_mesh_vocab#Qualifier
  http___id.nlm.nih.gov_mesh_vocab#dateRevised:
    name: http___id.nlm.nih.gov_mesh_vocab#dateRevised
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#dateRevised
    alias: http___id.nlm.nih.gov_mesh_vocab#dateRevised
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
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
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
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
  http___id.nlm.nih.gov_mesh_vocab#annotation:
    name: http___id.nlm.nih.gov_mesh_vocab#annotation
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#annotation
    alias: http___id.nlm.nih.gov_mesh_vocab#annotation
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#CheckTag
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#PublicationType
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    range: string
  http___id.nlm.nih.gov_mesh_vocab#active:
    name: http___id.nlm.nih.gov_mesh_vocab#active
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#active
    alias: http___id.nlm.nih.gov_mesh_vocab#active
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
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
  http___id.nlm.nih.gov_mesh_vocab#treeNumber:
    name: http___id.nlm.nih.gov_mesh_vocab#treeNumber
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#treeNumber
    alias: http___id.nlm.nih.gov_mesh_vocab#treeNumber
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#PublicationType
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    range: http___id.nlm.nih.gov_mesh_vocab#TreeNumber
  http___id.nlm.nih.gov_mesh_vocab#dateEstablished:
    name: http___id.nlm.nih.gov_mesh_vocab#dateEstablished
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#dateEstablished
    alias: http___id.nlm.nih.gov_mesh_vocab#dateEstablished
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#CheckTag
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#PublicationType
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    range: date
  http___id.nlm.nih.gov_mesh_vocab#onlineNote:
    name: http___id.nlm.nih.gov_mesh_vocab#onlineNote
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#onlineNote
    alias: http___id.nlm.nih.gov_mesh_vocab#onlineNote
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#GeographicalDescriptor
    - http___id.nlm.nih.gov_mesh_vocab#Qualifier
    - http___id.nlm.nih.gov_mesh_vocab#TopicalDescriptor
    range: string
  http___id.nlm.nih.gov_mesh_vocab#preferredConcept:
    name: http___id.nlm.nih.gov_mesh_vocab#preferredConcept
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#preferredConcept
    alias: http___id.nlm.nih.gov_mesh_vocab#preferredConcept
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
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
    owner: http___id.nlm.nih.gov_mesh_vocab#Qualifier
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
class_uri: http://id.nlm.nih.gov/mesh/vocab#Qualifier

```
</details>