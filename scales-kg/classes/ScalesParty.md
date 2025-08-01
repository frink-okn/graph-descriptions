

# Class: No class (type) name specified (scales_Party)


_No class (type) description specified_






This class occurs 7362525 times.


URI: [scales:Party](http://schemas.scales-okn.org/rdf/scales#Party)






```mermaid
 classDiagram
    class ScalesParty
    click ScalesParty href "../ScalesParty"
      ScalesParty : http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
        
          
    
    
    ScalesParty --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2Attorney : http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
    click HttpRelease.niem.govNiemDomainsJxdm7.2Attorney href "../HttpRelease.niem.govNiemDomainsJxdm7.2Attorney"

        
      ScalesParty : http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
        
          
    
    
    ScalesParty --> "0..1" String : http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    click String href "../String"

        
      ScalesParty : http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
        
          
    
    
    ScalesParty --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2Charge : http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
    click HttpRelease.niem.govNiemDomainsJxdm7.2Charge href "../HttpRelease.niem.govNiemDomainsJxdm7.2Charge"

        
      ScalesParty : http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
        
          
    
    
    ScalesParty --> "0..1" HttpRelease.niem.govNiemDomainsJxdm7.2Sentence : http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
    click HttpRelease.niem.govNiemDomainsJxdm7.2Sentence href "../HttpRelease.niem.govNiemDomainsJxdm7.2Sentence"

        
      ScalesParty : niem50_EntityName
        
          
    
    
    ScalesParty --> "0..1" String : niem50_EntityName
    click String href "../String"

        
      ScalesParty : niem50_PersonFullName
        
          
    
    
    ScalesParty --> "0..1" String : niem50_PersonFullName
    click String href "../String"

        
      ScalesParty : scales_hasExtraInfo
        
          
    
    
    ScalesParty --> "0..1" String : scales_hasExtraInfo
    click String href "../String"

        
      ScalesParty : scales_isInstanceOfEntity
        
          
    
    
    ScalesParty --> "0..1" Uri : scales_isInstanceOfEntity
    click Uri href "../Uri"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No slot (predicate) description specified <br/>  | direct | 2155917 |
| [scales_isInstanceOfEntity](../slots/scales_isInstanceOfEntity.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | No slot (predicate) description specified <br/>  | direct | 7057563 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_Sentence](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_Sentence.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2Sentence](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Sentence.md) | No slot (predicate) description specified <br/>  | direct | 319576 |
| [niem50_EntityName](../slots/niem50_EntityName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 317772 |
| [niem50_PersonFullName](../slots/niem50_PersonFullName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 7044753 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 7341708 |
| [scales_hasExtraInfo](../slots/scales_hasExtraInfo.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 43157 |
| [http___release.niem.gov_niem_domains_jxdm_7.2_Attorney](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_Attorney.md) | 0..1 <br/> [HttpRelease.niem.govNiemDomainsJxdm7.2Attorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Attorney.md) | No slot (predicate) description specified <br/>  | direct | 537560 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: scales_Party
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 7362525
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slots:
- http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
- scales_isInstanceOfEntity
- http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
- niem50_EntityName
- niem50_PersonFullName
- http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
- scales_hasExtraInfo
- http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_Attorney:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Attorney:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
        value: 537560
  http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    annotations:
      string:
        tag: string
        value: 7341708
  http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 2155917
  http___release.niem.gov_niem_domains_jxdm_7.2_Sentence:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Sentence:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
        value: 319576
  niem50_EntityName:
    name: niem50_EntityName
    annotations:
      string:
        tag: string
        value: 317772
  niem50_PersonFullName:
    name: niem50_PersonFullName
    annotations:
      string:
        tag: string
        value: 7044753
  scales_hasExtraInfo:
    name: scales_hasExtraInfo
    annotations:
      string:
        tag: string
        value: 43157
  scales_isInstanceOfEntity:
    name: scales_isInstanceOfEntity
    annotations:
      uri:
        tag: uri
        value: 7057563
class_uri: scales:Party

```
</details>

### Induced

<details>

```yaml
name: scales_Party
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 7362525
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_Attorney:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Attorney:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
        value: 537560
  http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    annotations:
      string:
        tag: string
        value: 7341708
  http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 2155917
  http___release.niem.gov_niem_domains_jxdm_7.2_Sentence:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Sentence:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
        value: 319576
  niem50_EntityName:
    name: niem50_EntityName
    annotations:
      string:
        tag: string
        value: 317772
  niem50_PersonFullName:
    name: niem50_PersonFullName
    annotations:
      string:
        tag: string
        value: 7044753
  scales_hasExtraInfo:
    name: scales_hasExtraInfo
    annotations:
      string:
        tag: string
        value: 43157
  scales_isInstanceOfEntity:
    name: scales_isInstanceOfEntity
    annotations:
      uri:
        tag: uri
        value: 7057563
attributes:
  http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Charge:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        value: 2155917
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Charge/akd;;1:16-cr-00001_c0-1-3
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
        example_subject: scales:/Agent/akd;;1:16-cr-00001_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: scales:Charge/ga-clayton-magistrate;;0:00-bc-00001_c0
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
        example_subject: scales:Agent/ga-clayton-magistrate;;0:00-bc-00001_a0
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
    owner: scales_Party
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - scales_Party
    range: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
  scales_isInstanceOfEntity:
    name: scales_isInstanceOfEntity
    annotations:
      uri:
        tag: uri
        value: 7057563
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:PartyEntity/SPID-GA-CLAYTON-WEAK-729449
        example_object_type: uri
        example_predicate: scales:isInstanceOfEntity
        example_subject: scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a0
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:isInstanceOfEntity
    alias: scales_isInstanceOfEntity
    owner: scales_Party
    domain_of:
    - scales_Party
    range: uri
  http___release.niem.gov_niem_domains_jxdm_7.2_Sentence:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Sentence:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
        value: 319576
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:Sentence/ga-clayton-state;;0:00-cr-01074_de32_s0
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/Sentence
        example_subject: scales:Agent/ga-clayton-state;;0:00-cr-01074_a1
        example_subject_type: scales_Party
    - object:
        example_object: scales:Sentence/ga-clayton-state;;0:00-cr-00001_de10_s0
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/Sentence
        example_subject: scales:DocketEntry/ga-clayton-state;;0:00-cr-00001_de10
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/Sentence
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
    owner: scales_Party
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    - scales_Party
    range: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
  niem50_EntityName:
    name: niem50_EntityName
    annotations:
      string:
        tag: string
        value: 317772
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: SCALES-Party-Hash-01169B980BF3557176ECC743C5841A32
        example_object_type: string
        example_predicate: niem50:EntityName
        example_subject: scales:/Agent/akd;;1:16-cr-00001_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: USA
        example_object_type: string
        example_predicate: niem50:EntityName
        example_subject: scales:/Agent/akd;;1:16-cr-00001_a1
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - object:
        example_object: State of Alaska
        example_object_type: string
        example_predicate: niem50:EntityName
        example_subject: scales:/Agent/akd;;1:16-cv-00008_a7
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:EntityName
    alias: niem50_EntityName
    owner: scales_Party
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - scales_Party
    range: string
  niem50_PersonFullName:
    name: niem50_PersonFullName
    annotations:
      string:
        tag: string
        value: 7044753
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Timothy M. Burgess
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:/Agent/akd;;1:16-cr-00001_a2
        example_subject_type: None
    - object:
        example_object: Matthew McCrary Scoble
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:/Agent/akd;;1:16-cr-00001_a3
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
    - object:
        example_object: Jack S. Schmidt
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:/Agent/akd;;1:16-cr-00001_a5
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
    - object:
        example_object: Mary Ann Lundquist
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:/Agent/akd;;1:16-cv-00008_a22
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
    - object:
        example_object: Stephen H Locher
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:/JudgeEntity/SJ000001
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    - object:
        example_object: BRAZELTON TROY DBA
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a0
        example_subject_type: scales_Party
    - object:
        example_object: SCALES-Party-Hash-2DB6296D52E366F752379C777C9BE051
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:Agent/ga-fulton-01/10000019
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: BAIRD
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:Judge/ga-clayton-magistrate-civil;;0:00-cm-00001_3
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:PersonFullName
    alias: niem50_PersonFullName
    owner: scales_Party
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
    - http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    - scales_Party
    range: string
  http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    annotations:
      string:
        tag: string
        value: 7341708
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Defendant
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
        example_subject: scales:/Agent/akd;;1:16-cr-00001_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: Plaintiff
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
        example_subject: scales:/Agent/akd;;1:16-cr-00001_a1
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - object:
        example_object: Amicus
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
        example_subject: scales:/Agent/akd;;1:16-cv-00008_a7
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
    owner: scales_Party
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
        value: 43157
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: 'doing business as

          Northstar Gift Shop'
        example_object_type: string
        example_predicate: scales:hasExtraInfo
        example_subject: scales:/Agent/akd;;1:16-cr-00004_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - object:
        example_object: 'Soc. Sec. #XXX-XX-0767'
        example_object_type: string
        example_predicate: scales:hasExtraInfo
        example_subject: scales:/Agent/akd;;1:16-cv-00003_a0
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - object:
        example_object: husband and wife
        example_object_type: string
        example_predicate: scales:hasExtraInfo
        example_subject: scales:/Agent/akd;;3:16-cv-00062_a4
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasExtraInfo
    alias: scales_hasExtraInfo
    owner: scales_Party
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    - scales_Party
    range: string
  http___release.niem.gov_niem_domains_jxdm_7.2_Attorney:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
    annotations:
      http___release.niem.gov_niem_domains_jxdm_7.2_Attorney:
        tag: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
        value: 537560
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: scales:/Agent/akd;;1:16-cv-00008_a22
        example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/Attorney
        example_subject: scales:/Agent/akd;;1:16-cv-00008_a7
        example_subject_type: scales_Party
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/Attorney
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
    owner: scales_Party
    domain_of:
    - scales_Party
    range: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
class_uri: scales:Party

```
</details>