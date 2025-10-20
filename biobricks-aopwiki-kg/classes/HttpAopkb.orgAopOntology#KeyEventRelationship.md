

# Class: HttpAopkb.orgAopOntology#KeyEventRelationship




This class occurs 2060 times.


URI: [http://aopkb.org/aop_ontology#KeyEventRelationship](http://aopkb.org/aop_ontology#KeyEventRelationship)






```mermaid
 classDiagram
    class HttpAopkb.orgAopOntology#KeyEventRelationship
    click HttpAopkb.orgAopOntology#KeyEventRelationship href "../HttpAopkb.orgAopOntology#KeyEventRelationship"
      HttpAopkb.orgAopOntology#KeyEventRelationship : dc_description
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" Any : dc_description
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : dc_identifier
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" Any : dc_identifier
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : dct_created
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" RdfsLiteral : dct_created
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : dct_isPartOf
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" Any : dct_isPartOf
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : dct_modified
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" Any : dct_modified
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : edam_data_1025
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" Any : edam_data_1025
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : edam_data_2042
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" String : edam_data_2042
    click String href "../String"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : foaf_page
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" FoafDocument : foaf_page
    click FoafDocument href "../FoafDocument"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : http___aopkb.org_aop_ontology#has_downstream_key_event
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" HttpAopkb.orgAopOntology#KeyEvent : http___aopkb.org_aop_ontology#has_downstream_key_event
    click HttpAopkb.orgAopOntology#KeyEvent href "../HttpAopkb.orgAopOntology#KeyEvent"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : http___aopkb.org_aop_ontology#has_upstream_key_event
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" HttpAopkb.orgAopOntology#KeyEvent : http___aopkb.org_aop_ontology#has_upstream_key_event
    click HttpAopkb.orgAopOntology#KeyEvent href "../HttpAopkb.orgAopOntology#KeyEvent"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C71478
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" String : http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C71478
    click String href "../String"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C80263
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" String : http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C80263
    click String href "../String"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : rdfs_label
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      HttpAopkb.orgAopOntology#KeyEventRelationship : rdfs_seeAlso
        
          
    
    
    HttpAopkb.orgAopOntology#KeyEventRelationship --> "0..1" Any : rdfs_seeAlso
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [dct_isPartOf](../slots/dct_isPartOf.md) | 0..1 <br/> [Any](../classes/Any.md) | This property is intended to be used with non-literal values <br/> description: A related resource in which the described resource is physically or logically included. | direct | 2778 |
| [http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C71478](../slots/http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C71478.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 515 |
| [rdfs_seeAlso](../slots/rdfs_seeAlso.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI) | Further information about the subject resource <br/>  | direct | 2060 |
| [dc_identifier](../slots/dc_identifier.md) | 0..1 <br/> [Any](../classes/Any.md) | Recommended practice is to identify the resource by means of a string conform... <br/> description: An unambiguous reference to the resource within a given context. | direct | 2060 |
| [foaf_page](../slots/foaf_page.md) | 0..1 <br/> [FoafDocument](../classes/FoafDocument.md) | A page or document about this thing <br/>  | direct | 2060 |
| [dc_description](../slots/dc_description.md) | 0..1 <br/> [Any](../classes/Any.md) | Description may include but is not limited to: an abstract, a table of conten... <br/> description: An account of the resource. | direct | 633 |
| [http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C80263](../slots/http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C80263.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 623 |
| [http___aopkb.org_aop_ontology#has_upstream_key_event](../slots/http___aopkb.org_aop_ontology#has_upstream_key_event.md) | 0..1 <br/> [HttpAopkb.orgAopOntology#KeyEvent](../classes/HttpAopkb.orgAopOntology#KeyEvent.md) |  <br/>  | direct | 2060 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](xsd:string) | A human-readable name for the subject <br/>  | direct | 2060 |
| [http___aopkb.org_aop_ontology#has_downstream_key_event](../slots/http___aopkb.org_aop_ontology#has_downstream_key_event.md) | 0..1 <br/> [HttpAopkb.orgAopOntology#KeyEvent](../classes/HttpAopkb.orgAopOntology#KeyEvent.md) |  <br/>  | direct | 2060 |
| [edam_data_2042](../slots/edam_data_2042.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 613 |
| [dct_modified](../slots/dct_modified.md) | 0..1 <br/> [xsd:date](xsd:date)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md) | Recommended practice is to describe the date, date/time, or period of time as... <br/> description: Date on which the resource was changed. | direct | 2060 |
| [edam_data_1025](../slots/edam_data_1025.md) | 0..1 <br/> [EdamData1025](../classes/EdamData1025.md)&nbsp;or&nbsp;<br />[EdamData2298](../classes/EdamData2298.md) |  <br/>  | direct | 7818 |
| [dct_created](../slots/dct_created.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Recommended practice is to describe the date, date/time, or period of time as... <br/> description: Date of creation of the resource. | direct | 2060 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpAopkb.orgAopOntology#AdverseOutcomePathway](../classes/HttpAopkb.orgAopOntology#AdverseOutcomePathway.md) | [http___aopkb.org_aop_ontology#has_key_event_relationship](../slots/http___aopkb.org_aop_ontology#has_key_event_relationship.md) | range | [HttpAopkb.orgAopOntology#KeyEventRelationship](../classes/HttpAopkb.orgAopOntology#KeyEventRelationship.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___aopkb.org_aop_ontology#KeyEventRelationship
from_schema: okns:biobricks-aopwiki-kg
rank: 1000
slots:
- dct_isPartOf
- http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C71478
- rdfs_seeAlso
- dc_identifier
- foaf_page
- dc_description
- http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C80263
- http___aopkb.org_aop_ontology#has_upstream_key_event
- rdfs_label
- http___aopkb.org_aop_ontology#has_downstream_key_event
- edam_data_2042
- dct_modified
- edam_data_1025
- dct_created
class_uri: http://aopkb.org/aop_ontology#KeyEventRelationship

```
</details>

### Induced

<details>

```yaml
name: http___aopkb.org_aop_ontology#KeyEventRelationship
from_schema: okns:biobricks-aopwiki-kg
rank: 1000
attributes:
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
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    subproperty_of: dct_relation
    range: Any
  http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C71478:
    name: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C71478
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl#C71478
    alias: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C71478
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    range: string
  rdfs_seeAlso:
    name: rdfs_seeAlso
    description: Further information about the subject resource.
    title: seeAlso
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:seeAlso
    alias: rdfs_seeAlso
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
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
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
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
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    inverse: foaf_topic
    range: foaf_Document
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
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    range: Any
  http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C80263:
    name: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C80263
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl#C80263
    alias: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C80263
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    range: string
  http___aopkb.org_aop_ontology#has_upstream_key_event:
    name: http___aopkb.org_aop_ontology#has_upstream_key_event
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://aopkb.org/aop_ontology#has_upstream_key_event
    alias: http___aopkb.org_aop_ontology#has_upstream_key_event
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    range: http___aopkb.org_aop_ontology#KeyEvent
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
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
  http___aopkb.org_aop_ontology#has_downstream_key_event:
    name: http___aopkb.org_aop_ontology#has_downstream_key_event
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://aopkb.org/aop_ontology#has_downstream_key_event
    alias: http___aopkb.org_aop_ontology#has_downstream_key_event
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    range: http___aopkb.org_aop_ontology#KeyEvent
  edam_data_2042:
    name: edam_data_2042
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: edam:data_2042
    alias: edam_data_2042
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    range: string
  dct_modified:
    name: dct_modified
    description: Recommended practice is to describe the date, date/time, or period
      of time as recommended for the property Date, of which this is a subproperty.
    title: Date Modified
    comments:
    - 'description: Date on which the resource was changed.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:modified
    alias: dct_modified
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    subproperty_of: dct_date
    range: Any
    any_of:
    - range: date
    - range: rdfs_Literal
  edam_data_1025:
    name: edam_data_1025
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: edam:data_1025
    alias: edam_data_1025
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    range: Any
    any_of:
    - range: edam_data_1025
    - range: edam_data_2298
  dct_created:
    name: dct_created
    description: Recommended practice is to describe the date, date/time, or period
      of time as recommended for the property Date, of which this is a subproperty.
    title: Date Created
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: Date of creation of the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/terms/
    slot_uri: dct:created
    alias: dct_created
    owner: http___aopkb.org_aop_ontology#KeyEventRelationship
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    subproperty_of: dct_date
    range: rdfs_Literal
class_uri: http://aopkb.org/aop_ontology#KeyEventRelationship

```
</details>