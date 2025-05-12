

# Class: No class (type) name specified (http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction)


_No class (type) description specified_






This class occurs 4999 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction](http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction)






```mermaid
 classDiagram
    class HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction
    click HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction href "../HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction"
      HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction : http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction --> "0..1" Uri : http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    click Uri href "../Uri"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified <br/>  | direct | 182022 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) |
| [ScalesCase](../classes/ScalesCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 4999
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slots:
- http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    annotations:
      uri:
        tag: uri
        value: 182022
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction

```
</details>

### Induced

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 4999
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    annotations:
      uri:
        tag: uri
        value: 182022
attributes:
  http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    annotations:
      uri:
        tag: uri
        value: 182022
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/DocketEntry/casd;;3:16-cv-01644_de0
        example_object_type: uri
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction
        example_subject: scales:/DocketTable/casd;;3:16-cv-01644
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    - object:
        example_object: scales:/DocketEntry/casd;;3:16-cv-01644_de0
        example_object_type: uri
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction
        example_subject: scales:/DocketTable/casd;;3:16-cv-01644
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    - http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    range: uri
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction

```
</details>