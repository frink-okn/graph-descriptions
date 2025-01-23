

# Class: No class (type) name specified (securechain_Software)


_No class (type) description specified_





URI: [securechain:Software](https://w3id.org/secure-chain/Software)






```mermaid
 classDiagram
    class SecurechainSoftware
    click SecurechainSoftware href "../SecurechainSoftware"
      HsdoSoftwareApplication <|-- SecurechainSoftware
        click HsdoSoftwareApplication href "../HsdoSoftwareApplication"
      

      SecurechainSoftware <|-- SecurechainSoftwareVersion
        click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"
      
      
      SecurechainSoftware : hsdo_contributor
        
          
    
    
    SecurechainSoftware --> "0..1" HsdoPerson : hsdo_contributor
    click HsdoPerson href "../HsdoPerson"

        
      SecurechainSoftware : hsdo_name
        
          
    
    
    SecurechainSoftware --> "0..1" String : hsdo_name
    click String href "../String"

        
      SecurechainSoftware : securechain_hasSoftwareVersion
        
          
    
    
    SecurechainSoftware --> "0..1" SecurechainSoftwareVersion : securechain_hasSoftwareVersion
    click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"

        
      
```





## Inheritance
* [HsdoSoftwareApplication](../classes/HsdoSoftwareApplication.md)
    * **SecurechainSoftware**
        * [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | 0..1 <br/> [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No slot (predicate) description specified <br/> 164001 occurrences with subject type securechain_Software and object type securechain_SoftwareVersion. | direct |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 53378 occurrences with subject type securechain_Hardware and object type string.<br/>22002 occurrences with subject type hsdo_Organization and object type string.<br/>20 occurrences with subject type hsdo_CreativeWork and object type string.<br/>34466 occurrences with subject type securechain_Software and object type string. | direct |
| [hsdo_contributor](../slots/hsdo_contributor.md) | 0..1 <br/> [HsdoPerson](../classes/HsdoPerson.md) | No slot (predicate) description specified <br/> 3668 occurrences with untyped subjects and object type http://schema.org/Person.<br/>33048 occurrences with subject type securechain_Software and object type hsdo_Person. | direct |









## Identifier and Mapping Information








## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:Software |
| native | secure-chain-kg/:SecurechainSoftware |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: securechain_Software
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 34469 occurrences.
rank: 1000
is_a: hsdo_SoftwareApplication
slots:
- securechain_hasSoftwareVersion
- hsdo_name
- hsdo_contributor
class_uri: securechain:Software

```
</details>

### Induced

<details>
```yaml
name: securechain_Software
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 34469 occurrences.
rank: 1000
is_a: hsdo_SoftwareApplication
attributes:
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
    owner: securechain_Software
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
    owner: securechain_Software
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
    owner: securechain_Software
    domain_of:
    - securechain_Software
    range: hsdo_Person
class_uri: securechain:Software

```
</details>