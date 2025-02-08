

# Class: No class (type) name specified (jxdm72_Judge)


_No class (type) description specified_





URI: [jxdm72:Judge](http://release.niem.gov/niem/domains/jxdm/7.2/#Judge)






```mermaid
 classDiagram
    class Jxdm72Judge
    click Jxdm72Judge href "../Jxdm72Judge"
      Jxdm72Judge : jxdm72_JudicialOfficialCategoryText
        
          
    
    
    Jxdm72Judge --> "0..1" String : jxdm72_JudicialOfficialCategoryText
    click String href "../String"

        
      Jxdm72Judge : niem50_PersonFullName
        
          
    
    
    Jxdm72Judge --> "0..1" String : niem50_PersonFullName
    click String href "../String"

        
      Jxdm72Judge : niem50_PersonRaceText
        
          
    
    
    Jxdm72Judge --> "0..1" String : niem50_PersonRaceText
    click String href "../String"

        
      Jxdm72Judge : niem50_PersonSexText
        
          
    
    
    Jxdm72Judge --> "0..1" String : niem50_PersonSexText
    click String href "../String"

        
      Jxdm72Judge : scales_appointedByParty
        
          
    
    
    Jxdm72Judge --> "0..1" String : scales_appointedByParty
    click String href "../String"

        
      Jxdm72Judge : scales_hasCommissionDate
        
          
    
    
    Jxdm72Judge --> "0..1" Date : scales_hasCommissionDate
    click Date href "../Date"

        
      Jxdm72Judge : scales_hasFJCNodeID
        
          
    
    
    Jxdm72Judge --> "0..1" Double : scales_hasFJCNodeID
    click Double href "../Double"

        
      Jxdm72Judge : scales_hasUVAJudgeDirID
        
          
    
    
    Jxdm72Judge --> "0..1" String : scales_hasUVAJudgeDirID
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [jxdm72_JudicialOfficialCategoryText](../slots/jxdm72_JudicialOfficialCategoryText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/> 5385 occurrences with subject type jxdm72_Judge and object type string.<br/>5385 occurrences with untyped subjects and object type string. | direct |
| [scales_hasCommissionDate](../slots/scales_hasCommissionDate.md) | 0..1 <br/> [xsd:date](http://www.w3.org/2001/XMLSchema#date) | No slot (predicate) description specified <br/> 4257 occurrences with subject type jxdm72_Judge and object type date. | direct |
| [niem50_PersonRaceText](../slots/niem50_PersonRaceText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/> 3762 occurrences with subject type jxdm72_Judge and object type string. | direct |
| [scales_hasUVAJudgeDirID](../slots/scales_hasUVAJudgeDirID.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/> 988 occurrences with subject type jxdm72_Judge and object type string. | direct |
| [niem50_PersonFullName](../slots/niem50_PersonFullName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/> 4973752 occurrences with untyped subjects and object type string.<br/>5385 occurrences with subject type jxdm72_Judge and object type string. | direct |
| [niem50_PersonSexText](../slots/niem50_PersonSexText.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/> 3762 occurrences with subject type jxdm72_Judge and object type string. | direct |
| [scales_hasFJCNodeID](../slots/scales_hasFJCNodeID.md) | 0..1 <br/> [xsd:double](http://www.w3.org/2001/XMLSchema#double) | No slot (predicate) description specified <br/> 3855 occurrences with subject type jxdm72_Judge and object type double. | direct |
| [scales_appointedByParty](../slots/scales_appointedByParty.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/> 3912 occurrences with subject type jxdm72_Judge and object type string. | direct |









## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | jxdm72:Judge |
| native | scales-kg-new/:Jxdm72Judge |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: jxdm72_Judge
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 5385 occurrences.
from_schema: scales-kg-new
rank: 1000
slots:
- jxdm72_JudicialOfficialCategoryText
- scales_hasCommissionDate
- niem50_PersonRaceText
- scales_hasUVAJudgeDirID
- niem50_PersonFullName
- niem50_PersonSexText
- scales_hasFJCNodeID
- scales_appointedByParty
class_uri: jxdm72:Judge

```
</details>

### Induced

<details>

```yaml
name: jxdm72_Judge
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 5385 occurrences.
from_schema: scales-kg-new
rank: 1000
attributes:
  jxdm72_JudicialOfficialCategoryText:
    name: jxdm72_JudicialOfficialCategoryText
    description: No slot (predicate) description specified
    comments:
    - 5385 occurrences with subject type jxdm72_Judge and object type string.
    - 5385 occurrences with untyped subjects and object type string.
    examples:
    - description: jxdm72_Judge → string
      object:
        example_object: Magistrate_Judge
        example_object_type: string
        example_predicate: jxdm72:JudicialOfficialCategoryText
        example_subject: scales/JudgeEntity/SJ000000
        example_subject_type: jxdm72_Judge
    - description: None → string
      object:
        example_object: Magistrate_Judge
        example_object_type: string
        example_predicate: jxdm72:JudicialOfficialCategoryText
        example_subject: http://schemas.scales-okn.org/rdf/ijp#JudgeEntity/SJ000000
        example_subject_type: None
    from_schema: scales-kg-new
    rank: 1000
    slot_uri: jxdm72:JudicialOfficialCategoryText
    alias: jxdm72_JudicialOfficialCategoryText
    owner: jxdm72_Judge
    domain_of:
    - jxdm72_Judge
    range: string
  scales_hasCommissionDate:
    name: scales_hasCommissionDate
    description: No slot (predicate) description specified
    comments:
    - 4257 occurrences with subject type jxdm72_Judge and object type date.
    examples:
    - description: jxdm72_Judge → date
      object:
        example_object: '1987-01-01'
        example_object_type: date
        example_predicate: scales:hasCommissionDate
        example_subject: scales/JudgeEntity/SJ000004
        example_subject_type: jxdm72_Judge
    from_schema: scales-kg-new
    rank: 1000
    slot_uri: scales:hasCommissionDate
    alias: scales_hasCommissionDate
    owner: jxdm72_Judge
    domain_of:
    - jxdm72_Judge
    range: date
  niem50_PersonRaceText:
    name: niem50_PersonRaceText
    description: No slot (predicate) description specified
    comments:
    - 3762 occurrences with subject type jxdm72_Judge and object type string.
    examples:
    - description: jxdm72_Judge → string
      object:
        example_object: White
        example_object_type: string
        example_predicate: niem50:PersonRaceText
        example_subject: scales/JudgeEntity/SJ000004
        example_subject_type: jxdm72_Judge
    from_schema: scales-kg-new
    rank: 1000
    slot_uri: niem50:PersonRaceText
    alias: niem50_PersonRaceText
    owner: jxdm72_Judge
    domain_of:
    - jxdm72_Judge
    range: string
  scales_hasUVAJudgeDirID:
    name: scales_hasUVAJudgeDirID
    description: No slot (predicate) description specified
    comments:
    - 988 occurrences with subject type jxdm72_Judge and object type string.
    examples:
    - description: jxdm72_Judge → string
      object:
        example_object: mag-424
        example_object_type: string
        example_predicate: scales:hasUVAJudgeDirID
        example_subject: scales/JudgeEntity/SJ000018
        example_subject_type: jxdm72_Judge
    from_schema: scales-kg-new
    rank: 1000
    slot_uri: scales:hasUVAJudgeDirID
    alias: scales_hasUVAJudgeDirID
    owner: jxdm72_Judge
    domain_of:
    - jxdm72_Judge
    range: string
  niem50_PersonFullName:
    name: niem50_PersonFullName
    description: No slot (predicate) description specified
    comments:
    - 4973752 occurrences with untyped subjects and object type string.
    - 5385 occurrences with subject type jxdm72_Judge and object type string.
    examples:
    - description: None → string
      object:
        example_object: Honorable Judge Myron H. Thompson
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales/Agent/almd;;1:16-cr-00020_a2
        example_subject_type: None
    - description: jxdm72_Judge → string
      object:
        example_object: Cj Williams
        example_object_type: string
        example_predicate: niem50:PersonFullName
        example_subject: scales/JudgeEntity/SJ000000
        example_subject_type: jxdm72_Judge
    from_schema: scales-kg-new
    rank: 1000
    slot_uri: niem50:PersonFullName
    alias: niem50_PersonFullName
    owner: jxdm72_Judge
    domain_of:
    - jxdm72_Judge
    range: string
  niem50_PersonSexText:
    name: niem50_PersonSexText
    description: No slot (predicate) description specified
    comments:
    - 3762 occurrences with subject type jxdm72_Judge and object type string.
    examples:
    - description: jxdm72_Judge → string
      object:
        example_object: Male
        example_object_type: string
        example_predicate: niem50:PersonSexText
        example_subject: scales/JudgeEntity/SJ000004
        example_subject_type: jxdm72_Judge
    from_schema: scales-kg-new
    rank: 1000
    slot_uri: niem50:PersonSexText
    alias: niem50_PersonSexText
    owner: jxdm72_Judge
    domain_of:
    - jxdm72_Judge
    range: string
  scales_hasFJCNodeID:
    name: scales_hasFJCNodeID
    description: No slot (predicate) description specified
    comments:
    - 3855 occurrences with subject type jxdm72_Judge and object type double.
    examples:
    - description: jxdm72_Judge → double
      object:
        example_object: '1390011.0'
        example_object_type: double
        example_predicate: scales:hasFJCNodeID
        example_subject: scales/JudgeEntity/SJ000004
        example_subject_type: jxdm72_Judge
    from_schema: scales-kg-new
    rank: 1000
    slot_uri: scales:hasFJCNodeID
    alias: scales_hasFJCNodeID
    owner: jxdm72_Judge
    domain_of:
    - jxdm72_Judge
    range: double
  scales_appointedByParty:
    name: scales_appointedByParty
    description: No slot (predicate) description specified
    comments:
    - 3912 occurrences with subject type jxdm72_Judge and object type string.
    examples:
    - description: jxdm72_Judge → string
      object:
        example_object: Republican
        example_object_type: string
        example_predicate: scales:appointedByParty
        example_subject: scales/JudgeEntity/SJ000004
        example_subject_type: jxdm72_Judge
    from_schema: scales-kg-new
    rank: 1000
    slot_uri: scales:appointedByParty
    alias: scales_appointedByParty
    owner: jxdm72_Judge
    domain_of:
    - jxdm72_Judge
    range: string
class_uri: jxdm72:Judge

```
</details>