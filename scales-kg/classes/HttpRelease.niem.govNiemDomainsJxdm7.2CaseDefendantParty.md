

# Class: No class (type) name specified (http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty)


_No class (type) description specified_






This class occurs 2586246 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty](http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty)






```mermaid
 classDiagram
    class HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty
    click HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty href "../HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty"
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty : http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney : http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
    click HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney href "../HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty : http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty --> "0..1" String : http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty : http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2Charge : http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
    click HttpRelease.niem.govNiemDomainsJxdm7.2Charge href "../HttpRelease.niem.govNiemDomainsJxdm7.2Charge"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty : niem50_EntityName
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty --> "0..1" String : niem50_EntityName
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty : scales_hasExtraInfo
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty --> "0..1" String : scales_hasExtraInfo
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty : scales_hasHighestOffenseLevelOpening
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty --> "0..1" String : scales_hasHighestOffenseLevelOpening
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty : scales_hasHighestOffenseLevelTerminated
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty --> "0..1" String : scales_hasHighestOffenseLevelTerminated
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [niem50_EntityName](../slots/niem50_EntityName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2586246 |
| [scales_hasHighestOffenseLevelTerminated](../slots/scales_hasHighestOffenseLevelTerminated.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 69523 |
| [scales_hasHighestOffenseLevelOpening](../slots/scales_hasHighestOffenseLevelOpening.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 159337 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney.md) | No slot (predicate) description specified <br/>  | direct | 2823772 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No slot (predicate) description specified <br/>  | direct | 389366 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 2586246 |
| [scales_hasExtraInfo](../slots/scales_hasExtraInfo.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 671599 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |
| [ScalesCase](../classes/ScalesCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 2586246
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slots:
- niem50_EntityName
- scales_hasHighestOffenseLevelTerminated
- scales_hasHighestOffenseLevelOpening
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
- http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
- scales_hasExtraInfo
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
        value: 2823772
  http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    annotations:
      string:
        tag: string
        value: 2586246
  http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 389366
  niem50_EntityName:
    name: niem50_EntityName
    annotations:
      string:
        tag: string
        value: 2586246
  scales_hasExtraInfo:
    name: scales_hasExtraInfo
    annotations:
      string:
        tag: string
        value: 671599
  scales_hasHighestOffenseLevelOpening:
    name: scales_hasHighestOffenseLevelOpening
    annotations:
      string:
        tag: string
        value: 159337
  scales_hasHighestOffenseLevelTerminated:
    name: scales_hasHighestOffenseLevelTerminated
    annotations:
      string:
        tag: string
        value: 69523
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty

```
</details>

### Induced

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 2586246
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
        value: 2823772
  http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    annotations:
      string:
        tag: string
        value: 2586246
  http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 389366
  niem50_EntityName:
    name: niem50_EntityName
    annotations:
      string:
        tag: string
        value: 2586246
  scales_hasExtraInfo:
    name: scales_hasExtraInfo
    annotations:
      string:
        tag: string
        value: 671599
  scales_hasHighestOffenseLevelOpening:
    name: scales_hasHighestOffenseLevelOpening
    annotations:
      string:
        tag: string
        value: 159337
  scales_hasHighestOffenseLevelTerminated:
    name: scales_hasHighestOffenseLevelTerminated
    annotations:
      string:
        tag: string
        value: 69523
attributes:
  niem50_EntityName:
    name: niem50_EntityName
    annotations:
      string:
        tag: string
        value: 2586246
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: SCALES-Party-Hash-01169B980BF3557176ECC743C5841A32
        example_object_type: string
        example_predicate: niem50:EntityName
        example_subject: scales:Agent/akd;;1:16-cr-00001_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: USA
        example_object_type: string
        example_predicate: niem50:EntityName
        example_subject: scales:Agent/akd;;1:16-cr-00001_a1
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - object:
        example_object: State of Alaska
        example_object_type: string
        example_predicate: niem50:EntityName
        example_subject: scales:Agent/akd;;1:16-cv-00008_a7
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:EntityName
    alias: niem50_EntityName
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - scales_Party
    range: string
  scales_hasHighestOffenseLevelTerminated:
    name: scales_hasHighestOffenseLevelTerminated
    annotations:
      string:
        tag: string
        value: 69523
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Misdemeanor
        example_object_type: string
        example_predicate: scales:hasHighestOffenseLevelTerminated
        example_subject: scales:Agent/akd;;1:16-cr-00006_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasHighestOffenseLevelTerminated
    alias: scales_hasHighestOffenseLevelTerminated
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    range: string
  scales_hasHighestOffenseLevelOpening:
    name: scales_hasHighestOffenseLevelOpening
    annotations:
      string:
        tag: string
        value: 159337
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Misdemeanor
        example_object_type: string
        example_predicate: scales:hasHighestOffenseLevelOpening
        example_subject: scales:Agent/akd;;1:16-cr-00001_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasHighestOffenseLevelOpening
    alias: scales_hasHighestOffenseLevelOpening
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    range: string
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
        value: 2823772
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:Agent/akd;;1:16-cr-00001_a3
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefenseAttorney
        example_subject: scales:Agent/akd;;1:16-cr-00001_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefenseAttorney
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
  http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 389366
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:Charge/akd;;1:16-cr-00001_c0-1-3
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
        example_subject: scales:Agent/akd;;1:16-cr-00001_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: scales:Charge/ga-clayton-magistrate;;0:00-bc-00001_c0
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
        example_subject: scales:Agent/ga-clayton-magistrate;;0:00-bc-00001_a0
        example_subject_type: scales_Party
    - object:
        example_object: scales:Charge/fulton-01-10000019
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
        example_subject: scales:Agent/10000019_0
        example_subject_type: scales_Agent
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - scales_Agent
    - scales_Party
    range: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
  http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    annotations:
      string:
        tag: string
        value: 2586246
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Defendant
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
        example_subject: scales:Agent/akd;;1:16-cr-00001_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: Plaintiff
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
        example_subject: scales:Agent/akd;;1:16-cr-00001_a1
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - object:
        example_object: Amicus
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
        example_subject: scales:Agent/akd;;1:16-cv-00008_a7
        example_subject_type: scales_Party
    - object:
        example_object: defendant
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
        example_subject: scales:Agent/10000019_0
        example_subject_type: scales_Agent
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - scales_Agent
    - scales_Party
    range: string
  scales_hasExtraInfo:
    name: scales_hasExtraInfo
    annotations:
      string:
        tag: string
        value: 671599
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 'doing business as

          Northstar Gift Shop'
        example_object_type: string
        example_predicate: scales:hasExtraInfo
        example_subject: scales:Agent/akd;;1:16-cr-00004_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: 'Soc. Sec. #XXX-XX-0767'
        example_object_type: string
        example_predicate: scales:hasExtraInfo
        example_subject: scales:Agent/akd;;1:16-cv-00003_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - object:
        example_object: husband and wife
        example_object_type: string
        example_predicate: scales:hasExtraInfo
        example_subject: scales:Agent/akd;;3:16-cv-00062_a4
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasExtraInfo
    alias: scales_hasExtraInfo
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - scales_Party
    range: string
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty

```
</details>