

# Class: HttpWww.w3.orgNsOa#Annotation




This class occurs 10718093 times.


URI: [http://www.w3.org/ns/oa#Annotation](http://www.w3.org/ns/oa#Annotation)






```mermaid
 classDiagram
    class HttpWww.w3.orgNsOa#Annotation
    click HttpWww.w3.orgNsOa#Annotation href "../HttpWww.w3.orgNsOa#Annotation"
      HttpWww.w3.orgNsOa#Annotation : dc_subject
        
          
    
    
    HttpWww.w3.orgNsOa#Annotation --> "0..1" Any : dc_subject
    click Any href "../Any"

        
      HttpWww.w3.orgNsOa#Annotation : http___www.w3.org_ns_oa#hasBody
        
          
    
    
    HttpWww.w3.orgNsOa#Annotation --> "0..1" Uri : http___www.w3.org_ns_oa#hasBody
    click Uri href "../Uri"

        
      HttpWww.w3.orgNsOa#Annotation : http___www.w3.org_ns_oa#hasTarget
        
          
    
    
    HttpWww.w3.orgNsOa#Annotation --> "0..1" Uri : http___www.w3.org_ns_oa#hasTarget
    click Uri href "../Uri"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___www.w3.org_ns_oa#hasTarget](../slots/http___www.w3.org_ns_oa#hasTarget.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) |  <br/>  | direct | 17550399 |
| [http___www.w3.org_ns_oa#hasBody](../slots/http___www.w3.org_ns_oa#hasBody.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) |  <br/>  | direct | 10718093 |
| [dc_subject](../slots/dc_subject.md) | 0..1 <br/> [Any](../classes/Any.md) | Typically, the subject will be represented using keywords, key phrases, or cl... <br/> description: The topic of the resource. | direct | 17550399 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___www.w3.org_ns_oa#Annotation
from_schema: okns:biobricks-pubchem-annotations-kg
rank: 1000
slots:
- http___www.w3.org_ns_oa#hasTarget
- http___www.w3.org_ns_oa#hasBody
- dc_subject
class_uri: http://www.w3.org/ns/oa#Annotation

```
</details>

### Induced

<details>

```yaml
name: http___www.w3.org_ns_oa#Annotation
from_schema: okns:biobricks-pubchem-annotations-kg
rank: 1000
attributes:
  http___www.w3.org_ns_oa#hasTarget:
    name: http___www.w3.org_ns_oa#hasTarget
    from_schema: okns:biobricks-pubchem-annotations-kg
    rank: 1000
    slot_uri: http://www.w3.org/ns/oa#hasTarget
    alias: http___www.w3.org_ns_oa#hasTarget
    owner: http___www.w3.org_ns_oa#Annotation
    domain_of:
    - http___www.w3.org_ns_oa#Annotation
    range: uri
  http___www.w3.org_ns_oa#hasBody:
    name: http___www.w3.org_ns_oa#hasBody
    from_schema: okns:biobricks-pubchem-annotations-kg
    rank: 1000
    slot_uri: http://www.w3.org/ns/oa#hasBody
    alias: http___www.w3.org_ns_oa#hasBody
    owner: http___www.w3.org_ns_oa#Annotation
    domain_of:
    - http___www.w3.org_ns_oa#Annotation
    range: uri
  dc_subject:
    name: dc_subject
    description: Typically, the subject will be represented using keywords, key phrases,
      or classification codes.  Recommended best practice is to use a controlled vocabulary.
    title: Subject
    notes:
    - 'A [second property](/specifications/dublin-core/dcmi-terms/#http://purl.org/dc/terms/subject)
      with the same name as this property has been declared in the [dcterms: namespace](http://purl.org/dc/terms/).  See
      the Introduction to the document [DCMI Metadata Terms](/specifications/dublin-core/dcmi-terms/)
      for an explanation.'
    - No occurrences of this slot in the graph.
    comments:
    - 'description: The topic of the resource.'
    from_schema: okns:dc
    source: http://purl.org/dc/elements/1.1/
    slot_uri: dc:subject
    alias: dc_subject
    owner: http___www.w3.org_ns_oa#Annotation
    domain_of:
    - http___www.w3.org_ns_oa#Annotation
    range: Any
class_uri: http://www.w3.org/ns/oa#Annotation

```
</details>