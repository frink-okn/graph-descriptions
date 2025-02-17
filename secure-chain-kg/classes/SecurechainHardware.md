

# Class: No class (type) name specified (securechain_Hardware)


_No class (type) description specified_






This class occurs 53378 times.


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

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | 0..1 <br/> [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No slot (predicate) description specified <br/>  | direct | 57295 |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | The name of the item <br/>  | direct | 53378 |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HsdoOrganization](../classes/HsdoOrganization.md) | [hsdo_manufacturer](../slots/hsdo_manufacturer.md) | range | [SecurechainHardware](../classes/SecurechainHardware.md) |











## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: securechain_Hardware
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 53378
description: No class (type) description specified
title: No class (type) name specified
from_schema: secure-chain-kg
rank: 1000
is_a: hsdo_Product
slots:
- securechain_hasHardwareVersion
- hsdo_name
slot_usage:
  hsdo_name:
    name: hsdo_name
    annotations:
      string:
        tag: string
        value: 53378
  securechain_hasHardwareVersion:
    name: securechain_hasHardwareVersion
    annotations:
      securechain_HardwareVersion:
        tag: securechain_HardwareVersion
        value: 57295
class_uri: securechain:Hardware

```
</details>

### Induced

<details>

```yaml
name: securechain_Hardware
conforms_to: No schema conformance document specified
annotations:
  count:
    tag: count
    value: 53378
description: No class (type) description specified
title: No class (type) name specified
from_schema: secure-chain-kg
rank: 1000
is_a: hsdo_Product
slot_usage:
  hsdo_name:
    name: hsdo_name
    annotations:
      string:
        tag: string
        value: 53378
  securechain_hasHardwareVersion:
    name: securechain_hasHardwareVersion
    annotations:
      securechain_HardwareVersion:
        tag: securechain_HardwareVersion
        value: 57295
attributes:
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
    owner: securechain_Hardware
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
    owner: securechain_Hardware
    domain_of:
    - hsdo_CreativeWork
    - hsdo_Organization
    - securechain_Hardware
    - securechain_Software
    range: string
class_uri: securechain:Hardware

```
</details>