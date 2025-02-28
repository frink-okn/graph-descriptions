

# Class: No class (type) name specified (http___sawgraph.spatialai.org_v1_fio#Agency)


_No class (type) description specified_





URI: [http://sawgraph.spatialai.org/v1/fio#Agency](http://sawgraph.spatialai.org/v1/fio#Agency)






```mermaid
 classDiagram
    class HttpSawgraph.spatialai.orgV1Fio#Agency
    click HttpSawgraph.spatialai.orgV1Fio#Agency href "../HttpSawgraph.spatialai.orgV1Fio#Agency"
      ProvOrganization <|-- HttpSawgraph.spatialai.orgV1Fio#Agency
        click ProvOrganization href "../ProvOrganization"
      
      HttpSawgraph.spatialai.orgV1Fio#Agency : rdfs_label
        
          
    
    
    HttpSawgraph.spatialai.orgV1Fio#Agency --> "0..1" Any : rdfs_label
    click Any href "../Any"

        
      
```





## Inheritance
* [ProvOrganization](../classes/ProvOrganization.md)
    * **HttpSawgraph.spatialai.orgV1Fio#Agency**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [rdfs_label](../slots/rdfs_label.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [B1](../classes/B1.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [HttpSawgraph.spatialai.orgV1Fio#Facility](../classes/HttpSawgraph.spatialai.orgV1Fio#Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsBarge-Facility](../classes/UsfrsBarge-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsBrownfieldsSite-Facility](../classes/UsfrsBrownfieldsSite-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsContaminatedSite-Facility](../classes/UsfrsContaminatedSite-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsContaminationAddressed-Facility](../classes/UsfrsContaminationAddressed-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsEPA-PFAS-Facility](../classes/UsfrsEPA-PFAS-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsFederal-Facility](../classes/UsfrsFederal-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsMonitoringStation-Facility](../classes/UsfrsMonitoringStation-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsPortable-Facility](../classes/UsfrsPortable-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsPotentiallyContaminatedSite-Facility](../classes/UsfrsPotentiallyContaminatedSite-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsStationary-Facility](../classes/UsfrsStationary-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsWaterSystem-Facility](../classes/UsfrsWaterSystem-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |
| [UsfrsWaterfrontFacility-Facility](../classes/UsfrsWaterfrontFacility-Facility.md) | [http___sawgraph.spatialai.org_v1_fio#ofAgency](../slots/http___sawgraph.spatialai.org_v1_fio#ofAgency.md) | any_of[range] | [HttpSawgraph.spatialai.orgV1Fio#Agency](../classes/HttpSawgraph.spatialai.orgV1Fio#Agency.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: fio-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | http://sawgraph.spatialai.org/v1/fio#Agency |
| native | fio-kg/:HttpSawgraph.spatialai.orgV1Fio#Agency |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: http___sawgraph.spatialai.org_v1_fio#Agency
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 15 occurrences.
from_schema: fio-kg
rank: 1000
is_a: prov_Organization
slots:
- rdfs_label
class_uri: http://sawgraph.spatialai.org/v1/fio#Agency

```
</details>

### Induced

<details>
```yaml
name: http___sawgraph.spatialai.org_v1_fio#Agency
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 15 occurrences.
from_schema: fio-kg
rank: 1000
is_a: prov_Organization
attributes:
  rdfs_label:
    name: rdfs_label
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    comments:
    - 15 occurrences with subject type http___sawgraph.spatialai.org_v1_fio#Agency
      and object type string.
    - 2129 occurrences with subject type http___sawgraph.spatialai.org_v1_fio#Industry
      and object type string.
    - 300917 occurrences with subject type __b1 and object type string.
    examples:
    - value: 'http://sawgraph.spatialai.org/v1/fio#d.Agency.C1017 rdfs:label Agriculture:
        Agricultural Research Service'
    - value: naics:NAICS-IndustryCode-11111 rdfs:label Soybean Farming
    - value: usfrsdata:d.FRS-Facility.110000314204 rdfs:label PRATT & WHITNEY
    from_schema: fio-kg
    rank: 1000
    domain: rdfs_Resource
    slot_uri: rdfs:label
    alias: rdfs_label
    owner: http___sawgraph.spatialai.org_v1_fio#Agency
    domain_of:
    - __b1
    - http___sawgraph.spatialai.org_v1_fio#Agency
    - http___sawgraph.spatialai.org_v1_fio#Industry
    range: Any
    any_of:
    - range: uri
    - range: string
class_uri: http://sawgraph.spatialai.org/v1/fio#Agency

```
</details>