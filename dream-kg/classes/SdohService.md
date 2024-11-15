

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
| [sdoh_category](../slots/sdoh_category.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SdohAudience](../classes/SdohAudience.md)&nbsp;or&nbsp;<br />[SdohCategoryCode](../classes/SdohCategoryCode.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_hoursAvailable](../slots/sdoh_hoursAvailable.md) | 0..1 <br/> [SdohOpeningHoursSpecification](../classes/SdohOpeningHoursSpecification.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_availableChannel](../slots/sdoh_availableChannel.md) | 0..1 <br/> [SdohServiceChannel](../classes/SdohServiceChannel.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_description](../slots/sdoh_description.md) | 0..1 <br/> [SdohTextObject](../classes/SdohTextObject.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_provider](../slots/sdoh_provider.md) | 0..1 <br/> [SdohOrganization](../classes/SdohOrganization.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_name](../slots/sdoh_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_identifier](../slots/sdoh_identifier.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_areaServed](../slots/sdoh_areaServed.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |










## Examples

| Value |
| --- |
| dreamkg:service/5186727883833344 |

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
- There are 87 instances of this class.
examples:
- value: dreamkg:service/5186727883833344
from_schema: dream-kg
slots:
- sdoh_category
- sdoh_hoursAvailable
- sdoh_availableChannel
- sdoh_description
- sdoh_provider
- sdoh_name
- sdoh_identifier
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
- There are 87 instances of this class.
examples:
- value: dreamkg:service/5186727883833344
from_schema: dream-kg
attributes:
  sdoh_category:
    name: sdoh_category
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 539 occurrences with subject type sdoh_Service and object type sdoh_Audience.
    - 806 occurrences with subject type sdoh_Service and object type sdoh_CategoryCode.
    examples:
    - value: dreamkg:service/4780892498952192 sdoh:category dreamkg:category/audience/YoungAdults
    - value: dreamkg:service/4964759830003712 sdoh:category dreamkg:category/service/main/AddictionAndRecovery
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:category
    alias: sdoh_category
    owner: sdoh_Service
    domain_of:
    - sdoh_Service
    range: Any
    any_of:
    - range: sdoh_Audience
    - range: sdoh_CategoryCode
  sdoh_hoursAvailable:
    name: sdoh_hoursAvailable
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 609 occurrences with subject type sdoh_Service and object type sdoh_OpeningHoursSpecification.
    examples:
    - value: dreamkg:service/4955538569953280 sdoh:hoursAvailable dreamkg:service/hours/monday/4955538569953280
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:hoursAvailable
    alias: sdoh_hoursAvailable
    owner: sdoh_Service
    domain_of:
    - sdoh_Service
    range: sdoh_OpeningHoursSpecification
  sdoh_availableChannel:
    name: sdoh_availableChannel
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 174 occurrences with subject type sdoh_Service and object type sdoh_ServiceChannel.
    examples:
    - value: dreamkg:service/5161629360586752 sdoh:availableChannel dreamkg:service/channel/P-5161629360586752
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:availableChannel
    alias: sdoh_availableChannel
    owner: sdoh_Service
    domain_of:
    - sdoh_Service
    range: sdoh_ServiceChannel
  sdoh_description:
    name: sdoh_description
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_Service and object type sdoh_TextObject.
    examples:
    - value: dreamkg:service/5112554392387584 sdoh:description dreamkg:service/desc/5112554392387584
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:description
    alias: sdoh_description
    owner: sdoh_Service
    domain_of:
    - sdoh_Service
    range: sdoh_TextObject
  sdoh_provider:
    name: sdoh_provider
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_Service and object type sdoh_Organization.
    examples:
    - value: dreamkg:service/5128979153944576 sdoh:provider dreamkg:service/provider/5128979153944576
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:provider
    alias: sdoh_provider
    owner: sdoh_Service
    domain_of:
    - sdoh_Service
    range: sdoh_Organization
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
    - value: dreamkg:service/provider/4666716061171712 sdoh:name Horizon House
    - value: dreamkg:service/6410727744077824 sdoh:name Opioid Treatment Program
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:name
    alias: sdoh_name
    owner: sdoh_Service
    domain_of:
    - sdoh_Organization
    - sdoh_Service
    range: string
  sdoh_identifier:
    name: sdoh_identifier
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_Service and object type string.
    - 39 occurrences with subject type sdoh_AdministrativeArea and object type string.
    examples:
    - value: dreamkg:service/4955538569953280 sdoh:identifier 4955538569953280
    - value: dreamkg:zip/19134 sdoh:identifier 19134
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:identifier
    alias: sdoh_identifier
    owner: sdoh_Service
    domain_of:
    - sdoh_AdministrativeArea
    - sdoh_Service
    range: string
  sdoh_areaServed:
    name: sdoh_areaServed
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_Service and object type string.
    examples:
    - value: 'dreamkg:service/4785885511417856 sdoh:areaServed This program covers
        residents of the following cities: Philadelphia, PA.'
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