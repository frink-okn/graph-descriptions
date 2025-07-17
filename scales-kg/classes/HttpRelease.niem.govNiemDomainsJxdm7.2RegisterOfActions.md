

# Class: No class (type) name specified (http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions)


_No class (type) description specified_






This class occurs 4159706 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions](http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions)






```mermaid
 classDiagram
    class HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions
    click HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions href "../HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions"
      HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions : http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions --> "0..1" Uri : http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    click Uri href "../Uri"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions : scales_DocketEntry
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction : scales_DocketEntry
    click HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction href "../HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified <br/>  | direct |  |
| [scales_DocketEntry](../slots/scales_DocketEntry.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) | No slot (predicate) description specified <br/>  | direct | 27914768 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) |
| [ScalesCase](../classes/ScalesCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [scales_DocketTable](../slots/scales_DocketTable.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [scales_DocketTable](../slots/scales_DocketTable.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 4159706
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slots:
- http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
- scales_DocketEntry
slot_usage:
  scales_DocketEntry:
    name: scales_DocketEntry
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        value: 27914768
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions

```
</details>

### Induced

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 4159706
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slot_usage:
  scales_DocketEntry:
    name: scales_DocketEntry
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        value: 27914768
attributes:
  http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    annotations:
      count:
        tag: count
        value: 30414852
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:DocketEntry/akd;;1:16-cr-00001_de0
        example_object_type: uri
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction
        example_subject: scales:DocketTable/akd;;1:16-cr-00001
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    - http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    range: uri
  scales_DocketEntry:
    name: scales_DocketEntry
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        value: 27914768
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:DocketEntry/ga-clayton-magistrate-civil;;0:00-cm-00001_de0
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
        example_predicate: scales:DocketEntry
        example_subject: scales:DocketTable/ga-clayton-magistrate-civil;;0:00-cm-00001
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:DocketEntry
    alias: scales_DocketEntry
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    range: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions

```
</details>