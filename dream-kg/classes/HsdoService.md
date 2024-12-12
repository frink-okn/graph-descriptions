

# Class: Service (hsdo_Service)


_A service provided by an organization, e.g. delivery service, print services, etc._





URI: [hsdo:Service](hsdo:Service)






```mermaid
 classDiagram
    class HsdoService
    click HsdoService href "../HsdoService"
      HsdoService : hsdo_areaServed
        
          
    
    
    HsdoService --> "0..1" String : hsdo_areaServed
    click String href "../String"

        
      HsdoService : hsdo_availableChannel
        
          
    
    
    HsdoService --> "0..1" HsdoServiceChannel : hsdo_availableChannel
    click HsdoServiceChannel href "../HsdoServiceChannel"

        
      HsdoService : hsdo_category
        
          
    
    
    HsdoService --> "0..1" Any : hsdo_category
    click Any href "../Any"

        
      HsdoService : hsdo_description
        
          
    
    
    HsdoService --> "0..1" HsdoTextObject : hsdo_description
    click HsdoTextObject href "../HsdoTextObject"

        
      HsdoService : hsdo_hoursAvailable
        
          
    
    
    HsdoService --> "0..1" HsdoOpeningHoursSpecification : hsdo_hoursAvailable
    click HsdoOpeningHoursSpecification href "../HsdoOpeningHoursSpecification"

        
      HsdoService : hsdo_identifier
        
          
    
    
    HsdoService --> "0..1" String : hsdo_identifier
    click String href "../String"

        
      HsdoService : hsdo_name
        
          
    
    
    HsdoService --> "0..1" String : hsdo_name
    click String href "../String"

        
      HsdoService : hsdo_provider
        
          
    
    
    HsdoService --> "0..1" HsdoOrganization : hsdo_provider
    click HsdoOrganization href "../HsdoOrganization"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [hsdo_category](../slots/hsdo_category.md) | 0..1 <br/> [HsdoCategoryCode](../classes/HsdoCategoryCode.md)&nbsp;or&nbsp;<br />[HsdoAudience](../classes/HsdoAudience.md) | No slot (predicate) description specified | direct |
| [hsdo_hoursAvailable](../slots/hsdo_hoursAvailable.md) | 0..1 <br/> [HsdoOpeningHoursSpecification](../classes/HsdoOpeningHoursSpecification.md) | No slot (predicate) description specified | direct |
| [hsdo_areaServed](../slots/hsdo_areaServed.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified | direct |
| [hsdo_provider](../slots/hsdo_provider.md) | 0..1 <br/> [HsdoOrganization](../classes/HsdoOrganization.md) | No slot (predicate) description specified | direct |
| [hsdo_description](../slots/hsdo_description.md) | 0..1 <br/> [HsdoTextObject](../classes/HsdoTextObject.md) | No slot (predicate) description specified | direct |
| [hsdo_identifier](../slots/hsdo_identifier.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified | direct |
| [hsdo_name](../slots/hsdo_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified | direct |
| [hsdo_availableChannel](../slots/hsdo_availableChannel.md) | 0..1 <br/> [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | No slot (predicate) description specified | direct |









## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:Service |
| native | dream-kg/:HsdoService |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: hsdo_Service
description: A service provided by an organization, e.g. delivery service, print services,
  etc.
title: Service
notes:
- Class with 87 occurrences.
from_schema: dream-kg
rank: 1000
slots:
- hsdo_category
- hsdo_hoursAvailable
- hsdo_areaServed
- hsdo_provider
- hsdo_description
- hsdo_identifier
- hsdo_name
- hsdo_availableChannel
class_uri: hsdo:Service

```
</details>

### Induced

