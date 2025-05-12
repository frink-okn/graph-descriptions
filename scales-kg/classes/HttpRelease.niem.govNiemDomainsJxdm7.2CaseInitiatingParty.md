

# Class: No class (type) name specified (http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty)


_No class (type) description specified_






This class occurs 5633 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty](http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty)






```mermaid
 classDiagram
    class HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty
    click HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty href "../HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty"
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty : http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney : http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
    click HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney href "../HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty : http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty --> "0..1" String : http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty : niem50_EntityName
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty --> "0..1" String : niem50_EntityName
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty : scales_hasExtraInfo
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty --> "0..1" String : scales_hasExtraInfo
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty : scales_hasPartyReferenceInExtraInfo
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty --> "0..1" Uri : scales_hasPartyReferenceInExtraInfo
    click Uri href "../Uri"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty : scales_isInstanceOfEntity
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty --> "0..1" Any : scales_isInstanceOfEntity
    click Any href "../Any"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [scales_isInstanceOfEntity](../slots/scales_isInstanceOfEntity.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md) | No slot (predicate) description specified <br/>  | direct | 3765 |
| [scales_hasPartyReferenceInExtraInfo](../slots/scales_hasPartyReferenceInExtraInfo.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified <br/>  | direct | 12 |
| [niem50_EntityName](../slots/niem50_EntityName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 5633 |
| [scales_hasExtraInfo](../slots/scales_hasExtraInfo.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 539 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 5633 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney.md) | No slot (predicate) description specified <br/>  | direct | 9088 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) |
| [ScalesCase](../classes/ScalesCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 5633
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slots:
- scales_isInstanceOfEntity
- scales_hasPartyReferenceInExtraInfo
- niem50_EntityName
- scales_hasExtraInfo
- http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
        value: 9088
  http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    annotations:
      string:
        tag: string
        value: 5633
  niem50_EntityName:
    name: niem50_EntityName
    annotations:
      string:
        tag: string
        value: 5633
  scales_hasExtraInfo:
    name: scales_hasExtraInfo
    annotations:
      string:
        tag: string
        value: 539
  scales_hasPartyReferenceInExtraInfo:
    name: scales_hasPartyReferenceInExtraInfo
    annotations:
      uri:
        tag: uri
        value: 12
  scales_isInstanceOfEntity:
    name: scales_isInstanceOfEntity
    annotations:
      uri:
        tag: uri
        value: 3765
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty

```
</details>

### Induced

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 5633
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
        value: 9088
  http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    annotations:
      string:
        tag: string
        value: 5633
  niem50_EntityName:
    name: niem50_EntityName
    annotations:
      string:
        tag: string
        value: 5633
  scales_hasExtraInfo:
    name: scales_hasExtraInfo
    annotations:
      string:
        tag: string
        value: 539
  scales_hasPartyReferenceInExtraInfo:
    name: scales_hasPartyReferenceInExtraInfo
    annotations:
      uri:
        tag: uri
        value: 12
  scales_isInstanceOfEntity:
    name: scales_isInstanceOfEntity
    annotations:
      uri:
        tag: uri
        value: 3765
attributes:
  scales_isInstanceOfEntity:
    name: scales_isInstanceOfEntity
    annotations:
      uri:
        tag: uri
        value: 3765
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/PartyEntity/SPID-GOVERNMENT-ST-025-000001969
        example_object_type: uri
        example_predicate: scales:isInstanceOfEntity
        example_subject: scales:/Agent/casd;;3:16-cv-01644_a1
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: scales:/JudgeEntity/SJ002053
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
        example_predicate: scales:isInstanceOfEntity
        example_subject: scales:/Agent/casd;;3:17-cr-03540_a2
        example_subject_type: None
    - object:
        example_object: scales:/PartyEntity/SPID-INDUSTRY-ST-020-000011105
        example_object_type: uri
        example_predicate: scales:isInstanceOfEntity
        example_subject: scales:/Agent/casd;;3:16-cv-01645_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - object:
        example_object: scales:/PartyEntity/SPID-INDUSTRY-ST-008-000022280
        example_object_type: uri
        example_predicate: scales:isInstanceOfEntity
        example_subject: scales:/Agent/casd;;3:16-cv-01645_a3
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:isInstanceOfEntity
    alias: scales_isInstanceOfEntity
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - scales_Party
    range: Any
    any_of:
    - range: uri
    - range: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
  scales_hasPartyReferenceInExtraInfo:
    name: scales_hasPartyReferenceInExtraInfo
    annotations:
      uri:
        tag: uri
        value: 12
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/PartyEntity/SPID-INDUSTRY-ST-010-000002068
        example_object_type: uri
        example_predicate: scales:hasPartyReferenceInExtraInfo
        example_subject: scales:/Agent/casd;;3:16-cv-01667_a1
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: scales:/PartyEntity/SPID-INDUSTRY-ST-016-000023681
        example_object_type: uri
        example_predicate: scales:hasPartyReferenceInExtraInfo
        example_subject: scales:/Agent/casd;;3:16-cv-01713_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasPartyReferenceInExtraInfo
    alias: scales_hasPartyReferenceInExtraInfo
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    range: uri
  niem50_EntityName:
    name: niem50_EntityName
    annotations:
      string:
        tag: string
        value: 5633
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: SCALES-Party-Hash-A832763C1FE77A32B6DE912B9C77F80C
        example_object_type: string
        example_predicate: niem50:EntityName
        example_subject: scales:/Agent/casd;;3:16-cv-01644_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - object:
        example_object: USA
        example_object_type: string
        example_predicate: niem50:EntityName
        example_subject: scales:/Agent/casd;;3:16-cv-01644_a1
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: Revolar, Inc.
        example_object_type: string
        example_predicate: niem50:EntityName
        example_subject: scales:/Agent/casd;;3:16-cv-01645_a3
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:EntityName
    alias: niem50_EntityName
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - scales_Party
    range: string
  scales_hasExtraInfo:
    name: scales_hasExtraInfo
    annotations:
      string:
        tag: string
        value: 539
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: a Delaware limited liability company
        example_object_type: string
        example_predicate: scales:hasExtraInfo
        example_subject: scales:/Agent/casd;;3:16-cv-01645_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - object:
        example_object: a Delaware corporation
        example_object_type: string
        example_predicate: scales:hasExtraInfo
        example_subject: scales:/Agent/casd;;3:16-cv-01645_a1
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: a Delaware corporation
        example_object_type: string
        example_predicate: scales:hasExtraInfo
        example_subject: scales:/Agent/casd;;3:16-cv-01645_a3
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasExtraInfo
    alias: scales_hasExtraInfo
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - scales_Party
    range: string
  http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    annotations:
      string:
        tag: string
        value: 5633
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Petitioner
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
        example_subject: scales:/Agent/casd;;3:16-cv-01644_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - object:
        example_object: Respondent
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
        example_subject: scales:/Agent/casd;;3:16-cv-01644_a1
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: Counter Claimant
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
        example_subject: scales:/Agent/casd;;3:16-cv-01645_a3
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - scales_Party
    range: string
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
        value: 9088
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Agent/casd;;3:16-cv-01644_a3
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingAttorney
        example_subject: scales:/Agent/casd;;3:16-cv-01644_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingAttorney
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty

```
</details>