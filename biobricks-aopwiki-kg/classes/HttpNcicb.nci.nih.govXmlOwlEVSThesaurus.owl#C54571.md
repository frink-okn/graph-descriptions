

# Class: HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571




This class occurs 658 times.


URI: [http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl#C54571](http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl#C54571)






```mermaid
 classDiagram
    class HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571
    click HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 href "../HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571"
      HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 : dc_description
        
          
    
    
    HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 --> "0..1" Any : dc_description
    click Any href "../Any"

        
      HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 : dc_identifier
        
          
    
    
    HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 --> "0..1" Any : dc_identifier
    click Any href "../Any"

        
      HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 : dc_title
        
          
    
    
    HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 --> "0..1" Any : dc_title
    click Any href "../Any"

        
      HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 : dct_created
        
          
    
    
    HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 --> "0..1" RdfsLiteral : dct_created
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 : dct_isPartOf
        
          
    
    
    HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 --> "0..1" Any : dct_isPartOf
    click Any href "../Any"

        
      HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 : dct_modified
        
          
    
    
    HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 --> "0..1" Any : dct_modified
    click Any href "../Any"

        
      HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 : foaf_page
        
          
    
    
    HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 --> "0..1" FoafDocument : foaf_page
    click FoafDocument href "../FoafDocument"

        
      HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 : http___aopkb.org_aop_ontology#has_chemical_entity
        
          
    
    
    HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 --> "0..1" Any : http___aopkb.org_aop_ontology#has_chemical_entity
    click Any href "../Any"

        
      HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 : rdfs_label
        
          
    
    
    HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571 --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___aopkb.org_aop_ontology#has_chemical_entity](../slots/http___aopkb.org_aop_ontology#has_chemical_entity.md) | 0..1 <br/> [xsd:string](xsd:string)&nbsp;or&nbsp;<br />[HttpSemanticscience.orgResourceCHEMINF000000](../classes/HttpSemanticscience.orgResourceCHEMINF000000.md)&nbsp;or&nbsp;<br />[HttpSemanticscience.orgResourceCHEMINF000446](../classes/HttpSemanticscience.orgResourceCHEMINF000446.md) |  <br/>  | direct | 800 |
| [foaf_page](../slots/foaf_page.md) | 0..1 <br/> [FoafDocument](../classes/FoafDocument.md) | A page or document about this thing <br/>  | direct | 658 |
| [dc_identifier](../slots/dc_identifier.md) | 0..1 <br/> [Any](../classes/Any.md) | Recommended practice is to identify the resource by means of a string conform... <br/> description: An unambiguous reference to the resource within a given context. | direct | 658 |
| [dc_title](../slots/dc_title.md) | 0..1 <br/> [Any](../classes/Any.md) | A name given to the resource <br/>  | direct | 658 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](xsd:string) | A human-readable name for the subject <br/>  | direct | 658 |
| [dct_isPartOf](../slots/dct_isPartOf.md) | 0..1 <br/> [Any](../classes/Any.md) | This property is intended to be used with non-literal values <br/> description: A related resource in which the described resource is physically or logically included. | direct | 603 |
| [dc_description](../slots/dc_description.md) | 0..1 <br/> [Any](../classes/Any.md) | Description may include but is not limited to: an abstract, a table of conten... <br/> description: An account of the resource. | direct | 16 |
| [dct_created](../slots/dct_created.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | Recommended practice is to describe the date, date/time, or period of time as... <br/> description: Date of creation of the resource. | direct | 658 |
| [dct_modified](../slots/dct_modified.md) | 0..1 <br/> [xsd:date](xsd:date)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md) | Recommended practice is to describe the date, date/time, or period of time as... <br/> description: Date on which the resource was changed. | direct | 658 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpAopkb.orgAopOntology#AdverseOutcomePathway](../classes/HttpAopkb.orgAopOntology#AdverseOutcomePathway.md) | [HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571](../classes/HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571.md) | range | [HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571](../classes/HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
from_schema: okns:biobricks-aopwiki-kg
rank: 1000
slots:
- http___aopkb.org_aop_ontology#has_chemical_entity
- foaf_page
- dc_identifier
- dc_title
- rdfs_label
- dct_isPartOf
- dc_description
- dct_created
- dct_modified
class_uri: http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl#C54571

```
</details>

### Induced

<details>

```yaml
name: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
from_schema: okns:biobricks-aopwiki-kg
rank: 1000
attributes:
  http___aopkb.org_aop_ontology#has_chemical_entity:
    name: http___aopkb.org_aop_ontology#has_chemical_entity
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://aopkb.org/aop_ontology#has_chemical_entity
    alias: http___aopkb.org_aop_ontology#has_chemical_entity
    owner: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    domain_of:
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    range: Any
    any_of:
    - range: string
    - range: http___semanticscience.org_resource_CHEMINF_000000
    - range: http___semanticscience.org_resource_CHEMINF_000446
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
    owner: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    inverse: foaf_topic
    range: foaf_Document
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
    owner: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
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
    owner: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
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
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
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
    owner: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    subproperty_of: dct_relation
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
    owner: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    range: Any
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
    owner: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    subproperty_of: dct_date
    range: rdfs_Literal
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
    owner: http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    subproperty_of: dct_date
    range: Any
    any_of:
    - range: date
    - range: rdfs_Literal
class_uri: http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl#C54571

```
</details>