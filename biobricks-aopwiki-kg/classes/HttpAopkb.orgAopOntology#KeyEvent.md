

# Class: HttpAopkb.orgAopOntology#KeyEvent




This class occurs 1469 times.


URI: [http://aopkb.org/aop_ontology#KeyEvent](http://aopkb.org/aop_ontology#KeyEvent)






```mermaid
 classDiagram
    class HttpAopkb.orgAopOntology#KeyEvent
    click HttpAopkb.orgAopOntology#KeyEvent href "../HttpAopkb.orgAopOntology#KeyEvent"
      HttpAopkb.orgAopOntology#KeyEvent : dc_description
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : dc_description
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEvent : dc_identifier
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : dc_identifier
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEvent : dc_source
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : dc_source
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEvent : dc_title
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : dc_title
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEvent : dct_alternative
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" RdfsLiteral : dct_alternative
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpAopkb.orgAopOntology#KeyEvent : dct_isPartOf
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : dct_isPartOf
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEvent : edam_data_1025
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : edam_data_1025
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEvent : foaf_page
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" FoafDocument : foaf_page
    click FoafDocument href "../FoafDocument"

        
      HttpAopkb.orgAopOntology#KeyEvent : http___aopkb.org_aop_ontology#CellTypeContext
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : http___aopkb.org_aop_ontology#CellTypeContext
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEvent : http___aopkb.org_aop_ontology#LifeStageContext
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" String : http___aopkb.org_aop_ontology#LifeStageContext
    click String href "../String"

        
      HttpAopkb.orgAopOntology#KeyEvent : http___aopkb.org_aop_ontology#OrganContext
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : http___aopkb.org_aop_ontology#OrganContext
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEvent : http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25664
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" String : http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25664
    click String href "../String"

        
      HttpAopkb.orgAopOntology#KeyEvent : http___purl.bioontology.org_ontology_NCBITAXON_131567
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : http___purl.bioontology.org_ontology_NCBITAXON_131567
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEvent : obo_GO_0008150
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" OboGO0008150 : obo_GO_0008150
    click OboGO0008150 href "../OboGO0008150"

        
      HttpAopkb.orgAopOntology#KeyEvent : obo_MMO_0000000
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" String : obo_MMO_0000000
    click String href "../String"

        
      HttpAopkb.orgAopOntology#KeyEvent : obo_PATO_0000001
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" String : obo_PATO_0000001
    click String href "../String"

        
      HttpAopkb.orgAopOntology#KeyEvent : obo_PATO_0000047
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" String : obo_PATO_0000047
    click String href "../String"

        
      HttpAopkb.orgAopOntology#KeyEvent : obo_PATO_0001241
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : obo_PATO_0001241
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEvent : rdfs_label
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEvent : rdfs_seeAlso
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEvent --> "0..1" Any : rdfs_seeAlso
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [rdfs_seeAlso](../slots/rdfs_seeAlso.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI) | Further information about the subject resource <br/>  | direct | 1469 |
| [obo_PATO_0001241](../slots/obo_PATO_0001241.md) | 0..1 <br/> [HttpAopkb.orgAopOntology#CellTypeContext](../classes/HttpAopkb.orgAopOntology#CellTypeContext.md)&nbsp;or&nbsp;<br />[HttpAopkb.orgAopOntology#OrganContext](../classes/HttpAopkb.orgAopOntology#OrganContext.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)&nbsp;or&nbsp;<br />[OboGO0008150](../classes/OboGO0008150.md) |  <br/>  | direct | 705 |
| [http___purl.bioontology.org_ontology_NCBITAXON_131567](../slots/http___purl.bioontology.org_ontology_NCBITAXON_131567.md) | 0..1 <br/> [xsd:string](xsd:string)&nbsp;or&nbsp;<br />[HttpPurl.bioontology.orgOntologyNCBITAXON131567](../classes/HttpPurl.bioontology.orgOntologyNCBITAXON131567.md) |  <br/>  | direct | 1199 |
| [dct_isPartOf](../slots/dct_isPartOf.md) | 0..1 <br/> [Any](../classes/Any.md) | This property is intended to be used with non-literal values <br/> description: A related resource in which the described resource is physically or logically included. | direct | 3103 |
| [foaf_page](../slots/foaf_page.md) | 0..1 <br/> [FoafDocument](../classes/FoafDocument.md) | A page or document about this thing <br/>  | direct | 1469 |
| [dc_title](../slots/dc_title.md) | 0..1 <br/> [Any](../classes/Any.md) | A name given to the resource <br/>  | direct | 1469 |
| [dc_description](../slots/dc_description.md) | 0..1 <br/> [Any](../classes/Any.md) | Description may include but is not limited to: an abstract, a table of conten... <br/> description: An account of the resource. | direct | 547 |
| [http___aopkb.org_aop_ontology#CellTypeContext](../slots/http___aopkb.org_aop_ontology#CellTypeContext.md) | 0..1 <br/> [xsd:string](xsd:string)&nbsp;or&nbsp;<br />[HttpAopkb.orgAopOntology#CellTypeContext](../classes/HttpAopkb.orgAopOntology#CellTypeContext.md) |  <br/>  | direct | 407 |
| [edam_data_1025](../slots/edam_data_1025.md) | 0..1 <br/> [EdamData1025](../classes/EdamData1025.md)&nbsp;or&nbsp;<br />[EdamData2298](../classes/EdamData2298.md) |  <br/>  | direct | 4134 |
| [http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25664](../slots/http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25664.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 1469 |
| [http___aopkb.org_aop_ontology#OrganContext](../slots/http___aopkb.org_aop_ontology#OrganContext.md) | 0..1 <br/> [xsd:string](xsd:string)&nbsp;or&nbsp;<br />[HttpAopkb.orgAopOntology#OrganContext](../classes/HttpAopkb.orgAopOntology#OrganContext.md) |  <br/>  | direct | 288 |
| [obo_MMO_0000000](../slots/obo_MMO_0000000.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 513 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](xsd:string) | A human-readable name for the subject <br/>  | direct | 1469 |
| [obo_PATO_0000001](../slots/obo_PATO_0000001.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 883 |
| [dc_identifier](../slots/dc_identifier.md) | 0..1 <br/> [Any](../classes/Any.md) | Recommended practice is to identify the resource by means of a string conform... <br/> description: An unambiguous reference to the resource within a given context. | direct | 1469 |
| [dct_alternative](../slots/dct_alternative.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | The distinction between titles and alternative titles is application-specific <br/> description: An alternative name for the resource. | direct | 1469 |
| [obo_PATO_0000047](../slots/obo_PATO_0000047.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 423 |
| [http___aopkb.org_aop_ontology#LifeStageContext](../slots/http___aopkb.org_aop_ontology#LifeStageContext.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 446 |
| [dc_source](../slots/dc_source.md) | 0..1 <br/> [Any](../classes/Any.md) | The described resource may be derived from the related resource in whole or i... <br/> description: A related resource from which the described resource is derived. | direct | 1469 |
| [obo_GO_0008150](../slots/obo_GO_0008150.md) | 0..1 <br/> [OboGO0008150](../classes/OboGO0008150.md) |  <br/>  | direct | 848 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpAopkb.orgAopOntology#AdverseOutcomePathway](../classes/HttpAopkb.orgAopOntology#AdverseOutcomePathway.md) | [http___aopkb.org_aop_ontology#has_adverse_outcome](../slots/http___aopkb.org_aop_ontology#has_adverse_outcome.md) | range | [HttpAopkb.orgAopOntology#KeyEvent](../classes/HttpAopkb.orgAopOntology#KeyEvent.md) |
| [HttpAopkb.orgAopOntology#AdverseOutcomePathway](../classes/HttpAopkb.orgAopOntology#AdverseOutcomePathway.md) | [http___aopkb.org_aop_ontology#has_key_event](../slots/http___aopkb.org_aop_ontology#has_key_event.md) | range | [HttpAopkb.orgAopOntology#KeyEvent](../classes/HttpAopkb.orgAopOntology#KeyEvent.md) |
| [HttpAopkb.orgAopOntology#AdverseOutcomePathway](../classes/HttpAopkb.orgAopOntology#AdverseOutcomePathway.md) | [http___aopkb.org_aop_ontology#has_molecular_initiating_event](../slots/http___aopkb.org_aop_ontology#has_molecular_initiating_event.md) | range | [HttpAopkb.orgAopOntology#KeyEvent](../classes/HttpAopkb.orgAopOntology#KeyEvent.md) |
| [HttpAopkb.orgAopOntology#KeyEventRelationship](../classes/HttpAopkb.orgAopOntology#KeyEventRelationship.md) | [http___aopkb.org_aop_ontology#has_upstream_key_event](../slots/http___aopkb.org_aop_ontology#has_upstream_key_event.md) | range | [HttpAopkb.orgAopOntology#KeyEvent](../classes/HttpAopkb.orgAopOntology#KeyEvent.md) |
| [HttpAopkb.orgAopOntology#KeyEventRelationship](../classes/HttpAopkb.orgAopOntology#KeyEventRelationship.md) | [http___aopkb.org_aop_ontology#has_downstream_key_event](../slots/http___aopkb.org_aop_ontology#has_downstream_key_event.md) | range | [HttpAopkb.orgAopOntology#KeyEvent](../classes/HttpAopkb.orgAopOntology#KeyEvent.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___aopkb.org_aop_ontology#KeyEvent
from_schema: okns:biobricks-aopwiki-kg
rank: 1000
slots:
- rdfs_seeAlso
- obo_PATO_0001241
- http___purl.bioontology.org_ontology_NCBITAXON_131567
- dct_isPartOf
- foaf_page
- dc_title
- dc_description
- http___aopkb.org_aop_ontology#CellTypeContext
- edam_data_1025
- http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25664
- http___aopkb.org_aop_ontology#OrganContext
- obo_MMO_0000000
- rdfs_label
- obo_PATO_0000001
- dc_identifier
- dct_alternative
- obo_PATO_0000047
- http___aopkb.org_aop_ontology#LifeStageContext
- dc_source
- obo_GO_0008150
class_uri: http://aopkb.org/aop_ontology#KeyEvent

```
</details>

### Induced

<details>

```yaml
name: http___aopkb.org_aop_ontology#KeyEvent
from_schema: okns:biobricks-aopwiki-kg
rank: 1000
attributes:
  rdfs_seeAlso:
    name: rdfs_seeAlso
    description: Further information about the subject resource.
    title: seeAlso
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:seeAlso
    alias: rdfs_seeAlso
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - dcam_VocabularyEncodingScheme
    - rdfs_Datatype
    - edam_data_1025
    - edam_data_2291
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    range: Any
    any_of:
    - range: rdfs_Resource
    - range: uri
  obo_PATO_0001241:
    name: obo_PATO_0001241
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: obo:PATO_0001241
    alias: obo_PATO_0001241
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    range: Any
    any_of:
    - range: http___aopkb.org_aop_ontology#CellTypeContext
    - range: http___aopkb.org_aop_ontology#OrganContext
    - range: uri
    - range: string
    - range: obo_GO_0008150
  http___purl.bioontology.org_ontology_NCBITAXON_131567:
    name: http___purl.bioontology.org_ontology_NCBITAXON_131567
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://purl.bioontology.org/ontology/NCBITAXON/131567
    alias: http___purl.bioontology.org_ontology_NCBITAXON_131567
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    range: Any
    any_of:
    - range: string
    - range: http___purl.bioontology.org_ontology_NCBITAXON_131567
  dct_isPartOf:
    name: dct_isPartOf
    description: This property is intended to be used with non-literal values. This
      property is an inverse property of Has Part.
    title: Is Part Of
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: A related resource in which the described resource is physically
      or logically included.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:isPartOf
    alias: dct_isPartOf
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    subproperty_of: dct_relation
    range: Any
  foaf_page:
    name: foaf_page
    description: A page or document about this thing.
    title: page
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:foaf
    source: http://xmlns.com/foaf/0.1/
    domain: owl_Thing
    slot_uri: foaf:page
    alias: foaf_page
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    inverse: foaf_topic
    range: foaf_Document
  dc_title:
    name: dc_title
    description: A name given to the resource.
    title: Title
    notes:
    - 'A [second property](/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/title)
      with the same name as this property has been declared in the [dcterms: namespace](http://purl.org/dc/terms/).  See
      the Introduction to the document [DCMI Metadata Terms](/specifications/dublin-core/dcmi-terms/)
      for an explanation.'
    - No occurrences of this slot in the graph.
    from_schema: okns:dc
    source: http://purl.org/dc/elements/1.1/
    slot_uri: dc:title
    alias: dc_title
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#CellTypeContext
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#OrganContext
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    - http___purl.bioontology.org_ontology_NCBITAXON_131567
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    - obo_GO_0008150
    range: Any
  dc_description:
    name: dc_description
    description: 'Description may include but is not limited to: an abstract, a table
      of contents, a graphical representation, or a free-text account of the resource.'
    title: Description
    notes:
    - 'A [second property](/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/description)
      with the same name as this property has been declared in the [dcterms: namespace](http://purl.org/dc/terms/).  See
      the Introduction to the document [DCMI Metadata Terms](/specifications/dublin-core/dcmi-terms/)
      for an explanation.'
    - No occurrences of this slot in the graph.
    comments:
    - 'description: An account of the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/elements/1.1/
    slot_uri: dc:description
    alias: dc_description
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    range: Any
  http___aopkb.org_aop_ontology#CellTypeContext:
    name: http___aopkb.org_aop_ontology#CellTypeContext
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://aopkb.org/aop_ontology#CellTypeContext
    alias: http___aopkb.org_aop_ontology#CellTypeContext
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    range: Any
    any_of:
    - range: string
    - range: http___aopkb.org_aop_ontology#CellTypeContext
  edam_data_1025:
    name: edam_data_1025
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: edam:data_1025
    alias: edam_data_1025
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    range: Any
    any_of:
    - range: edam_data_1025
    - range: edam_data_2298
  http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25664:
    name: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25664
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl#C25664
    alias: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C25664
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    range: string
  http___aopkb.org_aop_ontology#OrganContext:
    name: http___aopkb.org_aop_ontology#OrganContext
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://aopkb.org/aop_ontology#OrganContext
    alias: http___aopkb.org_aop_ontology#OrganContext
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    range: Any
    any_of:
    - range: string
    - range: http___aopkb.org_aop_ontology#OrganContext
  obo_MMO_0000000:
    name: obo_MMO_0000000
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: obo:MMO_0000000
    alias: obo_MMO_0000000
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
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
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - dcam_VocabularyEncodingScheme
    - dct_AgentClass
    - rdf_List
    - rdfs_Datatype
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
  obo_PATO_0000001:
    name: obo_PATO_0000001
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: obo:PATO_0000001
    alias: obo_PATO_0000001
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    range: string
  dc_identifier:
    name: dc_identifier
    description: Recommended practice is to identify the resource by means of a string
      conforming to an identification system.
    title: Identifier
    notes:
    - 'A [second property](/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/identifier)
      with the same name as this property has been declared in the [dcterms: namespace](http://purl.org/dc/terms/).  See
      the Introduction to the document [DCMI Metadata Terms](/specifications/dublin-core/dcmi-terms/)
      for an explanation.'
    - No occurrences of this slot in the graph.
    comments:
    - 'description: An unambiguous reference to the resource within a given context.'
    from_schema: okns:dc
    source: http://purl.org/dc/elements/1.1/
    slot_uri: dc:identifier
    alias: dc_identifier
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - edam_data_1025
    - edam_data_1027
    - edam_data_1033
    - edam_data_2291
    - edam_data_2298
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#CellTypeContext
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___aopkb.org_aop_ontology#OrganContext
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    - http___purl.bioontology.org_ontology_NCBITAXON_131567
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000140
    - http___semanticscience.org_resource_CHEMINF_000405
    - http___semanticscience.org_resource_CHEMINF_000406
    - http___semanticscience.org_resource_CHEMINF_000407
    - http___semanticscience.org_resource_CHEMINF_000408
    - http___semanticscience.org_resource_CHEMINF_000409
    - http___semanticscience.org_resource_CHEMINF_000412
    - http___semanticscience.org_resource_CHEMINF_000446
    - http___semanticscience.org_resource_CHEMINF_000564
    - http___semanticscience.org_resource_CHEMINF_000567
    - obo_GO_0008150
    range: Any
  dct_alternative:
    name: dct_alternative
    description: The distinction between titles and alternative titles is application-specific.
    title: Alternative Title
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: An alternative name for the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:alternative
    alias: dct_alternative
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    subproperty_of: dct_title
    range: rdfs_Literal
  obo_PATO_0000047:
    name: obo_PATO_0000047
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: obo:PATO_0000047
    alias: obo_PATO_0000047
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    range: string
  http___aopkb.org_aop_ontology#LifeStageContext:
    name: http___aopkb.org_aop_ontology#LifeStageContext
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://aopkb.org/aop_ontology#LifeStageContext
    alias: http___aopkb.org_aop_ontology#LifeStageContext
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    range: string
  dc_source:
    name: dc_source
    description: The described resource may be derived from the related resource in
      whole or in part. Recommended best practice is to identify the related resource
      by means of a string conforming to a formal identification system.
    title: Source
    notes:
    - 'A [second property](/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/source)
      with the same name as this property has been declared in the [dcterms: namespace](http://purl.org/dc/terms/).  See
      the Introduction to the document [DCMI Metadata Terms](/specifications/dublin-core/dcmi-terms/)
      for an explanation.'
    - No occurrences of this slot in the graph.
    comments:
    - 'description: A related resource from which the described resource is derived.'
    from_schema: okns:dc
    source: http://purl.org/dc/elements/1.1/
    slot_uri: dc:source
    alias: dc_source
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - edam_data_1025
    - edam_data_1027
    - edam_data_1033
    - edam_data_2291
    - edam_data_2298
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#CellTypeContext
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#OrganContext
    - http___purl.bioontology.org_ontology_NCBITAXON_131567
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000140
    - http___semanticscience.org_resource_CHEMINF_000405
    - http___semanticscience.org_resource_CHEMINF_000406
    - http___semanticscience.org_resource_CHEMINF_000407
    - http___semanticscience.org_resource_CHEMINF_000408
    - http___semanticscience.org_resource_CHEMINF_000409
    - http___semanticscience.org_resource_CHEMINF_000412
    - http___semanticscience.org_resource_CHEMINF_000446
    - http___semanticscience.org_resource_CHEMINF_000564
    - http___semanticscience.org_resource_CHEMINF_000567
    - obo_GO_0008150
    range: Any
  obo_GO_0008150:
    name: obo_GO_0008150
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: obo:GO_0008150
    alias: obo_GO_0008150
    owner: http___aopkb.org_aop_ontology#KeyEvent
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    range: obo_GO_0008150
class_uri: http://aopkb.org/aop_ontology#KeyEvent

```
</details>