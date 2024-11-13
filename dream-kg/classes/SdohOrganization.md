

# Class: TODO -- what's a good name for what this class (type) describes? (sdoh_Organization)


_TODO -- tell the world what this class (type) describes._





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
| [sdoh_sameAs](../slots/sdoh_sameAs.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_name](../slots/sdoh_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohService](../classes/SdohService.md) | [sdoh_provider](../slots/sdoh_provider.md) | range | [SdohOrganization](../classes/SdohOrganization.md) |







## Examples

| Value |
| --- |
| dreamkg:service/provider/5185303560585216 |

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
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 87 instances of this class.
examples:
- value: dreamkg:service/provider/5185303560585216
from_schema: dream-kg
slots:
- sdoh_sameAs
- sdoh_name
class_uri: sdoh:Organization

```
</details>

### Induced

<details>
```yaml
name: sdoh_Organization
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 87 instances of this class.
examples:
- value: dreamkg:service/provider/5185303560585216
from_schema: dream-kg
attributes:
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
    - value: dreamkg:service/provider/5929367212130304 sdoh:sameAs https://twitter.com/SalArmyPhilly
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:sameAs
    alias: sdoh_sameAs
    owner: sdoh_Organization
    domain_of:
    - sdoh_Organization
    range: uri
  sdoh_name:
    name: sdoh_name
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 88 occurrences with subject type sdoh_Service and object type string.
    - 89 occurrences with subject type sdoh_Organization and object type string.
    examples:
    - value: dreamkg:service/5112554392387584 sdoh:name Coffee House
    - value: dreamkg:service/provider/5477271096786944 sdoh:name Self Help Movement
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:name
    alias: sdoh_name
    owner: sdoh_Organization
    domain_of:
    - sdoh_Organization
    - sdoh_Service
    range: string
class_uri: sdoh:Organization

```
</details>