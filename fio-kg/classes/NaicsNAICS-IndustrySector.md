

# Class: No class (type) name specified (naics_NAICS-IndustrySector)


_No class (type) description specified_






This class occurs 24 times.


URI: [naics:NAICS-IndustrySector](http://sawgraph.spatialai.org/v1/fio/naics#NAICS-IndustrySector)






```mermaid
 classDiagram
    class NaicsNAICS-IndustrySector
    click NaicsNAICS-IndustrySector href "../NaicsNAICS-IndustrySector"
      NaicsNAICS-Industry <|-- NaicsNAICS-IndustrySector
        click NaicsNAICS-Industry href "../NaicsNAICS-Industry"
      
      NaicsNAICS-IndustrySector : fio_ofYear
        
          
    
    
    NaicsNAICS-IndustrySector --> "0..1" XsdGYear : fio_ofYear
    click XsdGYear href "../XsdGYear"

        
      NaicsNAICS-IndustrySector : fio_subcodeOf
        
          
    
    
    NaicsNAICS-IndustrySector --> "0..1" Any : fio_subcodeOf
    click Any href "../Any"

        
      NaicsNAICS-IndustrySector : owl_sameAs
        
          
    
    
    NaicsNAICS-IndustrySector --> "0..1" Any : owl_sameAs
    click Any href "../Any"

        
      NaicsNAICS-IndustrySector : rdfs_label
        
          
    
    
    NaicsNAICS-IndustrySector --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```





## Inheritance
* [FioIndustry](../classes/FioIndustry.md)
    * [NaicsNAICS-Industry](../classes/NaicsNAICS-Industry.md)
        * **NaicsNAICS-IndustrySector**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 24 |
| [fio_ofYear](../slots/fio_ofYear.md) | 0..1 <br/> [XsdGYear](../classes/XsdGYear.md) | No slot (predicate) description specified <br/>  | direct | 20 |
| [owl_sameAs](../slots/owl_sameAs.md) | 0..1 <br/> [FioIndustry](../classes/FioIndustry.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[RdfList](../classes/RdfList.md)&nbsp;or&nbsp;<br />[NaicsNAICS-Industry](../classes/NaicsNAICS-Industry.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No slot (predicate) description specified <br/>  | direct | 20 |
| [fio_subcodeOf](../slots/fio_subcodeOf.md) | 0..1 <br/> [NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md)&nbsp;or&nbsp;<br />[FioIndustry](../classes/FioIndustry.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[NaicsNAICS-Industry](../classes/NaicsNAICS-Industry.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No slot (predicate) description specified | [NaicsNAICS-Industry](../classes/NaicsNAICS-Industry.md), [FioIndustry](../classes/FioIndustry.md) |  |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [FioIndustry](../classes/FioIndustry.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [FioIndustry](../classes/FioIndustry.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [NaicsNAICS-Industry](../classes/NaicsNAICS-Industry.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [NaicsNAICS-Industry](../classes/NaicsNAICS-Industry.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlAllDifferent](../classes/OwlAllDifferent.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlAllDisjointClasses](../classes/OwlAllDisjointClasses.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlAllDisjointProperties](../classes/OwlAllDisjointProperties.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlAnnotation](../classes/OwlAnnotation.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlAxiom](../classes/OwlAxiom.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlNegativePropertyAssertion](../classes/OwlNegativePropertyAssertion.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlNothing](../classes/OwlNothing.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlNothing](../classes/OwlNothing.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlOntology](../classes/OwlOntology.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlThing](../classes/OwlThing.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [OwlThing](../classes/OwlThing.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [RdfList](../classes/RdfList.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |
| [RdfsResource](../classes/RdfsResource.md) | [owl_sameAs](../slots/owl_sameAs.md) | any_of[range] | [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: naics_NAICS-IndustrySector
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 24
description: No class (type) description specified
title: No class (type) name specified
from_schema: fio-kg
rank: 1000
is_a: naics_NAICS-Industry
slots:
- rdfs_label
- fio_ofYear
- owl_sameAs
slot_usage:
  fio_ofYear:
    name: fio_ofYear
    annotations:
      xsd_gYear:
        tag: xsd_gYear
        value: 20
  owl_sameAs:
    name: owl_sameAs
    annotations:
      fio_Industry:
        tag: fio_Industry
        value: 4
      naics_NAICS-Industry:
        tag: naics_NAICS-Industry
        value: 4
      naics_NAICS-IndustrySector:
        tag: naics_NAICS-IndustrySector
        value: 4
      owl_NamedIndividual:
        tag: owl_NamedIndividual
        value: 4
      owl_Thing:
        tag: owl_Thing
        value: 4
  rdfs_label:
    name: rdfs_label
    annotations:
      string:
        tag: string
        value: 24
class_uri: naics:NAICS-IndustrySector

```
</details>

### Induced

<details>

```yaml
name: naics_NAICS-IndustrySector
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 24
description: No class (type) description specified
title: No class (type) name specified
from_schema: fio-kg
rank: 1000
is_a: naics_NAICS-Industry
slot_usage:
  fio_ofYear:
    name: fio_ofYear
    annotations:
      xsd_gYear:
        tag: xsd_gYear
        value: 20
  owl_sameAs:
    name: owl_sameAs
    annotations:
      fio_Industry:
        tag: fio_Industry
        value: 4
      naics_NAICS-Industry:
        tag: naics_NAICS-Industry
        value: 4
      naics_NAICS-IndustrySector:
        tag: naics_NAICS-IndustrySector
        value: 4
      owl_NamedIndividual:
        tag: owl_NamedIndividual
        value: 4
      owl_Thing:
        tag: owl_Thing
        value: 4
  rdfs_label:
    name: rdfs_label
    annotations:
      string:
        tag: string
        value: 24
attributes:
  rdfs_label:
    name: rdfs_label
    annotations:
      string:
        tag: string
        value: 24
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: 'Agriculture: Agricultural Research Service'
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: fio:d.Agency.C1017
        example_subject_type: prov_Organization
    - object:
        example_object: 'Agriculture: Agricultural Research Service'
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: fio:d.Agency.C1017
        example_subject_type: fio_Agency
    - object:
        example_object: Soybean Farming
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: Soybean Farming
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: Soybean Farming
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_Thing
    - object:
        example_object: Soybean Farming
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: fio_Industry
    - object:
        example_object: Soybean Farming
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: Oilseed and Grain Farming
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: naics:NAICS-IndustryGroup-1111
        example_subject_type: naics_NAICS-IndustryGroup
    - object:
        example_object: Agriculture, Forestry, Fishing and Hunting
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: naics:NAICS-IndustrySector-11
        example_subject_type: naics_NAICS-IndustrySector
    - object:
        example_object: Crop Production
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: naics:NAICS-IndustrySubsector-111
        example_subject_type: naics_NAICS-IndustrySubsector
    - object:
        example_object: PRATT & WHITNEY
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110000314204
        example_subject_type: usfrs_Stationary-Facility
    - object:
        example_object: PRATT & WHITNEY
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110000314204
        example_subject_type: usfrs_FRS-Facility
    - object:
        example_object: PRATT & WHITNEY
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110000314204
        example_subject_type: fio_Facility
    - object:
        example_object: PRATT & WHITNEY
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110000314204
        example_subject_type: __b1
    - object:
        example_object: COOPER WIRING DEVICES
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110000314222
        example_subject_type: usfrs_EPA-PFAS-Facility
    - object:
        example_object: NASA JOHN H. GLENN RESEARCH CENTER - LEWIS FIELD
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110000387714
        example_subject_type: usfrs_Federal-Facility
    - object:
        example_object: BEHR DAYTON THERMAL SYSTEM VOC PLUME
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110000394635
        example_subject_type: usfrs_ContaminatedSite-Facility
    - object:
        example_object: NALCO CHEMICAL COMPANY
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110000888585
        example_subject_type: usfrs_PotentiallyContaminatedSite-Facility
    - object:
        example_object: BEALL MANUFACTURING
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110001347490
        example_subject_type: usfrs_BrownfieldsSite-Facility
    - object:
        example_object: DAYSPRING ASSISTED LIVING AND CARE
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110006216415
        example_subject_type: usfrs_WaterSystem-Facility
    - object:
        example_object: BOWERS LANDFILL
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110009304485
        example_subject_type: usfrs_ContaminationAddressed-Facility
    - object:
        example_object: RETRIEV TECHNOLOGIES INC
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110009668243
        example_subject_type: usfrs_Barge-Facility
    - object:
        example_object: REGIONAL OFFICE BUILDING
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110020787013
        example_subject_type: usfrs_MonitoringStation-Facility
    - object:
        example_object: DOUG GOTT & SONS, INC.
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110046118330
        example_subject_type: usfrs_Portable-Facility
    - object:
        example_object: AGRIUM TERMINAL
        example_object_type: string
        example_predicate: rdfs:label
        example_subject: usfrsdata:d.FRS-Facility.110063004323
        example_subject_type: usfrs_WaterfrontFacility-Facility
    from_schema: fio-kg
    rank: 1000
    domain: rdfs_label
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: naics_NAICS-IndustrySector
    domain_of:
    - __b1
    - fio_Agency
    - fio_Facility
    - fio_Industry
    - naics_NAICS-Industry
    - naics_NAICS-IndustryCode
    - naics_NAICS-IndustryGroup
    - naics_NAICS-IndustrySector
    - naics_NAICS-IndustrySubsector
    - owl_NamedIndividual
    - owl_Thing
    - prov_Organization
    - usfrs_Barge-Facility
    - usfrs_BrownfieldsSite-Facility
    - usfrs_ContaminatedSite-Facility
    - usfrs_ContaminationAddressed-Facility
    - usfrs_EPA-PFAS-Facility
    - usfrs_FRS-Facility
    - usfrs_Federal-Facility
    - usfrs_MonitoringStation-Facility
    - usfrs_Portable-Facility
    - usfrs_PotentiallyContaminatedSite-Facility
    - usfrs_Stationary-Facility
    - usfrs_WaterSystem-Facility
    - usfrs_WaterfrontFacility-Facility
    range: Any
    any_of:
    - range: uri
    - range: string
  fio_ofYear:
    name: fio_ofYear
    annotations:
      xsd_gYear:
        tag: xsd_gYear
        value: 20
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: '2022'
        example_object_type: xsd_gYear
        example_predicate: fio:ofYear
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: '2022'
        example_object_type: xsd_gYear
        example_predicate: fio:ofYear
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: '2022'
        example_object_type: xsd_gYear
        example_predicate: fio:ofYear
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_Thing
    - object:
        example_object: '2022'
        example_object_type: xsd_gYear
        example_predicate: fio:ofYear
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: fio_Industry
    - object:
        example_object: '2022'
        example_object_type: xsd_gYear
        example_predicate: fio:ofYear
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: '2022'
        example_object_type: xsd_gYear
        example_predicate: fio:ofYear
        example_subject: naics:NAICS-IndustryGroup-1111
        example_subject_type: naics_NAICS-IndustryGroup
    - object:
        example_object: '2022'
        example_object_type: xsd_gYear
        example_predicate: fio:ofYear
        example_subject: naics:NAICS-IndustrySector-11
        example_subject_type: naics_NAICS-IndustrySector
    - object:
        example_object: '2022'
        example_object_type: xsd_gYear
        example_predicate: fio:ofYear
        example_subject: naics:NAICS-IndustrySubsector-111
        example_subject_type: naics_NAICS-IndustrySubsector
    from_schema: fio-kg
    rank: 1000
    slot_uri: fio:ofYear
    alias: fio_ofYear
    owner: naics_NAICS-IndustrySector
    domain_of:
    - fio_Industry
    - naics_NAICS-Industry
    - naics_NAICS-IndustryCode
    - naics_NAICS-IndustryGroup
    - naics_NAICS-IndustrySector
    - naics_NAICS-IndustrySubsector
    - owl_NamedIndividual
    - owl_Thing
    range: xsd_gYear
  owl_sameAs:
    name: owl_sameAs
    annotations:
      fio_Industry:
        tag: fio_Industry
        value: 4
      naics_NAICS-Industry:
        tag: naics_NAICS-Industry
        value: 4
      naics_NAICS-IndustrySector:
        tag: naics_NAICS-IndustrySector
        value: 4
      owl_NamedIndividual:
        tag: owl_NamedIndividual
        value: 4
      owl_Thing:
        tag: owl_Thing
        value: 4
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
    owner: naics_NAICS-IndustrySector
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
  fio_subcodeOf:
    name: fio_subcodeOf
    annotations:
      fio_Industry:
        tag: fio_Industry
        value: 5815
      naics_NAICS-Industry:
        tag: naics_NAICS-Industry
        value: 5815
      naics_NAICS-IndustryGroup:
        tag: naics_NAICS-IndustryGroup
        value: 1701
      naics_NAICS-IndustrySector:
        tag: naics_NAICS-IndustrySector
        value: 2105
      naics_NAICS-IndustrySubsector:
        tag: naics_NAICS-IndustrySubsector
        value: 2009
      owl_NamedIndividual:
        tag: owl_NamedIndividual
        value: 5232
      owl_Thing:
        tag: owl_Thing
        value: 5232
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: naics_NAICS-IndustryGroup
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: naics_NAICS-Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: owl_Thing
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: fio_Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: owl_NamedIndividual
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: naics_NAICS-IndustryGroup
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: naics_NAICS-Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: owl_Thing
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: fio_Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: owl_NamedIndividual
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: naics_NAICS-IndustryGroup
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: naics_NAICS-Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: owl_Thing
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: fio_Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: owl_NamedIndividual
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: naics_NAICS-IndustryGroup
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: naics_NAICS-Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: owl_Thing
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: fio_Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: owl_NamedIndividual
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: naics_NAICS-IndustryGroup
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: naics_NAICS-Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: owl_Thing
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: fio_Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustryGroup-1111
        example_object_type: owl_NamedIndividual
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: naics_NAICS-IndustrySector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: naics_NAICS-IndustrySector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: naics_NAICS-IndustrySector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: naics_NAICS-IndustrySector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: naics_NAICS-IndustrySector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustrySubsector-111
        example_object_type: naics_NAICS-IndustrySubsector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-IndustryCode
    - object:
        example_object: naics:NAICS-IndustrySubsector-111
        example_object_type: naics_NAICS-IndustrySubsector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: naics_NAICS-Industry
    - object:
        example_object: naics:NAICS-IndustrySubsector-111
        example_object_type: naics_NAICS-IndustrySubsector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_Thing
    - object:
        example_object: naics:NAICS-IndustrySubsector-111
        example_object_type: naics_NAICS-IndustrySubsector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: fio_Industry
    - object:
        example_object: naics:NAICS-IndustrySubsector-111
        example_object_type: naics_NAICS-IndustrySubsector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryCode-11111
        example_subject_type: owl_NamedIndividual
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: naics_NAICS-Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryGroup-1111
        example_subject_type: naics_NAICS-IndustryGroup
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: owl_Thing
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryGroup-1111
        example_subject_type: naics_NAICS-IndustryGroup
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: naics_NAICS-IndustrySector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryGroup-1111
        example_subject_type: naics_NAICS-IndustryGroup
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: fio_Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryGroup-1111
        example_subject_type: naics_NAICS-IndustryGroup
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: owl_NamedIndividual
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryGroup-1111
        example_subject_type: naics_NAICS-IndustryGroup
    - object:
        example_object: naics:NAICS-IndustrySubsector-111
        example_object_type: naics_NAICS-IndustrySubsector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustryGroup-1111
        example_subject_type: naics_NAICS-IndustryGroup
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: naics_NAICS-Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustrySubsector-111
        example_subject_type: naics_NAICS-IndustrySubsector
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: owl_Thing
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustrySubsector-111
        example_subject_type: naics_NAICS-IndustrySubsector
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: naics_NAICS-IndustrySector
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustrySubsector-111
        example_subject_type: naics_NAICS-IndustrySubsector
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: fio_Industry
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustrySubsector-111
        example_subject_type: naics_NAICS-IndustrySubsector
    - object:
        example_object: naics:NAICS-IndustrySector-11
        example_object_type: owl_NamedIndividual
        example_predicate: fio:subcodeOf
        example_subject: naics:NAICS-IndustrySubsector-111
        example_subject_type: naics_NAICS-IndustrySubsector
    from_schema: fio-kg
    rank: 1000
    domain: fio_subcodeOf
    slot_uri: fio:subcodeOf
    alias: fio_subcodeOf
    owner: naics_NAICS-IndustrySector
    domain_of:
    - fio_Industry
    - naics_NAICS-Industry
    - naics_NAICS-IndustryCode
    - naics_NAICS-IndustryGroup
    - naics_NAICS-IndustrySubsector
    - owl_NamedIndividual
    - owl_Thing
    range: Any
    any_of:
    - range: naics_NAICS-IndustrySubsector
    - range: fio_Industry
    - range: owl_Thing
    - range: naics_NAICS-IndustryGroup
    - range: uri
    - range: naics_NAICS-Industry
    - range: naics_NAICS-IndustrySector
    - range: owl_NamedIndividual
class_uri: naics:NAICS-IndustrySector

```
</details>