<details>
```yaml
name: hsdo_Service
description: A service provided by an organization, e.g. delivery service, print services,
  etc.
title: Service
notes:
- Class with 87 occurrences.
from_schema: dream-kg
rank: 1000
attributes:
  hsdo_category:
    name: hsdo_category
    description: No slot (predicate) description specified
    comments:
    - 806 occurrences with subject type hsdo_Service and object type hsdo_CategoryCode.
    - 539 occurrences with subject type hsdo_Service and object type hsdo_Audience.
    examples:
    - description: hsdo_Service → hsdo_CategoryCode
      object:
        example_object: dreamkg:category/service/main/OneOnOneSupport
        example_predicate: hsdo:category
        example_subject: dreamkg:service/5181712996761600
    - description: hsdo_Service → hsdo_Audience
      object:
        example_object: dreamkg:category/audience/YoungAdults
        example_predicate: hsdo:category
        example_subject: dreamkg:service/6272068172382208
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:category
    alias: hsdo_category
    owner: hsdo_Service
    domain_of:
    - hsdo_Service
    range: Any
    any_of:
    - range: hsdo_CategoryCode
    - range: hsdo_Audience
  hsdo_hoursAvailable:
    name: hsdo_hoursAvailable
    description: No slot (predicate) description specified
    comments:
    - 609 occurrences with subject type hsdo_Service and object type hsdo_OpeningHoursSpecification.
    examples:
    - description: hsdo_Service → hsdo_OpeningHoursSpecification
      object:
        example_object: dreamkg:service/hours/monday/5348732074983424
        example_predicate: hsdo:hoursAvailable
        example_subject: dreamkg:service/5348732074983424
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:hoursAvailable
    alias: hsdo_hoursAvailable
    owner: hsdo_Service
    domain_of:
    - hsdo_Service
    range: hsdo_OpeningHoursSpecification
  hsdo_areaServed:
    name: hsdo_areaServed
    description: No slot (predicate) description specified
    comments:
    - 87 occurrences with subject type hsdo_Service and object type string.
    examples:
    - description: hsdo_Service → string
      object:
        example_object: 'This program covers residents of the following counties:
          Chester County, PA and Delaware County, PA.'
        example_predicate: hsdo:areaServed
        example_subject: dreamkg:service/5385341432496128
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:areaServed
    alias: hsdo_areaServed
    owner: hsdo_Service
    domain_of:
    - hsdo_Service
    range: string
  hsdo_provider:
    name: hsdo_provider
    description: No slot (predicate) description specified
    comments:
    - 87 occurrences with subject type hsdo_Service and object type hsdo_Organization.
    examples:
    - description: hsdo_Service → hsdo_Organization
      object:
        example_object: dreamkg:service/provider/6206753615380480
        example_predicate: hsdo:provider
        example_subject: dreamkg:service/6206753615380480
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:provider
    alias: hsdo_provider
    owner: hsdo_Service
    domain_of:
    - hsdo_Service
    range: hsdo_Organization
  hsdo_description:
    name: hsdo_description
    description: No slot (predicate) description specified
    comments:
    - 87 occurrences with subject type hsdo_Service and object type hsdo_TextObject.
    examples:
    - description: hsdo_Service → hsdo_TextObject
      object:
        example_object: dreamkg:service/desc/5128979153944576
        example_predicate: hsdo:description
        example_subject: dreamkg:service/5128979153944576
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:description
    alias: hsdo_description
    owner: hsdo_Service
    domain_of:
    - hsdo_Service
    range: hsdo_TextObject
  hsdo_identifier:
    name: hsdo_identifier
    description: No slot (predicate) description specified
    comments:
    - 87 occurrences with subject type hsdo_Service and object type string.
    - 39 occurrences with subject type hsdo_AdministrativeArea and object type string.
    examples:
    - description: hsdo_Service → string
      object:
        example_object: '5367371355914240'
        example_predicate: hsdo:identifier
        example_subject: dreamkg:service/5367371355914240
    - description: hsdo_AdministrativeArea → string
      object:
        example_object: '19320'
        example_predicate: hsdo:identifier
        example_subject: dreamkg:zip/19320
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:identifier
    alias: hsdo_identifier
    owner: hsdo_Service
    domain_of:
    - hsdo_AdministrativeArea
    - hsdo_Service
    range: string
  hsdo_name:
    name: hsdo_name
    description: No slot (predicate) description specified
    comments:
    - 88 occurrences with subject type hsdo_Service and object type string.
    - 89 occurrences with subject type hsdo_Organization and object type string.
    examples:
    - description: hsdo_Service → string
      object:
        example_object: Emergency Shelter
        example_predicate: hsdo:name
        example_subject: dreamkg:service/5398794886447104
    - description: hsdo_Organization → string
      object:
        example_object: Belmont Behavioral Health System
        example_predicate: hsdo:name
        example_subject: dreamkg:service/provider/4829363626049536
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:name
    alias: hsdo_name
    owner: hsdo_Service
    domain_of:
    - hsdo_Organization
    - hsdo_Service
    range: string
  hsdo_availableChannel:
    name: hsdo_availableChannel
    description: No slot (predicate) description specified
    comments:
    - 174 occurrences with subject type hsdo_Service and object type hsdo_ServiceChannel.
    examples:
    - description: hsdo_Service → hsdo_ServiceChannel
      object:
        example_object: dreamkg:service/channel/AB-5715375002484736
        example_predicate: hsdo:availableChannel
        example_subject: dreamkg:service/5715375002484736
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:availableChannel
    alias: hsdo_availableChannel
    owner: hsdo_Service
    domain_of:
    - hsdo_Service
    range: hsdo_ServiceChannel
class_uri: hsdo:Service

```
</details>