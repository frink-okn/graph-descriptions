

# Class: TODO -- what's a good name for this class (type)? (securechain_Hardware)


_No type description provided_





URI: [securechain:Hardware](https://w3id.org/secure-chain/Hardware)






```mermaid
 classDiagram
    class SecurechainHardware
    click SecurechainHardware href "../SecurechainHardware"
      SdohProduct <|-- SecurechainHardware
        click SdohProduct href "../SdohProduct"
      

      SecurechainHardware <|-- SecurechainHardwareVersion
        click SecurechainHardwareVersion href "../SecurechainHardwareVersion"
      
      
      SecurechainHardware : sdoh_name
        
          
    
    
    SecurechainHardware --> "0..1" String : sdoh_name
    click String href "../String"

        
      SecurechainHardware : securechain_hasHardwareVersion
        
          
    
    
    SecurechainHardware --> "0..1" SecurechainHardwareVersion : securechain_hasHardwareVersion
    click SecurechainHardwareVersion href "../SecurechainHardwareVersion"

        
      
```





## Inheritance
* [SdohProduct](../classes/SdohProduct.md)
    * **SecurechainHardware**
        * [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [securechain_hasHardwareVersion](../slots/securechain_hasHardwareVersion.md) | 0..1 <br/> [SecurechainHardwareVersion](../classes/SecurechainHardwareVersion.md) | No slot description provided | direct |
| [sdoh_name](../slots/sdoh_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohOrganization](../classes/SdohOrganization.md) | [sdoh_manufacturer](../slots/sdoh_manufacturer.md) | range | [SecurechainHardware](../classes/SecurechainHardware.md) |







## Examples

| Value |
| --- |
| securechain:Hardware/xeon_gold_6222 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg




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
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 53378 occurences.
examples:
- value: securechain:Hardware/xeon_gold_6222
from_schema: secure-chain-kg
rank: 1000
is_a: sdoh_Product
slots:
- securechain_hasHardwareVersion
- sdoh_name
class_uri: securechain:Hardware

```
</details>

### Induced

<details>
```yaml
name: securechain_Hardware
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 53378 occurences.
examples:
- value: securechain:Hardware/xeon_gold_6222
from_schema: secure-chain-kg
rank: 1000
is_a: sdoh_Product
attributes:
  securechain_hasHardwareVersion:
    name: securechain_hasHardwareVersion
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 57295 occurrences with subject type securechain_Hardware and object type securechain_HardwareVersion.
    examples:
    - value: securechain:Hardware/core_i5 securechain:hasHardwareVersion securechain:HardwareVersion/core_i5#2557m
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: securechain:hasHardwareVersion
    alias: securechain_hasHardwareVersion
    owner: securechain_Hardware
    domain_of:
    - securechain_Hardware
    range: securechain_HardwareVersion
  sdoh_name:
    name: sdoh_name
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 53378 occurrences with subject type securechain_Hardware and object type string.
    - 22002 occurrences with subject type sdoh_Organization and object type string.
    - 34469 occurrences with subject type securechain_Software and object type string.
    - 20 occurrences with subject type sdoh_CreativeWork and object type string.
    examples:
    - value: securechain:Hardware/nvr1xxx sdoh:name nvr1xxx
    - value: schema:Organization/opencaching sdoh:name opencaching
    - value: securechain:Software/libdime sdoh:name libdime
    - value: securechain:License/mit sdoh:name MIT License
    from_schema: secure-chain-kg
    rank: 1000
    slot_uri: sdoh:name
    alias: sdoh_name
    owner: securechain_Hardware
    domain_of:
    - sdoh_CreativeWork
    - sdoh_Organization
    - securechain_Hardware
    - securechain_Software
    range: string
class_uri: securechain:Hardware

```
</details>