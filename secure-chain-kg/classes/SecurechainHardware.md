

# Class: No class (type) name specified (securechain_Hardware)


_No class (type) description specified_





URI: [securechain:Hardware](https://w3id.org/secure-chain/Hardware)






```mermaid
 classDiagram
    class SecurechainHardware
    click SecurechainHardware href "../SecurechainHardware"
      HsdoProduct <|-- SecurechainHardware
        click HsdoProduct href "../HsdoProduct"
      

      SecurechainHardware <|-- SecurechainHardwareVersion
        click SecurechainHardwareVersion href "../SecurechainHardwareVersion"
      
      
      SecurechainHardware : hsdo_name
        
          
    
    
    SecurechainHardware --> "0..1" String : hsdo_name
    click String href "../String"

        
      SecurechainHardware : securechain_hasHardwareVersion
        
          
    
    
    SecurechainHardware --> "0..1" SecurechainHardwareVersion : securechain_hasHardwareVersion
    click SecurechainHardwareVersion href "../SecurechainHardwareVersion"

        
      
```





## Inheritance
* [HsdoProduct](../classes/HsdoProduct.md)
    * **SecurechainHardware**
        * [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 53378 occurrences with subject type securechain_Hardware and object type string.<br/>22002 occurrences with subject type hsdo_Organization and object type string.<br/>20 occurrences with subject type hsdo_CreativeWork and object type string.<br/>34466 occurrences with subject type securechain_Software and object type string. | direct |
| [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | 0..1 <br/> [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No slot (predicate) description specified <br/> 57295 occurrences with subject type securechain_Hardware and object type securechain_HardwareVersion. | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | [hsdo_manufacturer](../slots/hsdo_manufacturer.md) | range | [SecurechainHardware](../classes/SecurechainHardware.md) |






## Identifier and Mapping Information








## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:Hardware |
| native | secure-chain-kg/:SecurechainHardware |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: securechain_Hardware
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 53378 occurrences.
rank: 1000
is_a: hsdo_Product
slots:
- hsdo_name
- securechain_hasHardwareVersion
class_uri: securechain:Hardware

```
</details>

### Induced

<details>
```yaml
name: securechain_Hardware
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 53378 occurrences.
rank: 1000
is_a: hsdo_Product
attributes:
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
    owner: securechain_Hardware
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
    owner: securechain_Hardware
    domain_of:
    - securechain_Hardware
    range: securechain_HardwareVersion
class_uri: securechain:Hardware

```
</details>