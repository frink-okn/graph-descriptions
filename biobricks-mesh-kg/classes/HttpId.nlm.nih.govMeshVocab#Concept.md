

# Class: HttpId.nlm.nih.govMeshVocab#Concept




This class occurs 464362 times.


URI: [http://id.nlm.nih.gov/mesh/vocab#Concept](http://id.nlm.nih.gov/mesh/vocab#Concept)






```mermaid
 classDiagram
    class HttpId.nlm.nih.govMeshVocab#Concept
    click HttpId.nlm.nih.govMeshVocab#Concept href "../HttpId.nlm.nih.govMeshVocab#Concept"
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#active
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" Boolean : http___id.nlm.nih.gov_mesh_vocab#active
    click Boolean href "../Boolean"

        
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#broaderConcept
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#broaderConcept
    click HttpId.nlm.nih.govMeshVocab#Concept href "../HttpId.nlm.nih.govMeshVocab#Concept"

        
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#casn1_label
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#casn1_label
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#identifier
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#identifier
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#narrowerConcept
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#narrowerConcept
    click HttpId.nlm.nih.govMeshVocab#Concept href "../HttpId.nlm.nih.govMeshVocab#Concept"

        
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#preferredTerm
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#preferredTerm
    click HttpId.nlm.nih.govMeshVocab#Term href "../HttpId.nlm.nih.govMeshVocab#Term"

        
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#registryNumber
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#registryNumber
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#relatedConcept
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#relatedConcept
    click HttpId.nlm.nih.govMeshVocab#Concept href "../HttpId.nlm.nih.govMeshVocab#Concept"

        
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#relatedRegistryNumber
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#relatedRegistryNumber
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#scopeNote
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" String : http___id.nlm.nih.gov_mesh_vocab#scopeNote
    click String href "../String"

        
      HttpId.nlm.nih.govMeshVocab#Concept : http___id.nlm.nih.gov_mesh_vocab#term
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" HttpId.nlm.nih.govMeshVocab#Term : http___id.nlm.nih.gov_mesh_vocab#term
    click HttpId.nlm.nih.govMeshVocab#Term href "../HttpId.nlm.nih.govMeshVocab#Term"

        
      HttpId.nlm.nih.govMeshVocab#Concept : rdfs_label
        
          
    
    
    HttpId.nlm.nih.govMeshVocab#Concept --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___id.nlm.nih.gov_mesh_vocab#preferredTerm](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredTerm.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |  <br/>  | direct | 464362 |
| [http___id.nlm.nih.gov_mesh_vocab#lastActiveYear](../slots/http___id.nlm.nih.gov_mesh_vocab#lastActiveYear.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 4321 |
| [http___id.nlm.nih.gov_mesh_vocab#narrowerConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#narrowerConcept.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |  <br/>  | direct | 91735 |
| [http___id.nlm.nih.gov_mesh_vocab#casn1_label](../slots/http___id.nlm.nih.gov_mesh_vocab#casn1_label.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 22720 |
| [http___id.nlm.nih.gov_mesh_vocab#identifier](../slots/http___id.nlm.nih.gov_mesh_vocab#identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 464362 |
| [http___id.nlm.nih.gov_mesh_vocab#registryNumber](../slots/http___id.nlm.nih.gov_mesh_vocab#registryNumber.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 385145 |
| [http___id.nlm.nih.gov_mesh_vocab#relatedConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#relatedConcept.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |  <br/>  | direct | 8072 |
| [http___id.nlm.nih.gov_mesh_vocab#active](../slots/http___id.nlm.nih.gov_mesh_vocab#active.md) | 0..1 <br/> [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean) |  <br/>  | direct | 464362 |
| [http___id.nlm.nih.gov_mesh_vocab#scopeNote](../slots/http___id.nlm.nih.gov_mesh_vocab#scopeNote.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 32789 |
| [http___id.nlm.nih.gov_mesh_vocab#relatedRegistryNumber](../slots/http___id.nlm.nih.gov_mesh_vocab#relatedRegistryNumber.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 43667 |
| [http___id.nlm.nih.gov_mesh_vocab#broaderConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#broaderConcept.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |  <br/>  | direct | 8850 |
| [http___id.nlm.nih.gov_mesh_vocab#term](../slots/http___id.nlm.nih.gov_mesh_vocab#term.md) | 0..1 <br/> [HttpId.nlm.nih.govMeshVocab#Term](../classes/HttpId.nlm.nih.govMeshVocab#Term.md) |  <br/>  | direct | 392785 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 464362 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpId.nlm.nih.govMeshVocab#CheckTag](../classes/HttpId.nlm.nih.govMeshVocab#CheckTag.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) | [http___id.nlm.nih.gov_mesh_vocab#narrowerConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#narrowerConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) | [http___id.nlm.nih.gov_mesh_vocab#relatedConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#relatedConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) | [http___id.nlm.nih.gov_mesh_vocab#broaderConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#broaderConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor.md) | [http___id.nlm.nih.gov_mesh_vocab#concept](../slots/http___id.nlm.nih.gov_mesh_vocab#concept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#GeographicalDescriptor.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#PublicationType](../classes/HttpId.nlm.nih.govMeshVocab#PublicationType.md) | [http___id.nlm.nih.gov_mesh_vocab#concept](../slots/http___id.nlm.nih.gov_mesh_vocab#concept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#PublicationType](../classes/HttpId.nlm.nih.govMeshVocab#PublicationType.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) | [http___id.nlm.nih.gov_mesh_vocab#concept](../slots/http___id.nlm.nih.gov_mesh_vocab#concept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#Qualifier](../classes/HttpId.nlm.nih.govMeshVocab#Qualifier.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRChemical](../classes/HttpId.nlm.nih.govMeshVocab#SCRChemical.md) | [http___id.nlm.nih.gov_mesh_vocab#concept](../slots/http___id.nlm.nih.gov_mesh_vocab#concept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRChemical](../classes/HttpId.nlm.nih.govMeshVocab#SCRChemical.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRDisease](../classes/HttpId.nlm.nih.govMeshVocab#SCRDisease.md) | [http___id.nlm.nih.gov_mesh_vocab#concept](../slots/http___id.nlm.nih.gov_mesh_vocab#concept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRDisease](../classes/HttpId.nlm.nih.govMeshVocab#SCRDisease.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#SCROrganism](../classes/HttpId.nlm.nih.govMeshVocab#SCROrganism.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#SCROrganism](../classes/HttpId.nlm.nih.govMeshVocab#SCROrganism.md) | [http___id.nlm.nih.gov_mesh_vocab#concept](../slots/http___id.nlm.nih.gov_mesh_vocab#concept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRPopulation](../classes/HttpId.nlm.nih.govMeshVocab#SCRPopulation.md) | [http___id.nlm.nih.gov_mesh_vocab#concept](../slots/http___id.nlm.nih.gov_mesh_vocab#concept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRPopulation](../classes/HttpId.nlm.nih.govMeshVocab#SCRPopulation.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRProtocol](../classes/HttpId.nlm.nih.govMeshVocab#SCRProtocol.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#SCRProtocol](../classes/HttpId.nlm.nih.govMeshVocab#SCRProtocol.md) | [http___id.nlm.nih.gov_mesh_vocab#concept](../slots/http___id.nlm.nih.gov_mesh_vocab#concept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md) | [http___id.nlm.nih.gov_mesh_vocab#preferredConcept](../slots/http___id.nlm.nih.gov_mesh_vocab#preferredConcept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |
| [HttpId.nlm.nih.govMeshVocab#TopicalDescriptor](../classes/HttpId.nlm.nih.govMeshVocab#TopicalDescriptor.md) | [http___id.nlm.nih.gov_mesh_vocab#concept](../slots/http___id.nlm.nih.gov_mesh_vocab#concept.md) | range | [HttpId.nlm.nih.govMeshVocab#Concept](../classes/HttpId.nlm.nih.govMeshVocab#Concept.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#Concept
from_schema: okns:biobricks-mesh-kg
rank: 1000
slots:
- http___id.nlm.nih.gov_mesh_vocab#preferredTerm
- http___id.nlm.nih.gov_mesh_vocab#lastActiveYear
- http___id.nlm.nih.gov_mesh_vocab#narrowerConcept
- http___id.nlm.nih.gov_mesh_vocab#casn1_label
- http___id.nlm.nih.gov_mesh_vocab#identifier
- http___id.nlm.nih.gov_mesh_vocab#registryNumber
- http___id.nlm.nih.gov_mesh_vocab#relatedConcept
- http___id.nlm.nih.gov_mesh_vocab#active
- http___id.nlm.nih.gov_mesh_vocab#scopeNote
- http___id.nlm.nih.gov_mesh_vocab#relatedRegistryNumber
- http___id.nlm.nih.gov_mesh_vocab#broaderConcept
- http___id.nlm.nih.gov_mesh_vocab#term
- rdfs_label
class_uri: http://id.nlm.nih.gov/mesh/vocab#Concept

```
</details>

### Induced

<details>

```yaml
name: http___id.nlm.nih.gov_mesh_vocab#Concept
from_schema: okns:biobricks-mesh-kg
rank: 1000
attributes:
  http___id.nlm.nih.gov_mesh_vocab#preferredTerm:
    name: http___id.nlm.nih.gov_mesh_vocab#preferredTerm
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#preferredTerm
    alias: http___id.nlm.nih.gov_mesh_vocab#preferredTerm
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
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
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
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
  http___id.nlm.nih.gov_mesh_vocab#narrowerConcept:
    name: http___id.nlm.nih.gov_mesh_vocab#narrowerConcept
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#narrowerConcept
    alias: http___id.nlm.nih.gov_mesh_vocab#narrowerConcept
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    range: http___id.nlm.nih.gov_mesh_vocab#Concept
  http___id.nlm.nih.gov_mesh_vocab#casn1_label:
    name: http___id.nlm.nih.gov_mesh_vocab#casn1_label
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#casn1_label
    alias: http___id.nlm.nih.gov_mesh_vocab#casn1_label
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    range: string
  http___id.nlm.nih.gov_mesh_vocab#identifier:
    name: http___id.nlm.nih.gov_mesh_vocab#identifier
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#identifier
    alias: http___id.nlm.nih.gov_mesh_vocab#identifier
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
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
  http___id.nlm.nih.gov_mesh_vocab#registryNumber:
    name: http___id.nlm.nih.gov_mesh_vocab#registryNumber
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#registryNumber
    alias: http___id.nlm.nih.gov_mesh_vocab#registryNumber
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    range: string
  http___id.nlm.nih.gov_mesh_vocab#relatedConcept:
    name: http___id.nlm.nih.gov_mesh_vocab#relatedConcept
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#relatedConcept
    alias: http___id.nlm.nih.gov_mesh_vocab#relatedConcept
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    range: http___id.nlm.nih.gov_mesh_vocab#Concept
  http___id.nlm.nih.gov_mesh_vocab#active:
    name: http___id.nlm.nih.gov_mesh_vocab#active
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#active
    alias: http___id.nlm.nih.gov_mesh_vocab#active
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
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
  http___id.nlm.nih.gov_mesh_vocab#scopeNote:
    name: http___id.nlm.nih.gov_mesh_vocab#scopeNote
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#scopeNote
    alias: http___id.nlm.nih.gov_mesh_vocab#scopeNote
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    range: string
  http___id.nlm.nih.gov_mesh_vocab#relatedRegistryNumber:
    name: http___id.nlm.nih.gov_mesh_vocab#relatedRegistryNumber
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#relatedRegistryNumber
    alias: http___id.nlm.nih.gov_mesh_vocab#relatedRegistryNumber
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    range: string
  http___id.nlm.nih.gov_mesh_vocab#broaderConcept:
    name: http___id.nlm.nih.gov_mesh_vocab#broaderConcept
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#broaderConcept
    alias: http___id.nlm.nih.gov_mesh_vocab#broaderConcept
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    range: http___id.nlm.nih.gov_mesh_vocab#Concept
  http___id.nlm.nih.gov_mesh_vocab#term:
    name: http___id.nlm.nih.gov_mesh_vocab#term
    from_schema: okns:biobricks-mesh-kg
    rank: 1000
    slot_uri: http://id.nlm.nih.gov/mesh/vocab#term
    alias: http___id.nlm.nih.gov_mesh_vocab#term
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
    domain_of:
    - http___id.nlm.nih.gov_mesh_vocab#Concept
    range: http___id.nlm.nih.gov_mesh_vocab#Term
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___id.nlm.nih.gov_mesh_vocab#Concept
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
class_uri: http://id.nlm.nih.gov/mesh/vocab#Concept

```
</details>