

# Class: HttpId.nlm.nih.govMeshVocab#Term




This class occurs 862579 times.


URI: [http://id.nlm.nih.gov/mesh/vocab#Term](http://id.nlm.nih.gov/mesh/vocab#Term)






```mermaid
 classDiagram
    class HttpId.nlm.nih.govMeshVocab#Term
    click HttpId.nlm.nih.govMeshVocab#Term href "../HttpId.nlm.nih.govMeshVocab#Term"
      HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#abbreviation
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Term --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#abbreviation
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#active
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Term --> "0..1" Boolean : http___id.nlm.nih.gov_mesh_vocab#active
    click Boolean href "../Boolean"

        
      HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#altLabel
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Term --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#altLabel
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#dateCreated
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Term --> "0..1" Date : http___id.nlm.nih.gov_mesh_vocab#dateCreated
    click Date href "../Date"

        
      HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#entryVersion
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Term --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#entryVersion
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#identifier
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Term --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#identifier
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Term --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#lexicalTag
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Term --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#lexicalTag
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#prefLabel
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Term --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#prefLabel
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#sortVersion
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Term --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#sortVersion
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#thesaurusID
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Term --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#thesaurusID
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___id.nlm.nih.gov_mesh_vocab#prefLabel](../slots/http___id.nlm.nih.gov_mesh_vocab#prefLabel.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 862579 |
| [http___id.nlm.nih.gov_mesh_vocab#dateCreated](../slots/http___id.nlm.nih.gov_mesh_vocab#dateCreated.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) |  <br/>  | direct | 632173 |
| [http___id.nlm.nih.gov_mesh_vocab#entryVersion](../slots/http___id.nlm.nih.gov_mesh_vocab#entryVersion.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 16274 |
| [http___id.nlm.nih.gov_mesh_vocab#lastActiveYear](../slots/http___id.nlm.nih.gov_mesh_vocab#lastActiveYear.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 12436 |
| [http___id.nlm.nih.gov_mesh_vocab#altLabel](../slots/http___id.nlm.nih.gov_mesh_vocab#altLabel.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 131103 |
| [http___id.nlm.nih.gov_mesh_vocab#identifier](../slots/http___id.nlm.nih.gov_mesh_vocab#identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 862579 |
| [http___id.nlm.nih.gov_mesh_vocab#thesaurusID](../slots/http___id.nlm.nih.gov_mesh_vocab#thesaurusID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 909053 |
| [http___id.nlm.nih.gov_mesh_vocab#sortVersion](../slots/http___id.nlm.nih.gov_mesh_vocab#sortVersion.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 3973 |
| [http___id.nlm.nih.gov_mesh_vocab#active](../slots/http___id.nlm.nih.gov_mesh_vocab#active.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) |  <br/>  | direct | 862579 |
| [http___id.nlm.nih.gov_mesh_vocab#abbreviation](../slots/http___id.nlm.nih.gov_mesh_vocab#abbreviation.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 81 |
| [http___id.nlm.nih.gov_mesh_vocab#lexicalTag](../slots/http___id.nlm.nih.gov_mesh_vocab#lexicalTag.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 862579 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpId.nlm.nih.govMeshVocab#CheckTag](../classes/HttpId.nlm.nih.govMeshVocab#CheckTag.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |
| [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |
| [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) | [http___id.nlm.nih.gov_mesh_vocab#term](../slots/http___id.nlm.nih.gov_mesh_vocab#term.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |
| [HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |
| [HttpId.nlm.nih.govMeshVocab#PublicationType](../classes/HttpId.nlm.nih.govMeshVocab#PublicationType.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |
| [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRChemical](../classes/HttpId.nlm.nih.govMeshVocab#SCRChemical.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRDisease](../classes/HttpId.nlm.nih.govMeshVocab#SCRDisease.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |
| [HttpId.nlm.nih.govMeshVocab#SCROrganism](../classes/HttpId.nlm.nih.govMeshVocab#SCROrganism.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRPopulation](../classes/HttpId.nlm.nih.govMeshVocab#SCRPopulation.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRProtocol](../classes/HttpId.nlm.nih.govMeshVocab#SCRProtocol.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |
| [HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | range | [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#Term
from_schema: okns:biobricks-mesh-kg
rank: 1000
slots:
- http___id.nlm.nih.gov_mesh_vocab#prefLabel
- http___id.nlm.nih.gov_mesh_vocab#dateCreated
- http___id.nlm.nih.gov_mesh_vocab#entryVersion
- http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
- http___id.nlm.nih.gov_mesh_vocab#altLabel
- http___id.nlm.nih.gov_mesh_vocab#identifier
- http___id.nlm.nih.gov_mesh_vocab#thesaurusID
- http___id.nlm.nih.gov_mesh_vocab#sortVersion
- http___id.nlm.nih.gov_mesh_vocab#active
- http___id.nlm.nih.gov_mesh_vocab#abbreviation
- http___id.nlm.nih.gov_mesh_vocab#lexicalTag
class_uri: http://id.nlm.nih.gov/mesh/vocab#Term

```
</details>

### Induced

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#Term
from_schema: okns:biobricks-mesh-kg
rank: 1000
attributes:
  http___id.nlm.nih.gov_mesh_vocab#prefLabel:
    name: http___id.nlm.nih.gov_mesh_vocab#prefLabel
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#prefLabel
    alias: http___id.nlm.nih.gov_mesh_vocab#prefLabel
    owner: http___id.nlm.nih.gov_mesh_vocab#Term
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Term
    range: string
  http___id.nlm.nih.gov_mesh_vocab#dateCreated:
    name: http___id.nlm.nih.gov_mesh_vocab#dateCreated
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#dateCreated
    alias: http___id.nlm.nih.gov_mesh_vocab#dateCreated
    owner: http___id.nlm.nih.gov_mesh_vocab#Term
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
  http___id.nlm.nih.gov_mesh_vocab#entryVersion:
    name: http___id.nlm.nih.gov_mesh_vocab#entryVersion
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#entryVersion
    alias: http___id.nlm.nih.gov_mesh_vocab#entryVersion
    owner: http___id.nlm.nih.gov_mesh_vocab#Term
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Term
    range: string
  http___id.nlm.nih.gov_mesh_vocab#lastActiveYear:
    name: http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#lastActiveYear
    alias: http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    owner: http___id.nlm.nih.gov_mesh_vocab#Term
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
  http___id.nlm.nih.gov_mesh_vocab#altLabel:
    name: http___id.nlm.nih.gov_mesh_vocab#altLabel
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#altLabel
    alias: http___id.nlm.nih.gov_mesh_vocab#altLabel
    owner: http___id.nlm.nih.gov_mesh_vocab#Term
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Term
    range: string
  http___id.nlm.nih.gov_mesh_vocab#identifier:
    name: http___id.nlm.nih.gov_mesh_vocab#identifier
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#identifier
    alias: http___id.nlm.nih.gov_mesh_vocab#identifier
    owner: http___id.nlm.nih.gov_mesh_vocab#Term
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
  http___id.nlm.nih.gov_mesh_vocab#thesaurusID:
    name: http___id.nlm.nih.gov_mesh_vocab#thesaurusID
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#thesaurusID
    alias: http___id.nlm.nih.gov_mesh_vocab#thesaurusID
    owner: http___id.nlm.nih.gov_mesh_vocab#Term
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Term
    range: string
  http___id.nlm.nih.gov_mesh_vocab#sortVersion:
    name: http___id.nlm.nih.gov_mesh_vocab#sortVersion
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#sortVersion
    alias: http___id.nlm.nih.gov_mesh_vocab#sortVersion
    owner: http___id.nlm.nih.gov_mesh_vocab#Term
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Term
    range: string
  http___id.nlm.nih.gov_mesh_vocab#active:
    name: http___id.nlm.nih.gov_mesh_vocab#active
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#active
    alias: http___id.nlm.nih.gov_mesh_vocab#active
    owner: http___id.nlm.nih.gov_mesh_vocab#Term
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
  http___id.nlm.nih.gov_mesh_vocab#abbreviation:
    name: http___id.nlm.nih.gov_mesh_vocab#abbreviation
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#abbreviation
    alias: http___id.nlm.nih.gov_mesh_vocab#abbreviation
    owner: http___id.nlm.nih.gov_mesh_vocab#Term
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Term
    range: string
  http___id.nlm.nih.gov_mesh_vocab#lexicalTag:
    name: http___id.nlm.nih.gov_mesh_vocab#lexicalTag
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#lexicalTag
    alias: http___id.nlm.nih.gov_mesh_vocab#lexicalTag
    owner: http___id.nlm.nih.gov_mesh_vocab#Term
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Term
    range: string
class_uri: http://id.nlm.nih.gov/mesh/vocab#Term

```
</details>