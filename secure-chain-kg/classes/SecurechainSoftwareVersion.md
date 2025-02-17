

# Class: No class (type) name specified (securechain_SoftwareVersion)


_No class (type) description specified_






This class occurs 164001 times.


URI: [securechain:SoftwareVersion](https://w3id.org/secure-chain/SoftwareVersion)






```mermaid
 classDiagram
    class SecurechainSoftwareVersion
    click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"
      SecurechainSoftware <|-- SecurechainSoftwareVersion
        click SecurechainSoftware href "../SecurechainSoftware"
      
      SecurechainSoftwareVersion : hsdo_contributor
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" HsdoPerson : hsdo_contributor
    click HsdoPerson href "../HsdoPerson"

        
      SecurechainSoftwareVersion : hsdo_name
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" String : hsdo_name
    click String href "../String"

        
      SecurechainSoftwareVersion : securechain_dependsOn
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" Any : securechain_dependsOn
    click Any href "../Any"

        
      SecurechainSoftwareVersion : securechain_hasSoftwareVersion
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SecurechainSoftwareVersion : securechain_hasSoftwareVersion
    click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"

        
      SecurechainSoftwareVersion : securechain_versionName
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" String : securechain_versionName
    click String href "../String"

        
      SecurechainSoftwareVersion : securechain_vulnerableTo
        
          
    
    
    SecurechainSoftwareVersion --> "0..1" SecurechainVulnerability : securechain_vulnerableTo
    click SecurechainVulnerability href "../SecurechainVulnerability"

        
      
```





## Inheritance
* [HsdoSoftwareApplication](../classes/HsdoSoftwareApplication.md)
    * [SecurechainSoftware](../classes/SecurechainSoftware.md)
        * **SecurechainSoftwareVersion**



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [securechain_dependsOn](../slots/securechain_dependsOn.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No slot (predicate) description specified <br/>  | direct | 696918 |
| [securechain_versionName](../slots/securechain_versionName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 164000 |
| [securechain_vulnerableTo](../slots/securechain_vulnerableTo.md) | 0..1 <br/> [SecurechainVulnerability](../classes/SecurechainVulnerability.md) | No slot (predicate) description specified <br/>  | direct | 5067 |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | The name of the item | [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |
| [hsdo_contributor](../slots/hsdo_contributor.md) | 0..1 <br/> [HsdoPerson](../classes/HsdoPerson.md) | A secondary contributor to the CreativeWork or Event | [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |
| [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | 0..1 <br/> [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No slot (predicate) description specified | [SecurechainSoftware](../classes/SecurechainSoftware.md) |  |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_dependsOn](../slots/securechain_dependsOn.md) | any_of[range] | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: securechain_SoftwareVersion
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 164001
description: No class (type) description specified
title: No class (type) name specified
from_schema: secure-chain-kg
rank: 1000
is_a: securechain_Software
slots:
- securechain_dependsOn
- securechain_versionName
- securechain_vulnerableTo
slot_usage:
  securechain_dependsOn:
    name: securechain_dependsOn
    annotations:
      securechain_SoftwareVersion:
        tag: securechain_SoftwareVersion
        value: 696916
      uri:
        tag: uri
        value: 2
  securechain_versionName:
    name: securechain_versionName
    annotations:
      string:
        tag: string
        value: 164000
  securechain_vulnerableTo:
    name: securechain_vulnerableTo
    annotations:
      securechain_Vulnerability:
        tag: securechain_Vulnerability
        value: 5067
class_uri: securechain:SoftwareVersion

```
</details>

### Induced

<details>

```yaml
name: securechain_SoftwareVersion
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 164001
description: No class (type) description specified
title: No class (type) name specified
from_schema: secure-chain-kg
rank: 1000
is_a: securechain_Software
slot_usage:
  securechain_dependsOn:
    name: securechain_dependsOn
    annotations:
      securechain_SoftwareVersion:
        tag: securechain_SoftwareVersion
        value: 696916
      uri:
        tag: uri
        value: 2
  securechain_versionName:
    name: securechain_versionName
    annotations:
      string:
        tag: string
        value: 164000
  securechain_vulnerableTo:
    name: securechain_vulnerableTo
    annotations:
      securechain_Vulnerability:
        tag: securechain_Vulnerability
        value: 5067
attributes:
  securechain_dependsOn:
    name: securechain_dependsOn
    annotations:
      securechain_SoftwareVersion:
        tag: securechain_SoftwareVersion
        value: 696916
      uri:
        tag: uri
        value: 2
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: securechain:SoftwareVersion/0ad-data#%3E%3D+0.0.17%26%3C%3D+0.0.17-1
        example_object_type: securechain_SoftwareVersion
        example_predicate: securechain:dependsOn
        example_subject: securechain:SoftwareVersion/0ad#0.0.17-1
        example_subject_type: securechain_SoftwareVersion
    - object:
        example_object: securechain:SoftwareVersion/libc6#%3E%3E+2.39%26%3C%3C+2.40
        example_object_type: securechain_SoftwareVersion
        example_predicate: securechain:dependsOn
        example_subject: securechain:SoftwareVersion/zzuf#0.15-4%2Bb3
        example_subject_type: None
    - object:
        example_object: securechain:SoftwareVersion/dosbox#0.74-2
        example_object_type: uri
        example_predicate: securechain:dependsOn
        example_subject: securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2
        example_subject_type: securechain_SoftwareVersion
    - object:
        example_object: securechain:SoftwareVersion/fast_float#v3.4.0
        example_object_type: uri
        example_predicate: securechain:dependsOn
        example_subject: securechain:SoftwareVersion/glaze#v0.0.1
        example_subject_type: None
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:dependsOn
    alias: securechain_dependsOn
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_SoftwareVersion
    range: Any
    any_of:
    - range: uri
    - range: securechain_SoftwareVersion
  securechain_versionName:
    name: securechain_versionName
    annotations:
      string:
        tag: string
        value: 164000
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: '-'
        example_object_type: string
        example_predicate: securechain:versionName
        example_subject: securechain:HardwareVersion/-#-
        example_subject_type: securechain_HardwareVersion
    - object:
        example_object: '"//api#*'
        example_object_type: string
        example_predicate: securechain:versionName
        example_subject: securechain:SoftwareVersion/#%22%2F%2Fapi%23%2A
        example_subject_type: securechain_SoftwareVersion
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:versionName
    alias: securechain_versionName
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_HardwareVersion
    - securechain_SoftwareVersion
    range: string
  securechain_vulnerableTo:
    name: securechain_vulnerableTo
    annotations:
      securechain_Vulnerability:
        tag: securechain_Vulnerability
        value: 5067
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: securechain:Vulnerability/CVE-2019-0162
        example_object_type: securechain_Vulnerability
        example_predicate: securechain:vulnerableTo
        example_subject: securechain:HardwareVersion/-#-
        example_subject_type: securechain_HardwareVersion
    - object:
        example_object: securechain:Vulnerability/CVE-2017-17529
        example_object_type: securechain_Vulnerability
        example_predicate: securechain:vulnerableTo
        example_subject: securechain:SoftwareVersion/abiword#3.0.2-2%2Bdeb9u2
        example_subject_type: securechain_SoftwareVersion
    - object:
        example_object: securechain:Vulnerability/CVE-2007-4319
        example_object_type: securechain_Vulnerability
        example_predicate: securechain:vulnerableTo
        example_subject: securechain:HardwareVersion/zywall_2#%2A
        example_subject_type: None
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:vulnerableTo
    alias: securechain_vulnerableTo
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_HardwareVersion
    - securechain_SoftwareVersion
    range: securechain_Vulnerability
  hsdo_name:
    name: hsdo_name
    annotations:
      string:
        tag: string
        value: 34466
    description: The name of the item.
    title: name
    examples:
    - object:
        example_object: '-'
        example_object_type: string
        example_predicate: hsdo:name
        example_subject: securechain:Hardware/-
        example_subject_type: securechain_Hardware
    - object:
        example_object: '%240.99_kindle_books_project'
        example_object_type: string
        example_predicate: hsdo:name
        example_subject: schema:Organization/%25240.99_kindle_books_project
        example_subject_type: hsdo_Organization
    - object:
        example_object: Permission to use, copy, modify, and/or distribute this software
          for any
        example_object_type: string
        example_predicate: hsdo:name
        example_subject: securechain:License/0bsd
        example_subject_type: hsdo_CreativeWork
    - object:
        example_object: ''
        example_object_type: string
        example_predicate: hsdo:name
        example_subject: securechain:Software/
        example_subject_type: securechain_Software
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: hsdo:name
    alias: hsdo_name
    owner: securechain_SoftwareVersion
    domain_of:
    - hsdo_CreativeWork
    - hsdo_Organization
    - securechain_Hardware
    - securechain_Software
    range: string
  hsdo_contributor:
    name: hsdo_contributor
    annotations:
      hsdo_Person:
        tag: hsdo_Person
        value: 33048
    description: A secondary contributor to the CreativeWork or Event.
    title: contributor
    examples:
    - object:
        example_object: schema:Person/yrnkrn
        example_object_type: hsdo_Person
        example_predicate: hsdo:contributor
        example_subject: securechain:Software/zapcc
        example_subject_type: None
    - object:
        example_object: schema:Person/JosephA-packt
        example_object_type: hsdo_Person
        example_predicate: hsdo:contributor
        example_subject: securechain:Software/3D-Graphics-Rendering-Cookbook
        example_subject_type: securechain_Software
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: hsdo:contributor
    alias: hsdo_contributor
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Software
    range: hsdo_Person
  securechain_hasSoftwareVersion:
    name: securechain_hasSoftwareVersion
    annotations:
      securechain_SoftwareVersion:
        tag: securechain_SoftwareVersion
        value: 164001
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: securechain:SoftwareVersion/#%22%2F%2Fapi%23%2A
        example_object_type: securechain_SoftwareVersion
        example_predicate: securechain:hasSoftwareVersion
        example_subject: securechain:Software/
        example_subject_type: securechain_Software
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:hasSoftwareVersion
    alias: securechain_hasSoftwareVersion
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Software
    range: securechain_SoftwareVersion
class_uri: securechain:SoftwareVersion

```
</details>