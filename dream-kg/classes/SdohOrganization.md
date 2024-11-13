

# Class: Organization (sdoh_Organization)


_An organization such as a school, NGO, corporation, club, etc._





URI: [sdoh:Organization](http://schema.org/Organization)






```mermaid
 classDiagram
    class SdohOrganization
    click SdohOrganization href "../SdohOrganization"
      SdohOrganization : sdoh_name
        
          
    
    
    SdohOrganization --> "0..1" String : sdoh_name
    click String href "../String"

        
      SdohOrganization : sdoh_sameAs
        
          
    
    
    SdohOrganization --> "0..1" Uri : sdoh_sameAs
    click Uri href "../Uri"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sdoh_name](../slots/sdoh_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_sameAs](../slots/sdoh_sameAs.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohService](../classes/SdohService.md) | [sdoh_provider](../slots/sdoh_provider.md) | range | [SdohOrganization](../classes/SdohOrganization.md) |







## Examples

| Value |
| --- |
| dreamkg:service/provider/6032260047568896 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | sdoh:Organization |
| native | dream-kg/:SdohOrganization |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_Organization
description: An organization such as a school, NGO, corporation, club, etc.
title: Organization
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 87 instances of this class.
examples:
- value: dreamkg:service/provider/6032260047568896
from_schema: dream-kg
slots:
- sdoh_name
- sdoh_sameAs
class_uri: sdoh:Organization

```
</details>

### Induced

<details>
```yaml
name: sdoh_Organization
description: An organization such as a school, NGO, corporation, club, etc.
title: Organization
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 87 instances of this class.
examples:
- value: dreamkg:service/provider/6032260047568896
from_schema: dream-kg
attributes:
  sdoh_name:
    name: sdoh_name
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 89 occurrences with subject type sdoh_Organization and object type string.
    - 88 occurrences with subject type sdoh_Service and object type string.
    examples:
    - value: dreamkg:service/provider/5385341432496128 sdoh:name Better Living Center
    - value: dreamkg:service/4829363626049536 sdoh:name Adult Inpatient Mental Health
        Services
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:name
    alias: sdoh_name
    owner: sdoh_Organization
    domain_of:
    - sdoh_Organization
    - sdoh_Service
    range: string
  sdoh_sameAs:
    name: sdoh_sameAs
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 127 occurrences with subject type sdoh_Organization and object type uri.
    examples:
    - value: dreamkg:service/provider/5715375002484736 sdoh:sameAs https://www.facebook.com/livengrin
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:sameAs
    alias: sdoh_sameAs
    owner: sdoh_Organization
    domain_of:
    - sdoh_Organization
    range: uri
class_uri: sdoh:Organization

```
</details>