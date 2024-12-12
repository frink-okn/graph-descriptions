

# Class: Service (sdoh_Service)


_A service provided by an organization, e.g. delivery service, print services, etc._





URI: [sdoh:Service](http://schema.org/Service)






```mermaid
 classDiagram
    class SdohService
    click SdohService href "../SdohService"
      SdohService : sdoh_areaServed
        
          
    
    
    SdohService --> "0..1" String : sdoh_areaServed
    click String href "../String"

        
      SdohService : sdoh_availableChannel
        
          
    
    
    SdohService --> "0..1" SdohServiceChannel : sdoh_availableChannel
    click SdohServiceChannel href "../SdohServiceChannel"

        
      SdohService : sdoh_category
        
          
    
    
    SdohService --> "0..1" Any : sdoh_category
    click Any href "../Any"

        
      SdohService : sdoh_description
        
          
    
    
    SdohService --> "0..1" SdohTextObject : sdoh_description
    click SdohTextObject href "../SdohTextObject"

        
      SdohService : sdoh_hoursAvailable
        
          
    
    
    SdohService --> "0..1" SdohOpeningHoursSpecification : sdoh_hoursAvailable
    click SdohOpeningHoursSpecification href "../SdohOpeningHoursSpecification"

        
      SdohService : sdoh_identifier
        
          
    
    
    SdohService --> "0..1" String : sdoh_identifier
    click String href "../String"

        
      SdohService : sdoh_name
        
          
    
    
    SdohService --> "0..1" String : sdoh_name
    click String href "../String"

        
      SdohService : sdoh_provider
        
          
    
    
    SdohService --> "0..1" SdohOrganization : sdoh_provider
    click SdohOrganization href "../SdohOrganization"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sdoh_name](../slots/sdoh_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [sdoh_hoursAvailable](../slots/sdoh_hoursAvailable.md) | 0..1 <br/> [SdohOpeningHoursSpecification](../classes/SdohOpeningHoursSpecification.md) | No slot description provided | direct |
| [sdoh_description](../slots/sdoh_description.md) | 0..1 <br/> [SdohTextObject](../classes/SdohTextObject.md) | No slot description provided | direct |
| [sdoh_availableChannel](../slots/sdoh_availableChannel.md) | 0..1 <br/> [SdohServiceChannel](../classes/SdohServiceChannel.md) | No slot description provided | direct |
| [sdoh_provider](../slots/sdoh_provider.md) | 0..1 <br/> [SdohOrganization](../classes/SdohOrganization.md) | No slot description provided | direct |
| [sdoh_identifier](../slots/sdoh_identifier.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [sdoh_category](../slots/sdoh_category.md) | 0..1 <br/> [SdohCategoryCode](../classes/SdohCategoryCode.md)&nbsp;or&nbsp;<br />[SdohAudience](../classes/SdohAudience.md) | No slot description provided | direct |
| [sdoh_areaServed](../slots/sdoh_areaServed.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |










## Examples

| Value |
| --- |
| dreamkg:service/4964759830003712 |

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
| self | sdoh:Service |
| native | dream-kg/:SdohService |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_Service
description: A service provided by an organization, e.g. delivery service, print services,
  etc.
title: Service
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 87 occurences.
examples:
- value: dreamkg:service/4964759830003712
from_schema: dream-kg
rank: 1000
slots:
- sdoh_name
- sdoh_hoursAvailable
- sdoh_description
- sdoh_availableChannel
- sdoh_provider
- sdoh_identifier
- sdoh_category
- sdoh_areaServed
class_uri: sdoh:Service

```
</details>

### Induced

<details>
```yaml
name: sdoh_Service
description: A service provided by an organization, e.g. delivery service, print services,
  etc.
title: Service
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 87 occurences.
examples:
- value: dreamkg:service/4964759830003712
from_schema: dream-kg
rank: 1000
attributes:
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
    owner: sdoh_Service
    domain_of:
    - sdoh_Organization
    - sdoh_Service
    range: string
  sdoh_hoursAvailable:
    name: sdoh_hoursAvailable
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 609 occurrences with subject type sdoh_Service and object type sdoh_OpeningHoursSpecification.
    examples:
    - value: dreamkg:service/4874573658193920 sdoh:hoursAvailable dreamkg:service/hours/thursday/4874573658193920
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:hoursAvailable
    alias: sdoh_hoursAvailable
    owner: sdoh_Service
    domain_of:
    - sdoh_Service
    range: sdoh_OpeningHoursSpecification
  sdoh_description:
    name: sdoh_description
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_Service and object type sdoh_TextObject.
    examples:
    - value: dreamkg:service/5367371355914240 sdoh:description dreamkg:service/desc/5367371355914240
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:description
    alias: sdoh_description
    owner: sdoh_Service
    domain_of:
    - sdoh_Service
    range: sdoh_TextObject
  sdoh_availableChannel:
    name: sdoh_availableChannel
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 174 occurrences with subject type sdoh_Service and object type sdoh_ServiceChannel.
    examples:
    - value: dreamkg:service/6494806799548416 sdoh:availableChannel dreamkg:service/channel/AB-6494806799548416
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:availableChannel
    alias: sdoh_availableChannel
    owner: sdoh_Service
    domain_of:
    - sdoh_Service
    range: sdoh_ServiceChannel
  sdoh_provider:
    name: sdoh_provider
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_Service and object type sdoh_Organization.
    examples:
    - value: dreamkg:service/4785885511417856 sdoh:provider dreamkg:service/provider/4785885511417856
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:provider
    alias: sdoh_provider
    owner: sdoh_Service
    domain_of:
    - sdoh_Service
    range: sdoh_Organization
  sdoh_identifier:
    name: sdoh_identifier
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 39 occurrences with subject type sdoh_AdministrativeArea and object type string.
    - 87 occurrences with subject type sdoh_Service and object type string.
    examples:
    - value: dreamkg:zip/19120 sdoh:identifier 19120
    - value: dreamkg:service/5398794886447104 sdoh:identifier 5398794886447104
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:identifier
    alias: sdoh_identifier
    owner: sdoh_Service
    domain_of:
    - sdoh_AdministrativeArea
    - sdoh_Service
    range: string
  sdoh_category:
    name: sdoh_category
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 806 occurrences with subject type sdoh_Service and object type sdoh_CategoryCode.
    - 539 occurrences with subject type sdoh_Service and object type sdoh_Audience.
    examples:
    - value: dreamkg:service/5929367212130304 sdoh:category dreamkg:category/language/English
    - value: dreamkg:service/5390636500647936 sdoh:category dreamkg:category/audience/Children
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:category
    alias: sdoh_category
    owner: sdoh_Service
    domain_of:
    - sdoh_Service
    range: Any
    any_of:
    - range: sdoh_CategoryCode
    - range: sdoh_Audience
  sdoh_areaServed:
    name: sdoh_areaServed
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_Service and object type string.
    examples:
    - value: 'dreamkg:service/4670495380209664 sdoh:areaServed This program covers
        residents of the following counties: Philadelphia County, PA.'
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:areaServed
    alias: sdoh_areaServed
    owner: sdoh_Service
    domain_of:
    - sdoh_Service
    range: string
class_uri: sdoh:Service

```
</details>