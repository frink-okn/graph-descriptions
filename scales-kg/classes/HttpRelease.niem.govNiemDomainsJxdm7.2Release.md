

# Class: No class (type) name specified (http___release.niem.gov_niem_domains_jxdm_7.2_Release)


_No class (type) description specified_






This class occurs 347084 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/Release](http://release.niem.gov/niem/domains/jxdm/7.2/Release)






```mermaid
 classDiagram
    class HttpRelease.niem.govNiemDomainsJxdm7.2Release
    click HttpRelease.niem.govNiemDomainsJxdm7.2Release href "../HttpRelease.niem.govNiemDomainsJxdm7.2Release"
      HttpRelease.niem.govNiemDomainsJxdm7.2Release : niem50_ActivityDate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Release --> "0..1" Date : niem50_ActivityDate
    click Date href "../Date"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [niem50_ActivityDate](../slots/niem50_ActivityDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) | No slot (predicate) description specified <br/>  | direct | 400567 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Booking](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Booking.md) | [http___release.niem.gov_niem_domains_jxdm_7.2_BookingRelease](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_BookingRelease.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2Release](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Release.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_Release
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 347084
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slots:
- niem50_ActivityDate
slot_usage:
  niem50_ActivityDate:
    name: niem50_ActivityDate
    annotations:
      date:
        tag: date
        value: 400567
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/Release

```
</details>

### Induced

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_Release
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 347084
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slot_usage:
  niem50_ActivityDate:
    name: niem50_ActivityDate
    annotations:
      date:
        tag: date
        value: 400567
attributes:
  niem50_ActivityDate:
    name: niem50_ActivityDate
    annotations:
      date:
        tag: date
        value: 400567
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '2018-04-18'
        example_object_type: date
        example_predicate: niem50:ActivityDate
        example_subject: scales:Booking/ga-fulton-01/10000019
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Booking
    - object:
        example_object: '2018-04-18'
        example_object_type: date
        example_predicate: niem50:ActivityDate
        example_subject: scales:Release/ga-fulton-01/10000019
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Release
    - object:
        example_object: '2014-05-03'
        example_object_type: date
        example_predicate: niem50:ActivityDate
        example_subject: scales:Arrest/ga-atlanta-pd-100720495
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Arrest
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:ActivityDate
    alias: niem50_ActivityDate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Release
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Arrest
    - http___release.niem.gov_niem_domains_jxdm_7.2_Booking
    - http___release.niem.gov_niem_domains_jxdm_7.2_Release
    range: date
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/Release

```
</details>