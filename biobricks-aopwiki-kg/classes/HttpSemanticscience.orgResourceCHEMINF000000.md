

# Class: HttpSemanticscience.orgResourceCHEMINF000000




This class occurs 391 times.


URI: [http://semanticscience.org/resource/CHEMINF_000000](http://semanticscience.org/resource/CHEMINF_000000)






```mermaid
 classDiagram
    class HttpSemanticscience.orgResourceCHEMINF000000
    click HttpSemanticscience.orgResourceCHEMINF000000 href "../HttpSemanticscience.orgResourceCHEMINF000000"
      HttpSemanticscience.orgResourceCHEMINF000000 : dc_identifier
        
          
    
    
    HttpSemanticscience.orgResourceCHEMINF000000 --> "0..1" Any : dc_identifier
    click Any href "../Any"

        
      HttpSemanticscience.orgResourceCHEMINF000000 : dc_source
        
          
    
    
    HttpSemanticscience.orgResourceCHEMINF000000 --> "0..1" Any : dc_source
    click Any href "../Any"

        
      HttpSemanticscience.orgResourceCHEMINF000000 : dc_title
        
          
    
    
    HttpSemanticscience.orgResourceCHEMINF000000 --> "0..1" Any : dc_title
    click Any href "../Any"

        
      HttpSemanticscience.orgResourceCHEMINF000000 : dct_alternative
        
          
    
    
    HttpSemanticscience.orgResourceCHEMINF000000 --> "0..1" RdfsLiteral : dct_alternative
    click RdfsLiteral href "../RdfsLiteral"

        
      HttpSemanticscience.orgResourceCHEMINF000000 : dct_isPartOf
        
          
    
    
    HttpSemanticscience.orgResourceCHEMINF000000 --> "0..1" Any : dct_isPartOf
    click Any href "../Any"

        
      HttpSemanticscience.orgResourceCHEMINF000000 : http___semanticscience.org_resource_CHEMINF_000059
        
          
    
    
    HttpSemanticscience.orgResourceCHEMINF000000 --> "0..1" Uri : http___semanticscience.org_resource_CHEMINF_000059
    click Uri href "../Uri"

        
      HttpSemanticscience.orgResourceCHEMINF000000 : http___semanticscience.org_resource_CHEMINF_000446
        
          
    
    
    HttpSemanticscience.orgResourceCHEMINF000000 --> "0..1" String : http___semanticscience.org_resource_CHEMINF_000446
    click String href "../String"

        
      HttpSemanticscience.orgResourceCHEMINF000000 : http___semanticscience.org_resource_CHEMINF_000568
        
          
    
    
    HttpSemanticscience.orgResourceCHEMINF000000 --> "0..1" Uri : http___semanticscience.org_resource_CHEMINF_000568
    click Uri href "../Uri"

        
      HttpSemanticscience.orgResourceCHEMINF000000 : skos_exactMatch
        
          
    
    
    HttpSemanticscience.orgResourceCHEMINF000000 --> "0..1" Any : skos_exactMatch
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [dct_isPartOf](../slots/dct_isPartOf.md) | 0..1 <br/> [Any](../classes/Any.md) | This property is intended to be used with non-literal values <br/> description: A related resource in which the described resource is physically or logically included. | direct | 397 |
| [dc_identifier](../slots/dc_identifier.md) | 0..1 <br/> [Any](../classes/Any.md) | Recommended practice is to identify the resource by means of a string conform... <br/> description: An unambiguous reference to the resource within a given context. | direct | 782 |
| [skos_exactMatch](../slots/skos_exactMatch.md) | 0..1 <br/> [Any](../classes/Any.md) | skos:exactMatch is used to link two concepts, indicating a high degree of con... <br/> description: skos:exactMatch is disjoint with each of the properties skos:broadMatch and skos:relatedMatch. | direct | 3297 |
| [dct_alternative](../slots/dct_alternative.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md) | The distinction between titles and alternative titles is application-specific <br/> description: An alternative name for the resource. | direct | 13157 |
| [dc_source](../slots/dc_source.md) | 0..1 <br/> [Any](../classes/Any.md) | The described resource may be derived from the related resource in whole or i... <br/> description: A related resource from which the described resource is derived. | direct | 391 |
| [dc_title](../slots/dc_title.md) | 0..1 <br/> [Any](../classes/Any.md) | A name given to the resource <br/>  | direct | 391 |
| [http___semanticscience.org_resource_CHEMINF_000059](../slots/http___semanticscience.org_resource_CHEMINF_000059.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) |  <br/>  | direct | 375 |
| [http___semanticscience.org_resource_CHEMINF_000568](../slots/http___semanticscience.org_resource_CHEMINF_000568.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) |  <br/>  | direct | 391 |
| [http___semanticscience.org_resource_CHEMINF_000446](../slots/http___semanticscience.org_resource_CHEMINF_000446.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 391 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571](../classes/HttpNcicb.nci.nih.govXmlOwlEVSThesaurus.owl#C54571.md) | [http___aopkb.org_aop_ontology#has_chemical_entity](../slots/http___aopkb.org_aop_ontology#has_chemical_entity.md) | any_of[range] | [HttpSemanticscience.orgResourceCHEMINF000000](../classes/HttpSemanticscience.orgResourceCHEMINF000000.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___semanticscience.org_resource_CHEMINF_000000
from_schema: okns:biobricks-aopwiki-kg
rank: 1000
slots:
- dct_isPartOf
- dc_identifier
- skos_exactMatch
- dct_alternative
- dc_source
- dc_title
- http___semanticscience.org_resource_CHEMINF_000059
- http___semanticscience.org_resource_CHEMINF_000568
- http___semanticscience.org_resource_CHEMINF_000446
class_uri: http://semanticscience.org/resource/CHEMINF_000000

```
</details>

### Induced

<details>

```yaml
name: http___semanticscience.org_resource_CHEMINF_000000
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
    owner: http___semanticscience.org_resource_CHEMINF_000000
    domain_of:
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___aopkb.org_aop_ontology#KeyEventRelationship
    - http___ncicb.nci.nih.gov_xml_owl_EVS_Thesaurus.owl#C54571
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    subproperty_of: dct_relation
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
    owner: http___semanticscience.org_resource_CHEMINF_000000
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
    owner: http___semanticscience.org_resource_CHEMINF_000000
    domain_of:
    - edam_data_1025
    - edam_data_2298
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    subproperty_of: skos_closeMatch
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
    owner: http___semanticscience.org_resource_CHEMINF_000000
    domain_of:
    - http___aopkb.org_aop_ontology#AdverseOutcomePathway
    - http___aopkb.org_aop_ontology#KeyEvent
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    subproperty_of: dct_title
    range: rdfs_Literal
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
    owner: http___semanticscience.org_resource_CHEMINF_000000
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
    owner: http___semanticscience.org_resource_CHEMINF_000000
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
  http___semanticscience.org_resource_CHEMINF_000059:
    name: http___semanticscience.org_resource_CHEMINF_000059
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://semanticscience.org/resource/CHEMINF_000059
    alias: http___semanticscience.org_resource_CHEMINF_000059
    owner: http___semanticscience.org_resource_CHEMINF_000000
    domain_of:
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    range: uri
  http___semanticscience.org_resource_CHEMINF_000568:
    name: http___semanticscience.org_resource_CHEMINF_000568
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://semanticscience.org/resource/CHEMINF_000568
    alias: http___semanticscience.org_resource_CHEMINF_000568
    owner: http___semanticscience.org_resource_CHEMINF_000000
    domain_of:
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    range: uri
  http___semanticscience.org_resource_CHEMINF_000446:
    name: http___semanticscience.org_resource_CHEMINF_000446
    from_schema: okns:biobricks-aopwiki-kg
    rank: 1000
    slot_uri: http://semanticscience.org/resource/CHEMINF_000446
    alias: http___semanticscience.org_resource_CHEMINF_000446
    owner: http___semanticscience.org_resource_CHEMINF_000000
    domain_of:
    - http___semanticscience.org_resource_CHEMINF_000000
    - http___semanticscience.org_resource_CHEMINF_000446
    range: string
class_uri: http://semanticscience.org/resource/CHEMINF_000000

```
</details>