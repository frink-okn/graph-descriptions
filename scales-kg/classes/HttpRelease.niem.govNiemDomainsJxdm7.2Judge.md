

# Class: No class (type) name specified (http___release.niem.gov_niem_domains_jxdm_7.2_Judge)


_No class (type) description specified_






This class occurs 5385 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/Judge](http://release.niem.gov/niem/domains/jxdm/7.2/Judge)






```mermaid
 classDiagram
    class HttpRelease.niem.govNiemDomainsJxdm7.2Judge
    click HttpRelease.niem.govNiemDomainsJxdm7.2Judge href "../HttpRelease.niem.govNiemDomainsJxdm7.2Judge"
      HttpRelease.niem.govNiemDomainsJxdm7.2Judge : http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Judge --> "0..1" String : http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Judge : niem50_PersonFullName
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Judge --> "0..1" String : niem50_PersonFullName
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Judge : niem50_PersonRaceText
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Judge --> "0..1" String : niem50_PersonRaceText
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Judge : niem50_PersonSexText
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Judge --> "0..1" String : niem50_PersonSexText
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Judge : scales_appointedByParty
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Judge --> "0..1" String : scales_appointedByParty
    click String href "../String"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Judge : scales_hasCommissionDate
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Judge --> "0..1" Date : scales_hasCommissionDate
    click Date href "../Date"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Judge : scales_hasFJCNodeID
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Judge --> "0..1" Double : scales_hasFJCNodeID
    click Double href "../Double"

        
      HttpRelease.niem.govNiemDomainsJxdm7.2Judge : scales_hasUVAJudgeDirID
        
          
    
    
    HttpRelease.niem.govNiemDomainsJxdm7.2Judge --> "0..1" String : scales_hasUVAJudgeDirID
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 5385 |
| [niem50_PersonRaceText](../slots/niem50_PersonRaceText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 3762 |
| [niem50_PersonSexText](../slots/niem50_PersonSexText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 3762 |
| [scales_hasUVAJudgeDirID](../slots/scales_hasUVAJudgeDirID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 988 |
| [niem50_PersonFullName](../slots/niem50_PersonFullName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 5385 |
| [scales_appointedByParty](../slots/scales_appointedByParty.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 3912 |
| [scales_hasFJCNodeID](../slots/scales_hasFJCNodeID.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/>  | direct | 3855 |
| [scales_hasCommissionDate](../slots/scales_hasCommissionDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) | No slot (predicate) description specified <br/>  | direct | 4253 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | [scales_isInstanceOfEntity](../slots/scales_isInstanceOfEntity.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md) |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | [scales_isInstanceOfEntity](../slots/scales_isInstanceOfEntity.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md) |
| [ScalesParty](../classes/ScalesParty.md) | [scales_isInstanceOfEntity](../slots/scales_isInstanceOfEntity.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 5385
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slots:
- http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText
- niem50_PersonRaceText
- niem50_PersonSexText
- scales_hasUVAJudgeDirID
- niem50_PersonFullName
- scales_appointedByParty
- scales_hasFJCNodeID
- scales_hasCommissionDate
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText
    annotations:
      string:
        tag: string
        value: 5385
  niem50_PersonFullName:
    name: niem50_PersonFullName
    annotations:
      string:
        tag: string
        value: 5385
  niem50_PersonRaceText:
    name: niem50_PersonRaceText
    annotations:
      string:
        tag: string
        value: 3762
  niem50_PersonSexText:
    name: niem50_PersonSexText
    annotations:
      string:
        tag: string
        value: 3762
  scales_appointedByParty:
    name: scales_appointedByParty
    annotations:
      string:
        tag: string
        value: 3912
  scales_hasCommissionDate:
    name: scales_hasCommissionDate
    annotations:
      date:
        tag: date
        value: 4253
  scales_hasFJCNodeID:
    name: scales_hasFJCNodeID
    annotations:
      double:
        tag: double
        value: 3855
  scales_hasUVAJudgeDirID:
    name: scales_hasUVAJudgeDirID
    annotations:
      string:
        tag: string
        value: 988
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/Judge

```
</details>

### Induced

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 5385
description: No class (type) description specified
title: No class (type) name specified
from_schema: scales-kg
rank: 1000
slot_usage:
  http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText
    annotations:
      string:
        tag: string
        value: 5385
  niem50_PersonFullName:
    name: niem50_PersonFullName
    annotations:
      string:
        tag: string
        value: 5385
  niem50_PersonRaceText:
    name: niem50_PersonRaceText
    annotations:
      string:
        tag: string
        value: 3762
  niem50_PersonSexText:
    name: niem50_PersonSexText
    annotations:
      string:
        tag: string
        value: 3762
  scales_appointedByParty:
    name: scales_appointedByParty
    annotations:
      string:
        tag: string
        value: 3912
  scales_hasCommissionDate:
    name: scales_hasCommissionDate
    annotations:
      date:
        tag: date
        value: 4253
  scales_hasFJCNodeID:
    name: scales_hasFJCNodeID
    annotations:
      double:
        tag: double
        value: 3855
  scales_hasUVAJudgeDirID:
    name: scales_hasUVAJudgeDirID
    annotations:
      string:
        tag: string
        value: 988
attributes:
  http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText:
    name: http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText
    annotations:
      string:
        tag: string
        value: 5385
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: FJC Judge
        example_object_type: string
        example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/JudicialOfficialCategoryText
        example_subject: scales:/JudgeEntity/SJ000002
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    from_schema: scales-kg
    rank: 1000
    slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/JudicialOfficialCategoryText
    alias: http___release.niem.gov_niem_domains_jxdm_7.2_JudicialOfficialCategoryText
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    range: string
  niem50_PersonRaceText:
    name: niem50_PersonRaceText
    annotations:
      string:
        tag: string
        value: 3762
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: White
        example_object_type: string
        example_predicate: niem50:PersonRaceText
        example_subject: scales:/JudgeEntity/SJ000002
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:PersonRaceText
    alias: niem50_PersonRaceText
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    range: string
  niem50_PersonSexText:
    name: niem50_PersonSexText
    annotations:
      string:
        tag: string
        value: 3762
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Male
        example_object_type: string
        example_predicate: niem50:PersonSexText
        example_subject: scales:/JudgeEntity/SJ000002
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:PersonSexText
    alias: niem50_PersonSexText
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    range: string
  scales_hasUVAJudgeDirID:
    name: scales_hasUVAJudgeDirID
    annotations:
      string:
        tag: string
        value: 988
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: mag-261
        example_object_type: string
        example_predicate: scales:hasUVAJudgeDirID
        example_subject: scales:/JudgeEntity/SJ000079
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasUVAJudgeDirID
    alias: scales_hasUVAJudgeDirID
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    range: string
  niem50_PersonFullName:
    name: niem50_PersonFullName
    annotations:
      string:
        tag: string
        value: 5385
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Judge Gonzalo P. Curiel
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:/Agent/casd;;3:16-cv-01644_a2
        example_subject_type: None
    - object:
        example_object: SCALES-Party-Hash-A832763C1FE77A32B6DE912B9C77F80C
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:/Agent/casd;;3:16-cv-01644_a3
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
    - object:
        example_object: Ryan A. Sausedo
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:/Agent/casd;;3:16-cv-01644_a5
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
    - object:
        example_object: Benjamin Gilford
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:/Agent/casd;;3:16-cv-01645_a20
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
    - object:
        example_object: Carroll O Switzer
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales:/JudgeEntity/SJ000002
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    from_schema: scales-kg
    rank: 1000
    slot_uri: niem50:PersonFullName
    alias: niem50_PersonFullName
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
    - http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
    - http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    range: string
  scales_appointedByParty:
    name: scales_appointedByParty
    annotations:
      string:
        tag: string
        value: 3912
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: Democratic
        example_object_type: string
        example_predicate: scales:appointedByParty
        example_subject: scales:/JudgeEntity/SJ000002
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:appointedByParty
    alias: scales_appointedByParty
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    range: string
  scales_hasFJCNodeID:
    name: scales_hasFJCNodeID
    annotations:
      double:
        tag: double
        value: 3855
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1388511.0'
        example_object_type: double
        example_predicate: scales:hasFJCNodeID
        example_subject: scales:/JudgeEntity/SJ000002
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasFJCNodeID
    alias: scales_hasFJCNodeID
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    range: double
  scales_hasCommissionDate:
    name: scales_hasCommissionDate
    annotations:
      date:
        tag: date
        value: 4253
    description: No slot (predicate) description specified
    examples:
    - object:
        example_object: '1980-01-01'
        example_object_type: date
        example_predicate: scales:hasCommissionDate
        example_subject: scales:/JudgeEntity/SJ000184
        example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    from_schema: scales-kg
    rank: 1000
    slot_uri: scales:hasCommissionDate
    alias: scales_hasCommissionDate
    owner: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    domain_of:
    - http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    range: date
class_uri: http://release.niem.gov/niem/domains/jxdm/7.2/Judge

```
</details>