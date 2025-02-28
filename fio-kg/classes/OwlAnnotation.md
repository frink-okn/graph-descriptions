

# Class: No class (type) name specified (owl_Annotation)


_No class (type) description specified_






This class occurs 0 times.


URI: [owl:Annotation](http://www.w3.org/2002/07/owl#Annotation)






```mermaid
 classDiagram
    class OwlAnnotation
    click OwlAnnotation href "../OwlAnnotation"
      RdfsResource <|-- OwlAnnotation
        click RdfsResource href "../RdfsResource"
      
      OwlAnnotation : owl_sameAs
        
          
    
    
    OwlAnnotation --> "0..1" Any : owl_sameAs
    click Any href "../Any"

        
      
```





## Inheritance
* [RdfsResource](../classes/RdfsResource.md)
    * **OwlAnnotation**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [FioIndustry](../classes/FioIndustry.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[RdfList](../classes/RdfList.md)&nbsp;or&nbsp;<br />[NaicsNAICS-Industry](../classes/NaicsNAICS-Industry.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No slot (predicate) description specified | [RdfsResource](../classes/RdfsResource.md) |  |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: owl_Annotation
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 0
description: No class (type) description specified
title: No class (type) name specified
from_schema: fio-kg
rank: 1000
is_a: rdfs_Resource
class_uri: owl:Annotation

```
</details>

### Induced

<details>

```yaml
name: owl_Annotation
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 0
description: No class (type) description specified
title: No class (type) name specified
from_schema: fio-kg
rank: 1000
is_a: rdfs_Resource
attributes:
  owl_sameAs:
    name: owl_sameAs
    annotations:
      owl_Thing:
        tag: owl_Thing
        value: 2
      rdf_List:
        tag: rdf_List
        value: 1
      rdfs_Resource:
        tag: rdfs_Resource
        value: 2
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: naics_NAICS-IndustryCode
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: naics_NAICS-Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: owl_Thing
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: fio_Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: owl_NamedIndividual
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: naics_NAICS-IndustryCode
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: naics_NAICS-Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: owl_Thing
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: fio_Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: owl_NamedIndividual
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: naics_NAICS-IndustryCode
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: naics_NAICS-Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: owl_Thing
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: fio_Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: owl_NamedIndividual
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: naics_NAICS-IndustryCode
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: naics_NAICS-Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: owl_Thing
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: fio_Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: owl_NamedIndividual
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: naics_NAICS-IndustryCode
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: naics_NAICS-Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: owl_Thing
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: fio_Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustryCode-11111
        example_object_type: owl_NamedIndividual
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustryCode-111110
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustrySector-31
        example_object_type: naics_NAICS-IndustrySector
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustrySector-32
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustrySector-31
        example_object_type: naics_NAICS-IndustrySector
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustrySector-32
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustrySector-31
        example_object_type: naics_NAICS-Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustrySector-32
        example_subject_type: naics_NAICS-IndustrySector
    - object:
        example_object: naics:NAICS-IndustrySector-31
        example_object_type: owl_Thing
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustrySector-32
        example_subject_type: naics_NAICS-IndustrySector
    - object:
        example_object: naics:NAICS-IndustrySector-31
        example_object_type: naics_NAICS-IndustrySector
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustrySector-32
        example_subject_type: naics_NAICS-IndustrySector
    - object:
        example_object: naics:NAICS-IndustrySector-31
        example_object_type: fio_Industry
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustrySector-32
        example_subject_type: naics_NAICS-IndustrySector
    - object:
        example_object: naics:NAICS-IndustrySector-31
        example_object_type: owl_NamedIndividual
        example_predicate: owl:sameAs
        example_subject: naics:NAICS-IndustrySector-32
        example_subject_type: naics_NAICS-IndustrySector
    - object:
        example_object: rdf:ObjectProperty
        example_object_type: rdfs_Resource
        example_predicate: owl:sameAs
        example_subject: rdf:ObjectProperty
        example_subject_type: owl_Thing
    - object:
        example_object: rdf:ObjectProperty
        example_object_type: owl_Thing
        example_predicate: owl:sameAs
        example_subject: rdf:ObjectProperty
        example_subject_type: rdfs_Resource
    - object:
        example_object: rdf:ObjectProperty
        example_object_type: rdfs_Resource
        example_predicate: owl:sameAs
        example_subject: rdf:ObjectProperty
        example_subject_type: rdfs_Resource
    - object:
        example_object: rdf:nil
        example_object_type: rdf_List
        example_predicate: owl:sameAs
        example_subject: rdf:nil
        example_subject_type: owl_Thing
    - object:
        example_object: rdf:nil
        example_object_type: rdfs_Resource
        example_predicate: owl:sameAs
        example_subject: rdf:nil
        example_subject_type: rdf_List
    - object:
        example_object: rdf:nil
        example_object_type: owl_Thing
        example_predicate: owl:sameAs
        example_subject: rdf:nil
        example_subject_type: rdf_List
    - object:
        example_object: rdf:nil
        example_object_type: rdf_List
        example_predicate: owl:sameAs
        example_subject: rdf:nil
        example_subject_type: rdf_List
    - object:
        example_object: rdf:nil
        example_object_type: rdf_List
        example_predicate: owl:sameAs
        example_subject: rdf:nil
        example_subject_type: rdfs_Resource
    from_schema: fio-kg
    rank: 1000
    domain: owl_sameAs
    slot_uri: owl:sameAs
    alias: owl_sameAs
    owner: owl_Annotation
    domain_of:
    - fio_Industry
    - naics_NAICS-Industry
    - naics_NAICS-IndustryCode
    - naics_NAICS-IndustrySector
    - owl_NamedIndividual
    - owl_Thing
    - rdf_List
    - rdfs_Resource
    range: Any
    any_of:
    - range: fio_Industry
    - range: owl_Thing
    - range: uri
    - range: naics_NAICS-IndustryCode
    - range: rdfs_Resource
    - range: rdf_List
    - range: naics_NAICS-Industry
    - range: naics_NAICS-IndustrySector
    - range: owl_NamedIndividual
class_uri: owl:Annotation

```
</details>