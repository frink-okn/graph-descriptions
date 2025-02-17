

# Class: No class (type) name specified (securechain_Software)


_No class (type) description specified_






This class occurs 34469 times.


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

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | The name of the item <br/>  | direct | 34466 |
| [hsdo_contributor](../slots/hsdo_contributor.md) | 0..1 <br/> [HsdoPerson](../classes/HsdoPerson.md) | A secondary contributor to the CreativeWork or Event <br/>  | direct | 33048 |
| [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | 0..1 <br/> [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | No slot (predicate) description specified <br/>  | direct | 164001 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: securechain_Software
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 34469
description: No class (type) description specified
title: No class (type) name specified
from_schema: secure-chain-kg
rank: 1000
is_a: hsdo_SoftwareApplication
slots:
- hsdo_name
- hsdo_contributor
- securechain_hasSoftwareVersion
slot_usage:
  hsdo_contributor:
    name: hsdo_contributor
    annotations:
      hsdo_Person:
        tag: hsdo_Person
        value: 33048
  hsdo_name:
    name: hsdo_name
    annotations:
      string:
        tag: string
        value: 34466
  securechain_hasSoftwareVersion:
    name: securechain_hasSoftwareVersion
    annotations:
      securechain_SoftwareVersion:
        tag: securechain_SoftwareVersion
        value: 164001
class_uri: securechain:Software

```
</details>

### Induced

<details>

```yaml
name: securechain_Software
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 34469
description: No class (type) description specified
title: No class (type) name specified
from_schema: secure-chain-kg
rank: 1000
is_a: hsdo_SoftwareApplication
slot_usage:
  hsdo_contributor:
    name: hsdo_contributor
    annotations:
      hsdo_Person:
        tag: hsdo_Person
        value: 33048
  hsdo_name:
    name: hsdo_name
    annotations:
      string:
        tag: string
        value: 34466
  securechain_hasSoftwareVersion:
    name: securechain_hasSoftwareVersion
    annotations:
      securechain_SoftwareVersion:
        tag: securechain_SoftwareVersion
        value: 164001
attributes:
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
    owner: securechain_Software
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
    owner: securechain_Software
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
    owner: securechain_Software
    domain_of:
    - securechain_Software
    range: securechain_SoftwareVersion
class_uri: securechain:Software

```
</details>