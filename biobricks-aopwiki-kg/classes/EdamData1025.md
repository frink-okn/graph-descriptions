

# Class: EdamData1025




This class occurs 12500 times.


URI: [edam:data_1025](http://edamontology.org/data_1025)






```mermaid
 classDiagram
    class EdamData1025
    click EdamData1025 href "../EdamData1025"
      EdamData1025 : dc_identifier
        
          
    
    
    EdamData1025 --> "0..1" Any : dc_identifier
    click Any href "../Any"

        
      EdamData1025 : dc_source
        
          
    
    
    EdamData1025 --> "0..1" Any : dc_source
    click Any href "../Any"

        
      EdamData1025 : edam_data_1027
        
          
    
    
    EdamData1025 --> "0..1" String : edam_data_1027
    click String href "../String"

        
      EdamData1025 : edam_data_1033
        
          
    
    
    EdamData1025 --> "0..1" String : edam_data_1033
    click String href "../String"

        
      EdamData1025 : edam_data_2291
        
          
    
    
    EdamData1025 --> "0..1" String : edam_data_2291
    click String href "../String"

        
      EdamData1025 : edam_data_2298
        
          
    
    
    EdamData1025 --> "0..1" String : edam_data_2298
    click String href "../String"

        
      EdamData1025 : owl_sameAs
        
          
    
    
    EdamData1025 --> "0..1" OwlThing : owl_sameAs
    click OwlThing href "../OwlThing"

        
      EdamData1025 : rdfs_seeAlso
        
          
    
    
    EdamData1025 --> "0..1" Any : rdfs_seeAlso
    click Any href "../Any"

        
      EdamData1025 : skos_exactMatch
        
          
    
    
    EdamData1025 --> "0..1" Any : skos_exactMatch
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [rdfs_seeAlso](../slots/rdfs_seeAlso.md) | 0..1 <br/> [RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI) | Further information about the subject resource <br/>  | direct | 526 |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [OwlThing](../classes/OwlThing.md) | The property that determines that two given individuals are equal <br/>  | direct | 526 |
| [dc_identifier](../slots/dc_identifier.md) | 0..1 <br/> [Any](../classes/Any.md) | Recommended practice is to identify the resource by means of a string conform... <br/> description: An unambiguous reference to the resource within a given context. | direct | 12500 |
| [dc_source](../slots/dc_source.md) | 0..1 <br/> [Any](../classes/Any.md) | The described resource may be derived from the related resource in whole or i... <br/> description: A related resource from which the described resource is derived. | direct | 12500 |
| [edam_data_1033](../slots/edam_data_1033.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 1478 |
| [skos_exactMatch](../slots/skos_exactMatch.md) | 0..1 <br/> [Any](../classes/Any.md) | skos:exactMatch is used to link two concepts, indicating a high degree of con... <br/> description: skos:exactMatch is disjoint with each of the properties skos:broadMatch and skos:relatedMatch. | direct | 20790 |
| [edam_data_2298](../slots/edam_data_2298.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 1621 |
| [edam_data_2291](../slots/edam_data_2291.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 7883 |
| [edam_data_1027](../slots/edam_data_1027.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 1518 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpAopkb.orgAopOntology#KeyEvent](../classes/HttpAopkb.orgAopOntology#KeyEvent.md) | [EdamData1025](../classes/EdamData1025.md) | any_of[range] | [EdamData1025](../classes/EdamData1025.md) |
| [HttpAopkb.orgAopOntology#KeyEventRelationship](../classes/HttpAopkb.orgAopOntology#KeyEventRelationship.md) | [EdamData1025](../classes/EdamData1025.md) | any_of[range] | [EdamData1025](../classes/EdamData1025.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: edam_data_1025
from_schema: okns:biobricks-aopwiki-kg
rank: 1000
slots:
- rdfs_seeAlso
- owl_sameAs
- dc_identifier
- dc_source
- edam_data_1033
- skos_exactMatch
- edam_data_2298
- edam_data_2291
- edam_data_1027
class_uri: edam:data_1025

```
</details>

### Induced

<details>

```yaml
name: edam_data_1025
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
    owner: edam_data_1025
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
  owl_sameAs:
    name: owl_sameAs
    description: The property that determines that two given individuals are equal.
    title: sameAs
    notes:
    - No occurrences of this slot in the graph.
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2002/07/owl#
    domain: owl_Thing
    slot_uri: owl:sameAs
    alias: owl_sameAs
    owner: edam_data_1025
    domain_of:
    - edam_data_1025
    - edam_data_2291
    range: owl_Thing
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
    owner: edam_data_1025
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
    owner: edam_data_1025
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
  edam_data_1033:
    name: edam_data_1033
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: edam:data_1033
    alias: edam_data_1033
    owner: edam_data_1025
    domain_of:
    - edam_data_1025
    - edam_data_1033
    range: string
  skos_exactMatch:
    name: skos_exactMatch
    description: skos:exactMatch is used to link two concepts, indicating a high degree
      of confidence that the concepts can be used interchangeably across a wide range
      of information retrieval applications. skos:exactMatch is a transitive property,
      and is a sub-property of skos:closeMatch.
    title: has exact match
    notes:
    - No occurrences of this slot in the graph.
    comments:
    - 'description: skos:exactMatch is disjoint with each of the properties skos:broadMatch
      and skos:relatedMatch.'
    from_schema: okns:skos
    source: http://www.w3.org/2004/02/skos/core
    slot_uri: skos:exactMatch
    alias: skos_exactMatch
    owner: edam_data_1025
    domain_of:
    - edam_data_1025
    - edam_data_2298
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    subproperty_of: skos_closeMatch
    range: Any
  edam_data_2298:
    name: edam_data_2298
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: edam:data_2298
    alias: edam_data_2298
    owner: edam_data_1025
    domain_of:
    - edam_data_1025
    - edam_data_2298
    range: string
  edam_data_2291:
    name: edam_data_2291
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: edam:data_2291
    alias: edam_data_2291
    owner: edam_data_1025
    domain_of:
    - edam_data_1025
    - edam_data_2291
    range: string
  edam_data_1027:
    name: edam_data_1027
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: edam:data_1027
    alias: edam_data_1027
    owner: edam_data_1025
    domain_of:
    - edam_data_1025
    - edam_data_1027
    range: string
class_uri: edam:data_1025

```
</details>