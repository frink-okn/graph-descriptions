

# Class: HttpsW3id.orgBiolinkVocabStudy




This class occurs 140 times.


URI: [https://w3id.org/biolink/vocab/Study](https://w3id.org/biolink/vocab/Study)






```mermaid
 classDiagram
    class HttpsW3id.orgBiolinkVocabStudy
    click HttpsW3id.orgBiolinkVocabStudy href "../HttpsW3id.orgBiolinkVocabStudy"
      HttpsW3id.orgBiolinkVocabStudy : https___purl.org_okn_frink_kg_spoke_genelab_schema_organism
        
          
    
    
    HttpsW3id.orgBiolinkVocabStudy --> "0..1" String : https___purl.org_okn_frink_kg_spoke_genelab_schema_organism
    click String href "../String"

        
      HttpsW3id.orgBiolinkVocabStudy : https___purl.org_okn_frink_kg_spoke_genelab_schema_PERFORMED_SpAS
        
          
    
    
    HttpsW3id.orgBiolinkVocabStudy --> "0..1" OboOBI0000070 : https___purl.org_okn_frink_kg_spoke_genelab_schema_PERFORMED_SpAS
    click OboOBI0000070 href "../OboOBI0000070"

        
      HttpsW3id.orgBiolinkVocabStudy : https___purl.org_okn_frink_kg_spoke_genelab_schema_project_title
        
          
    
    
    HttpsW3id.orgBiolinkVocabStudy --> "0..1" String : https___purl.org_okn_frink_kg_spoke_genelab_schema_project_title
    click String href "../String"

        
      HttpsW3id.orgBiolinkVocabStudy : https___purl.org_okn_frink_kg_spoke_genelab_schema_project_type
        
          
    
    
    HttpsW3id.orgBiolinkVocabStudy --> "0..1" String : https___purl.org_okn_frink_kg_spoke_genelab_schema_project_type
    click String href "../String"

        
      HttpsW3id.orgBiolinkVocabStudy : https___purl.org_okn_frink_kg_spoke_genelab_schema_taxonomy
        
          
    
    
    HttpsW3id.orgBiolinkVocabStudy --> "0..1" Any : https___purl.org_okn_frink_kg_spoke_genelab_schema_taxonomy
    click Any href "../Any"

        
      HttpsW3id.orgBiolinkVocabStudy : rdfs_comment
        
          
    
    
    HttpsW3id.orgBiolinkVocabStudy --> "0..1" Any : rdfs_comment
    click Any href "../Any"

        
      HttpsW3id.orgBiolinkVocabStudy : rdfs_label
        
          
    
    
    HttpsW3id.orgBiolinkVocabStudy --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [https___purl.org_okn_frink_kg_spoke_genelab_schema_project_title](../slots/https___purl.org_okn_frink_kg_spoke_genelab_schema_project_title.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 76 |
| [https___purl.org_okn_frink_kg_spoke_genelab_schema_organism](../slots/https___purl.org_okn_frink_kg_spoke_genelab_schema_organism.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 140 |
| [https___purl.org_okn_frink_kg_spoke_genelab_schema_project_type](../slots/https___purl.org_okn_frink_kg_spoke_genelab_schema_project_type.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 140 |
| [https___purl.org_okn_frink_kg_spoke_genelab_schema_taxonomy](../slots/https___purl.org_okn_frink_kg_spoke_genelab_schema_taxonomy.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) |  <br/>  | direct | 140 |
| [https___purl.org_okn_frink_kg_spoke_genelab_schema_PERFORMED_SpAS](../slots/https___purl.org_okn_frink_kg_spoke_genelab_schema_PERFORMED_SpAS.md) | 0..1 <br/> [OboOBI0000070](../classes/OboOBI0000070.md) |  <br/>  | direct | 6467 |
| [rdfs_comment](../slots/rdfs_comment.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A description of the subject resource <br/>  | direct | 140 |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | A human-readable name for the subject <br/>  | direct | 140 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpsPurl.orgOknFrinkKgSpoke-genelabSchemaMission](../classes/HttpsPurl.orgOknFrinkKgSpoke-genelabSchemaMission.md) | [https___purl.org_okn_frink_kg_spoke_genelab_schema_CONDUCTED_MIcS](../slots/https___purl.org_okn_frink_kg_spoke_genelab_schema_CONDUCTED_MIcS.md) | range | [HttpsW3id.orgBiolinkVocabStudy](../classes/HttpsW3id.orgBiolinkVocabStudy.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: https___w3id.org_biolink_vocab_Study
from_schema: okns:spoke-genelab
rank: 1000
slots:
- https___purl.org_okn_frink_kg_spoke-genelab_schema_project_title
- https___purl.org_okn_frink_kg_spoke-genelab_schema_organism
- https___purl.org_okn_frink_kg_spoke-genelab_schema_project_type
- https___purl.org_okn_frink_kg_spoke-genelab_schema_taxonomy
- https___purl.org_okn_frink_kg_spoke-genelab_schema_PERFORMED_SpAS
- rdfs_comment
- rdfs_label
class_uri: https://w3id.org/biolink/vocab/Study

```
</details>

### Induced

<details>

```yaml
name: https___w3id.org_biolink_vocab_Study
from_schema: okns:spoke-genelab
rank: 1000
attributes:
  https___purl.org_okn_frink_kg_spoke-genelab_schema_project_title:
    name: https___purl.org_okn_frink_kg_spoke-genelab_schema_project_title
    from_schema: okns:spoke-genelab
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke-genelab/schema/project_title
    alias: https___purl.org_okn_frink_kg_spoke_genelab_schema_project_title
    owner: https___w3id.org_biolink_vocab_Study
    domain_of:
    - https___purl.org_okn_frink_kg_spoke-genelab_schema_MetaNode
    - https___w3id.org_biolink_vocab_Study
    range: string
  https___purl.org_okn_frink_kg_spoke-genelab_schema_organism:
    name: https___purl.org_okn_frink_kg_spoke-genelab_schema_organism
    from_schema: okns:spoke-genelab
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke-genelab/schema/organism
    alias: https___purl.org_okn_frink_kg_spoke_genelab_schema_organism
    owner: https___w3id.org_biolink_vocab_Study
    domain_of:
    - https___purl.org_okn_frink_kg_spoke-genelab_schema_MetaNode
    - https___w3id.org_biolink_vocab_Gene
    - https___w3id.org_biolink_vocab_Study
    range: string
  https___purl.org_okn_frink_kg_spoke-genelab_schema_project_type:
    name: https___purl.org_okn_frink_kg_spoke-genelab_schema_project_type
    from_schema: okns:spoke-genelab
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke-genelab/schema/project_type
    alias: https___purl.org_okn_frink_kg_spoke_genelab_schema_project_type
    owner: https___w3id.org_biolink_vocab_Study
    domain_of:
    - https___purl.org_okn_frink_kg_spoke-genelab_schema_MetaNode
    - https___w3id.org_biolink_vocab_Study
    range: string
  https___purl.org_okn_frink_kg_spoke-genelab_schema_taxonomy:
    name: https___purl.org_okn_frink_kg_spoke-genelab_schema_taxonomy
    from_schema: okns:spoke-genelab
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke-genelab/schema/taxonomy
    alias: https___purl.org_okn_frink_kg_spoke_genelab_schema_taxonomy
    owner: https___w3id.org_biolink_vocab_Study
    domain_of:
    - https___purl.org_okn_frink_kg_spoke-genelab_schema_MetaNode
    - https___w3id.org_biolink_vocab_Gene
    - https___w3id.org_biolink_vocab_Study
    range: Any
    any_of:
    - range: uri
    - range: string
  https___purl.org_okn_frink_kg_spoke-genelab_schema_PERFORMED_SpAS:
    name: https___purl.org_okn_frink_kg_spoke-genelab_schema_PERFORMED_SpAS
    from_schema: okns:spoke-genelab
    rank: 1000
    slot_uri: https://purl.org/okn/frink/kg/spoke-genelab/schema/PERFORMED_SpAS
    alias: https___purl.org_okn_frink_kg_spoke_genelab_schema_PERFORMED_SpAS
    owner: https___w3id.org_biolink_vocab_Study
    domain_of:
    - https___w3id.org_biolink_vocab_Study
    range: obo_OBI_0000070
  rdfs_comment:
    name: rdfs_comment
    description: A description of the subject resource.
    title: comment
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:comment
    alias: rdfs_comment
    owner: https___w3id.org_biolink_vocab_Study
    domain_of:
    - rdf_List
    - rdfs_Datatype
    - https___purl.org_okn_frink_kg_spoke-genelab_schema_MetaNode
    - https___w3id.org_biolink_vocab_Study
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
  rdfs_label:
    name: rdfs_label
    description: A human-readable name for the subject.
    title: label
    from_schema: okns:owl-rdf-rdfs
    source: http://www.w3.org/2000/01/rdf-schema#
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: https___w3id.org_biolink_vocab_Study
    domain_of:
    - rdf_List
    - rdfs_Datatype
    - https___purl.org_okn_frink_kg_spoke-genelab_schema_MetaNode
    - https___purl.org_okn_frink_kg_spoke-genelab_schema_MethylationRegion
    - https___purl.org_okn_frink_kg_spoke-genelab_schema_Mission
    - https___w3id.org_biolink_vocab_Gene
    - https___w3id.org_biolink_vocab_Study
    - obo_OBI_0000070
    range: Any
    any_of:
    - range: rdfs_Literal
    - range: string
class_uri: https://w3id.org/biolink/vocab/Study

```
</details>