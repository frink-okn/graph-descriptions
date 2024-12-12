

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
| [sdoh_sameAs](../slots/sdoh_sameAs.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) | No slot description provided | direct |
| [sdoh_name](../slots/sdoh_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohService](../classes/SdohService.md) | [sdoh_provider](../slots/sdoh_provider.md) | range | [SdohOrganization](../classes/SdohOrganization.md) |







## Examples

| Value |
| --- |
| dreamkg:service/provider/6272068172382208 |

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
- Class with 87 occurences.
examples:
- value: dreamkg:service/provider/6272068172382208
from_schema: dream-kg
rank: 1000
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
description: An organization such as a school, NGO, corporation, club, etc.
title: Organization
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 87 occurences.
examples:
- value: dreamkg:service/provider/6272068172382208
from_schema: dream-kg
rank: 1000
attributes:
  sdoh_sameAs:
    name: sdoh_sameAs
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 127 occurrences with subject type sdoh_Organization and object type uri.
    examples:
    - value: dreamkg:service/provider/5518091445075968 sdoh:sameAs https://www.facebook.com/gpass19120/
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
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 88 occurrences with subject type sdoh_Service and object type string.
    - 89 occurrences with subject type sdoh_Organization and object type string.
    examples:
    - value: dreamkg:service/5175494499368960 sdoh:name Food Baskets
    - value: dreamkg:service/provider/5680777996009472 sdoh:name Youth Service Inc
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