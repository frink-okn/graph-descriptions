

# Class: TODO -- what's a good name for what this class (type) describes? (sdoh_CreativeWork)


_TODO -- tell the world what this class (type) describes._





URI: [sdoh:CreativeWork](http://schema.org/CreativeWork)






```mermaid
 classDiagram
    class SdohCreativeWork
    click SdohCreativeWork href "../SdohCreativeWork"
      SdohCreativeWork : sdoh_identifier
        
          
    
    
    SdohCreativeWork --> "0..1" String : sdoh_identifier
    click String href "../String"

        
      SdohCreativeWork : sdoh_name
        
          
    
    
    SdohCreativeWork --> "0..1" String : sdoh_name
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sdoh_name](../slots/sdoh_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_identifier](../slots/sdoh_identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |










## Examples

| Value |
| --- |
| securechain:License/zlib |

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
| self | sdoh:CreativeWork |
| native | secure-chain-kg/develop/:SdohCreativeWork |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_CreativeWork
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 20 instances of this class.
examples:
- value: securechain:License/zlib
from_schema: secure-chain-kg/develop
slots:
- sdoh_name
- sdoh_identifier
class_uri: sdoh:CreativeWork

```
</details>

### Induced

<details>
```yaml
name: sdoh_CreativeWork
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 20 instances of this class.
examples:
- value: securechain:License/zlib
from_schema: secure-chain-kg/develop
attributes:
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
    owner: sdoh_CreativeWork
    domain_of:
    - securechain_Hardware
    - securechain_Software
    - sdoh_CreativeWork
    - sdoh_Organization
    range: string
  sdoh_identifier:
    name: sdoh_identifier
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 259334 occurrences with subject type securechain_Vulnerability and object type
      string.
    - 30434 occurrences with subject type sdoh_Person and object type string.
    - 445 occurrences with subject type securechain_VulnerabilityType and object type
      string.
    - 887 occurrences with subject type sdoh_Organization and object type string.
    - 20 occurrences with subject type sdoh_CreativeWork and object type string.
    examples:
    - value: securechain:Vulnerability/CVE-2023-52458 sdoh:identifier CVE-2023-52458
    - value: schema:Person/Touhou-fan sdoh:identifier Touhou-fan
    - value: securechain:VulnerabilityType/CWE-842 sdoh:identifier CWE-842
    - value: schema:Organization/Basecamp sdoh:identifier Q36908
    - value: securechain:License/bsl-1.0 sdoh:identifier bsl-1.0
    from_schema: secure-chain-kg/develop
    rank: 1000
    slot_uri: sdoh:identifier
    alias: sdoh_identifier
    owner: sdoh_CreativeWork
    domain_of:
    - securechain_Vulnerability
    - securechain_VulnerabilityType
    - sdoh_CreativeWork
    - sdoh_Organization
    - sdoh_Person
    range: string
class_uri: sdoh:CreativeWork

```
</details>