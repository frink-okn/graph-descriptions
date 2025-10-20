

# Class: EdamData2298




This class occurs 1621 times.


URI: [edam:data_2298](http://edamontology.org/data_2298)






```mermaid
 classDiagram
    class EdamData2298
    click EdamData2298 href "../EdamData2298"
      EdamData2298 : dc_identifier
        
          
    
    
    EdamData2298 --> "0..1" Any : dc_identifier
    click Any href "../Any"

        
      EdamData2298 : dc_source
        
          
    
    
    EdamData2298 --> "0..1" Any : dc_source
    click Any href "../Any"

        
      EdamData2298 : edam_data_2298
        
          
    
    
    EdamData2298 --> "0..1" String : edam_data_2298
    click String href "../String"

        
      EdamData2298 : skos_exactMatch
        
          
    
    
    EdamData2298 --> "0..1" Any : skos_exactMatch
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [edam_data_2298](../slots/edam_data_2298.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 1621 |
| [dc_source](../slots/dc_source.md) | 0..1 <br/> [Any](../classes/Any.md) | The described resource may be derived from the related resource in whole or i... <br/> description: A related resource from which the described resource is derived. | direct | 1621 |
| [dc_identifier](../slots/dc_identifier.md) | 0..1 <br/> [Any](../classes/Any.md) | Recommended practice is to identify the resource by means of a string conform... <br/> description: An unambiguous reference to the resource within a given context. | direct | 1621 |
| [skos_exactMatch](../slots/skos_exactMatch.md) | 0..1 <br/> [Any](../classes/Any.md) | skos:exactMatch is used to link two concepts, indicating a high degree of con... <br/> description: skos:exactMatch is disjoint with each of the properties skos:broadMatch and skos:relatedMatch. | direct | 20790 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpAopkb.orgAopOntology#KeyEvent](../classes/HttpAopkb.orgAopOntology#KeyEvent.md) | [EdamData1025](../classes/EdamData1025.md) | any_of[range] | [EdamData2298](../classes/EdamData2298.md) |
| [HttpAopkb.orgAopOntology#KeyEventRelationship](../classes/HttpAopkb.orgAopOntology#KeyEventRelationship.md) | [EdamData1025](../classes/EdamData1025.md) | any_of[range] | [EdamData2298](../classes/EdamData2298.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: edam_data_2298
from_schema: okns:biobricks-aopwiki-kg
rank: 1000
slots:
- edam_data_2298
- dc_source
- dc_identifier
- skos_exactMatch
class_uri: edam:data_2298

```
</details>

### Induced

<details>

```yaml
name: edam_data_2298
from_schema: okns:biobricks-aopwiki-kg
rank: 1000
attributes:
  edam_data_2298:
    name: edam_data_2298
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: edam:data_2298
    alias: edam_data_2298
    owner: edam_data_2298
    domain_of:
    - edam_data_1025
    - edam_data_2298
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
    owner: edam_data_2298
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
    owner: edam_data_2298
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
    owner: edam_data_2298
    domain_of:
    - edam_data_1025
    - edam_data_2298
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    subproperty_of: skos_closeMatch
    range: Any
class_uri: edam:data_2298

```
</details>