

# Class: No class (type) name specified (securechain_SoftwareVersion)


_No class (type) description specified_





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

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [securechain_vulnerableTo](../slots/securechain_vulnerableTo.md) | 0..1 <br/> [SecurechainVulnerability](../classes/SecurechainVulnerability.md) | No slot (predicate) description specified <br/> 445386 occurrences with subject type securechain_HardwareVersion and object type securechain_Vulnerability.<br/>5067 occurrences with subject type securechain_SoftwareVersion and object type securechain_Vulnerability.<br/>21897 occurrences with untyped subjects and object type https://w3id.org/secure-chain/Vulnerability. | direct |
| [securechain_versionName](../slots/securechain_versionName.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 57295 occurrences with subject type securechain_HardwareVersion and object type string.<br/>164000 occurrences with subject type securechain_SoftwareVersion and object type string. | direct |
| [securechain_dependsOn](../slots/securechain_dependsOn.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No slot (predicate) description specified <br/> 696916 occurrences with subject type securechain_SoftwareVersion and object type securechain_SoftwareVersion.<br/>982961 occurrences with untyped subjects and object type https://w3id.org/secure-chain/SoftwareVersion.<br/>2 occurrences with subject type securechain_SoftwareVersion and object type uri.<br/>39 occurrences with untyped subjects and object type uri. | direct |
| [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | 0..1 <br/> [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No slot (predicate) description specified | [SecurechainSoftware](../classes/SecurechainSoftware.md) |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified | [SecurechainSoftware](../classes/SecurechainSoftware.md) |
| [hsdo_contributor](../slots/hsdo_contributor.md) | 0..1 <br/> [HsdoPerson](../classes/HsdoPerson.md) | No slot (predicate) description specified | [SecurechainSoftware](../classes/SecurechainSoftware.md) |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SecurechainSoftware](../classes/SecurechainSoftware.md) | [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_dependsOn](../slots/securechain_dependsOn.md) | any_of[range] | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |
| [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | range | [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) |






## Identifier and Mapping Information








## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:SoftwareVersion |
| native | secure-chain-kg/:SecurechainSoftwareVersion |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: securechain_SoftwareVersion
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 164001 occurrences.
rank: 1000
is_a: securechain_Software
slots:
- securechain_vulnerableTo
- securechain_versionName
- securechain_dependsOn
class_uri: securechain:SoftwareVersion

```
</details>

### Induced

<details>
```yaml
name: securechain_SoftwareVersion
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 164001 occurrences.
rank: 1000
is_a: securechain_Software
attributes:
  securechain_vulnerableTo:
    name: securechain_vulnerableTo
    description: No slot (predicate) description specified
    comments:
    - 445386 occurrences with subject type securechain_HardwareVersion and object
      type securechain_Vulnerability.
    - 5067 occurrences with subject type securechain_SoftwareVersion and object type
      securechain_Vulnerability.
    - 21897 occurrences with untyped subjects and object type https://w3id.org/secure-chain/Vulnerability.
    examples:
    - description: securechain_HardwareVersion → securechain_Vulnerability
      object:
        example_object: securechain:Vulnerability/CVE-2018-13888
        example_object_type: securechain_Vulnerability
        example_predicate: securechain:vulnerableTo
        example_subject: securechain:HardwareVersion/zz_qcs605#-
        example_subject_type: securechain_HardwareVersion
    - description: securechain_SoftwareVersion → securechain_Vulnerability
      object:
        example_object: securechain:Vulnerability/CVE-2018-1000637
        example_object_type: securechain_Vulnerability
        example_predicate: securechain:vulnerableTo
        example_subject: securechain:SoftwareVersion/zutils#1.8-3
        example_subject_type: securechain_SoftwareVersion
    - description: None → securechain_Vulnerability
      object:
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
  securechain_versionName:
    name: securechain_versionName
    description: No slot (predicate) description specified
    comments:
    - 57295 occurrences with subject type securechain_HardwareVersion and object type
      string.
    - 164000 occurrences with subject type securechain_SoftwareVersion and object
      type string.
    examples:
    - description: securechain_HardwareVersion → string
      object:
        example_object: '-'
        example_object_type: string
        example_predicate: securechain:versionName
        example_subject: securechain:HardwareVersion/-#-
        example_subject_type: securechain_HardwareVersion
    - description: securechain_SoftwareVersion → string
      object:
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
  securechain_dependsOn:
    name: securechain_dependsOn
    description: No slot (predicate) description specified
    comments:
    - 696916 occurrences with subject type securechain_SoftwareVersion and object
      type securechain_SoftwareVersion.
    - 982961 occurrences with untyped subjects and object type https://w3id.org/secure-chain/SoftwareVersion.
    - 2 occurrences with subject type securechain_SoftwareVersion and object type
      uri.
    - 39 occurrences with untyped subjects and object type uri.
    examples:
    - description: securechain_SoftwareVersion → securechain_SoftwareVersion
      object:
        example_object: securechain:SoftwareVersion/libc6#%3E%3E+2.39%26%3C%3C+2.40
        example_object_type: securechain_SoftwareVersion
        example_predicate: securechain:dependsOn
        example_subject: securechain:SoftwareVersion/zzuf#0.15-4
        example_subject_type: securechain_SoftwareVersion
    - description: None → securechain_SoftwareVersion
      object:
        example_object: securechain:SoftwareVersion/libc6#%3E%3E+2.39%26%3C%3C+2.40
        example_object_type: securechain_SoftwareVersion
        example_predicate: securechain:dependsOn
        example_subject: securechain:SoftwareVersion/zzuf#0.15-4%2Bb3
        example_subject_type: None
    - description: securechain_SoftwareVersion → uri
      object:
        example_object: securechain:SoftwareVersion/dosbox#0.74-2
        example_object_type: uri
        example_predicate: securechain:dependsOn
        example_subject: securechain:SoftwareVersion/dosbox-staging#svn_RELEASE_0_74_2
        example_subject_type: securechain_SoftwareVersion
    - description: None → uri
      object:
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
  securechain_hasSoftwareVersion:
    name: securechain_hasSoftwareVersion
    description: No slot (predicate) description specified
    comments:
    - 164001 occurrences with subject type securechain_Software and object type securechain_SoftwareVersion.
    examples:
    - description: securechain_Software → securechain_SoftwareVersion
      object:
        example_object: securechain:SoftwareVersion/zzuf#0.15-4
        example_object_type: securechain_SoftwareVersion
        example_predicate: securechain:hasSoftwareVersion
        example_subject: securechain:Software/zzuf
        example_subject_type: securechain_Software
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:hasSoftwareVersion
    alias: securechain_hasSoftwareVersion
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Software
    range: securechain_SoftwareVersion
  hsdo_name:
    name: hsdo_name
    description: No slot (predicate) description specified
    comments:
    - 53378 occurrences with subject type securechain_Hardware and object type string.
    - 22002 occurrences with subject type hsdo_Organization and object type string.
    - 20 occurrences with subject type hsdo_CreativeWork and object type string.
    - 34466 occurrences with subject type securechain_Software and object type string.
    examples:
    - description: securechain_Hardware → string
      object:
        example_object: '-'
        example_object_type: string
        example_predicate: hsdo:name
        example_subject: securechain:Hardware/-
        example_subject_type: securechain_Hardware
    - description: hsdo_Organization → string
      object:
        example_object: '%240.99_kindle_books_project'
        example_object_type: string
        example_predicate: hsdo:name
        example_subject: schema:Organization/%25240.99_kindle_books_project
        example_subject_type: hsdo_Organization
    - description: hsdo_CreativeWork → string
      object:
        example_object: Permission to use, copy, modify, and/or distribute this software
          for any
        example_object_type: string
        example_predicate: hsdo:name
        example_subject: securechain:License/0bsd
        example_subject_type: hsdo_CreativeWork
    - description: securechain_Software → string
      object:
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
    description: No slot (predicate) description specified
    comments:
    - 3668 occurrences with untyped subjects and object type http://schema.org/Person.
    - 33048 occurrences with subject type securechain_Software and object type hsdo_Person.
    examples:
    - description: None → hsdo_Person
      object:
        example_object: schema:Person/yrnkrn
        example_object_type: hsdo_Person
        example_predicate: hsdo:contributor
        example_subject: securechain:Software/zapcc
        example_subject_type: None
    - description: securechain_Software → hsdo_Person
      object:
        example_object: schema:Person/zander
        example_object_type: hsdo_Person
        example_predicate: hsdo:contributor
        example_subject: securechain:Software/zxing-cpp
        example_subject_type: securechain_Software
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: hsdo:contributor
    alias: hsdo_contributor
    owner: securechain_SoftwareVersion
    domain_of:
    - securechain_Software
    range: hsdo_Person
class_uri: securechain:SoftwareVersion

```
</details>