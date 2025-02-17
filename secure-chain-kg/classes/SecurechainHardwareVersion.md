

# Class: No class (type) name specified (securechain_HardwareVersion)


_No class (type) description specified_






This class occurs 57295 times.


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

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [securechain_versionName](../slots/securechain_versionName.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot (predicate) description specified <br/>  | direct | 57295 |
| [securechain_vulnerableTo](../slots/securechain_vulnerableTo.md) | 0..1 <br/> [SecurechainVulnerability](../classes/SecurechainVulnerability.md) | No slot (predicate) description specified <br/>  | direct | 445386 |
| [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | 0..1 <br/> [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No slot (predicate) description specified | [SecurechainHardware](../classes/SecurechainHardware.md) |  |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | The name of the item | [SecurechainHardware](../classes/SecurechainHardware.md) |  |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SecurechainHardware](../classes/SecurechainHardware.md) | [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | range | [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) |
| [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | range | [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: securechain_HardwareVersion
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 57295
description: No class (type) description specified
title: No class (type) name specified
from_schema: secure-chain-kg
rank: 1000
is_a: securechain_Hardware
slots:
- securechain_versionName
- securechain_vulnerableTo
slot_usage:
  securechain_versionName:
    name: securechain_versionName
    annotations:
      string:
        tag: string
        value: 57295
  securechain_vulnerableTo:
    name: securechain_vulnerableTo
    annotations:
      securechain_Vulnerability:
        tag: securechain_Vulnerability
        value: 445386
class_uri: securechain:HardwareVersion

```
</details>

### Induced

<details>

```yaml
name: securechain_HardwareVersion
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 57295
description: No class (type) description specified
title: No class (type) name specified
from_schema: secure-chain-kg
rank: 1000
is_a: securechain_Hardware
slot_usage:
  securechain_versionName:
    name: securechain_versionName
    annotations:
      string:
        tag: string
        value: 57295
  securechain_vulnerableTo:
    name: securechain_vulnerableTo
    annotations:
      securechain_Vulnerability:
        tag: securechain_Vulnerability
        value: 445386
attributes:
  securechain_versionName:
    name: securechain_versionName
    annotations:
      string:
        tag: string
        value: 57295
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
    owner: securechain_HardwareVersion
    domain_of:
    - securechain_HardwareVersion
    - securechain_SoftwareVersion
    range: string
  securechain_vulnerableTo:
    name: securechain_vulnerableTo
    annotations:
      securechain_Vulnerability:
        tag: securechain_Vulnerability
        value: 445386
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
    owner: securechain_HardwareVersion
    domain_of:
    - securechain_HardwareVersion
    - securechain_SoftwareVersion
    range: securechain_Vulnerability
  securechain_hasHardwareVersion:
    name: securechain_hasHardwareVersion
    annotations:
      securechain_HardwareVersion:
        tag: securechain_HardwareVersion
        value: 57295
    description: No slot (predicate) description specified
    title: No slot (predicate) name specified
    examples:
    - object:
        example_object: securechain:HardwareVersion/-#-
        example_object_type: securechain_HardwareVersion
        example_predicate: securechain:hasHardwareVersion
        example_subject: securechain:Hardware/-
        example_subject_type: securechain_Hardware
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:hasHardwareVersion
    alias: securechain_hasHardwareVersion
    owner: securechain_HardwareVersion
    domain_of:
    - securechain_Hardware
    range: securechain_HardwareVersion
  hsdo_name:
    name: hsdo_name
    annotations:
      string:
        tag: string
        value: 53378
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
    owner: securechain_HardwareVersion
    domain_of:
    - hsdo_CreativeWork
    - hsdo_Organization
    - securechain_Hardware
    - securechain_Software
    range: string
class_uri: securechain:HardwareVersion

```
</details>