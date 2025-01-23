

# Class: No class (type) name specified (securechain_HardwareVersion)


_No class (type) description specified_





URI: [securechain:HardwareVersion](https://w3id.org/secure-chain/HardwareVersion)






```mermaid
 classDiagram
    class SecurechainHardwareVersion
    click SecurechainHardwareVersion href "../SecurechainHardwareVersion"
      SecurechainHardware <|-- SecurechainHardwareVersion
        click SecurechainHardware href "../SecurechainHardware"
      
      SecurechainHardwareVersion : hsdo_name
        
          
    
    
    SecurechainHardwareVersion --> "0..1" String : hsdo_name
    click String href "../String"

        
      SecurechainHardwareVersion : securechain_hasHardwareVersion
        
          
    
    
    SecurechainHardwareVersion --> "0..1" SecurechainHardwareVersion : securechain_hasHardwareVersion
    click SecurechainHardwareVersion href "../SecurechainHardwareVersion"

        
      SecurechainHardwareVersion : securechain_versionName
        
          
    
    
    SecurechainHardwareVersion --> "0..1" String : securechain_versionName
    click String href "../String"

        
      SecurechainHardwareVersion : securechain_vulnerableTo
        
          
    
    
    SecurechainHardwareVersion --> "0..1" SecurechainVulnerability : securechain_vulnerableTo
    click SecurechainVulnerability href "../SecurechainVulnerability"

        
      
```





## Inheritance
* [HsdoProduct](../classes/HsdoProduct.md)
    * [SecurechainHardware](../classes/SecurechainHardware.md)
        * **SecurechainHardwareVersion**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [securechain_vulnerableTo](../slots/securechain_vulnerableTo.md) | 0..1 <br/> [SecurechainVulnerability](../classes/SecurechainVulnerability.md) | No slot (predicate) description specified <br/> 445386 occurrences with subject type securechain_HardwareVersion and object type securechain_Vulnerability.<br/>5067 occurrences with subject type securechain_SoftwareVersion and object type securechain_Vulnerability.<br/>21897 occurrences with untyped subjects and object type https://w3id.org/secure-chain/Vulnerability. | direct |
| [securechain_versionName](../slots/securechain_versionName.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 57295 occurrences with subject type securechain_HardwareVersion and object type string.<br/>164000 occurrences with subject type securechain_SoftwareVersion and object type string. | direct |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified | [SecurechainHardware](../classes/SecurechainHardware.md) |
| [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | 0..1 <br/> [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No slot (predicate) description specified | [SecurechainHardware](../classes/SecurechainHardware.md) |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SecurechainHardware](../classes/SecurechainHardware.md) | [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | range | [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | range | [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) |






## Identifier and Mapping Information








## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:HardwareVersion |
| native | secure-chain-kg/:SecurechainHardwareVersion |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: securechain_HardwareVersion
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 57295 occurrences.
rank: 1000
is_a: securechain_Hardware
slots:
- securechain_vulnerableTo
- securechain_versionName
class_uri: securechain:HardwareVersion

```
</details>

### Induced

<details>
```yaml
name: securechain_HardwareVersion
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 57295 occurrences.
rank: 1000
is_a: securechain_Hardware
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
    owner: securechain_HardwareVersion
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
    owner: securechain_HardwareVersion
    domain_of:
    - securechain_HardwareVersion
    - securechain_SoftwareVersion
    range: string
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
    owner: securechain_HardwareVersion
    domain_of:
    - hsdo_CreativeWork
    - hsdo_Organization
    - securechain_Hardware
    - securechain_Software
    range: string
  securechain_hasHardwareVersion:
    name: securechain_hasHardwareVersion
    description: No slot (predicate) description specified
    comments:
    - 57295 occurrences with subject type securechain_Hardware and object type securechain_HardwareVersion.
    examples:
    - description: securechain_Hardware → securechain_HardwareVersion
      object:
        example_object: securechain:HardwareVersion/zz_qcs605#-
        example_object_type: securechain_HardwareVersion
        example_predicate: securechain:hasHardwareVersion
        example_subject: securechain:Hardware/zz_qcs605
        example_subject_type: securechain_Hardware
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:hasHardwareVersion
    alias: securechain_hasHardwareVersion
    owner: securechain_HardwareVersion
    domain_of:
    - securechain_Hardware
    range: securechain_HardwareVersion
class_uri: securechain:HardwareVersion

```
</details>