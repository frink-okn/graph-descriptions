

# Class: TODO -- what's a good name for what this class (type) describes? (securechain_Software)


_TODO -- tell the world what this class (type) describes._





URI: [securechain:Software](https://w3id.org/secure-chain/Software)






```mermaid
 classDiagram
    class SecurechainSoftware
    click SecurechainSoftware href "../SecurechainSoftware"
      SecurechainSoftware : sdoh_contributor
        
          
    
    
    SecurechainSoftware --> "0..1" SdohPerson : sdoh_contributor
    click SdohPerson href "../SdohPerson"

        
      SecurechainSoftware : sdoh_name
        
          
    
    
    SecurechainSoftware --> "0..1" String : sdoh_name
    click String href "../String"

        
      SecurechainSoftware : securechain_hasSoftwareVersion
        
          
    
    
    SecurechainSoftware --> "0..1" SecurechainSoftwareVersion : securechain_hasSoftwareVersion
    click SecurechainSoftwareVersion href "../SecurechainSoftwareVersion"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [securechain_hasSoftwareVersion](../slots/securechain_hasSoftwareVersion.md) | 0..1 <br/> [SecurechainSoftwareVersion](../classes/SecurechainSoftwareVersion.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_contributor](../slots/sdoh_contributor.md) | 0..1 <br/> [SdohPerson](../classes/SdohPerson.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_name](../slots/sdoh_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |










## Examples

| Value |
| --- |
| securechain:Software/libwcs5 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: secure-chain-kg/develop




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | securechain:Software |
| native | secure-chain-kg/develop/:SecurechainSoftware |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: securechain_Software
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 34469 instances of this class.
examples:
- value: securechain:Software/libwcs5
from_schema: secure-chain-kg/develop
slots:
- securechain_hasSoftwareVersion
- sdoh_contributor
- sdoh_name
class_uri: securechain:Software

```
</details>

### Induced

<details>
```yaml
name: securechain_Software
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 34469 instances of this class.
examples:
- value: securechain:Software/libwcs5
from_schema: secure-chain-kg/develop
attributes:
  securechain_hasSoftwareVersion:
    name: securechain_hasSoftwareVersion
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 164001 occurrences with subject type securechain_Software and object type securechain_SoftwareVersion.
    examples:
    - value: securechain:Software/platform_system_core securechain:hasSoftwareVersion
        securechain:SoftwareVersion/platform_system_core#android-wear-o-preview-4
    from_schema: secure-chain-kg/develop
    rank: 1000
    slot_uri: securechain:hasSoftwareVersion
    alias: securechain_hasSoftwareVersion
    owner: securechain_Software
    domain_of:
    - securechain_Software
    range: securechain_SoftwareVersion
  sdoh_contributor:
    name: sdoh_contributor
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 33048 occurrences with subject type securechain_Software and object type sdoh_Person.
    - 3668 occurrences on untyped entities with type sdoh_Person.
    examples:
    - value: securechain:Software/filesystem sdoh:contributor schema:Person/nightlark
    from_schema: secure-chain-kg/develop
    rank: 1000
    slot_uri: sdoh:contributor
    alias: sdoh_contributor
    owner: securechain_Software
    domain_of:
    - securechain_Software
    range: sdoh_Person
  sdoh_name:
    name: sdoh_name
    description: TODO -- tell the world what this slot (predicate) describes.
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
    - value: securechain:Hardware/field_programmable_gate_array_programmable_acceleration_card_n3000
        sdoh:name field_programmable_gate_array_programmable_acceleration_card_n3000
    - value: schema:Organization/social_microblogging_pro_project sdoh:name social_microblogging_pro_project
    - value: securechain:Software/libcupscgi1 sdoh:name libcupscgi1
    - value: securechain:License/unlicense sdoh:name This is free and unencumbered
        software released into the public domain.
    from_schema: secure-chain-kg/develop
    rank: 1000
    slot_uri: sdoh:name
    alias: sdoh_name
    owner: securechain_Software
    domain_of:
    - securechain_Hardware
    - securechain_Software
    - sdoh_CreativeWork
    - sdoh_Organization
    range: string
class_uri: securechain:Software

```
</details>