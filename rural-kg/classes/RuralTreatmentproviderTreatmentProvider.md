

# Class: Treatment Provider (rural_treatmentprovider_TreatmentProvider)


_Entities that provide treatment services, sourcing from National Directory Of Mental Health Treatment Facilities._





URI: [rural:treatmentprovider/TreatmentProvider](http://sail.ua.edu/ruralkg/treatmentprovider/TreatmentProvider)






```mermaid
 classDiagram
    class RuralTreatmentproviderTreatmentProvider
    click RuralTreatmentproviderTreatmentProvider href "../RuralTreatmentproviderTreatmentProvider"
      RuralTreatmentproviderTreatmentProvider : rural_treatmentprovider_address
        
          
    
    
    RuralTreatmentproviderTreatmentProvider --> "0..1" String : rural_treatmentprovider_address
    click String href "../String"

        
      RuralTreatmentproviderTreatmentProvider : rural_treatmentprovider_alias
        
          
    
    
    RuralTreatmentproviderTreatmentProvider --> "0..1" String : rural_treatmentprovider_alias
    click String href "../String"

        
      RuralTreatmentproviderTreatmentProvider : rural_treatmentprovider_inCity
        
          
    
    
    RuralTreatmentproviderTreatmentProvider --> "0..1" Any : rural_treatmentprovider_inCity
    click Any href "../Any"

        
      RuralTreatmentproviderTreatmentProvider : rural_treatmentprovider_name
        
          
    
    
    RuralTreatmentproviderTreatmentProvider --> "0..1" String : rural_treatmentprovider_name
    click String href "../String"

        
      RuralTreatmentproviderTreatmentProvider : rural_treatmentprovider_phone
        
          
    
    
    RuralTreatmentproviderTreatmentProvider --> "0..1" String : rural_treatmentprovider_phone
    click String href "../String"

        
      RuralTreatmentproviderTreatmentProvider : rural_treatmentprovider_providesService
        
          
    
    
    RuralTreatmentproviderTreatmentProvider --> "0..1" RuralMentalhealthserviceMentalHealthService : rural_treatmentprovider_providesService
    click RuralMentalhealthserviceMentalHealthService href "../RuralMentalhealthserviceMentalHealthService"

        
      RuralTreatmentproviderTreatmentProvider : rural_treatmentprovider_zipcode
        
          
    
    
    RuralTreatmentproviderTreatmentProvider --> "0..1" String : rural_treatmentprovider_zipcode
    click String href "../String"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [rural_treatmentprovider_providesService](../slots/rural_treatmentprovider_providesService.md) | 0..1 <br/> [RuralMentalhealthserviceMentalHealthService](../classes/RuralMentalhealthserviceMentalHealthService.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_treatmentprovider_inCity](../slots/rural_treatmentprovider_inCity.md) | 0..1 <br/> [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_treatmentprovider_name](../slots/rural_treatmentprovider_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_treatmentprovider_alias](../slots/rural_treatmentprovider_alias.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_treatmentprovider_address](../slots/rural_treatmentprovider_address.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_treatmentprovider_phone](../slots/rural_treatmentprovider_phone.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_treatmentprovider_zipcode](../slots/rural_treatmentprovider_zipcode.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |










## Examples

| Value |
| --- |
| rural:treatmentprovider/TP_4956 |

## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:treatmentprovider/TreatmentProvider |
| native | rural-kg/:RuralTreatmentproviderTreatmentProvider |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: rural_treatmentprovider_TreatmentProvider
description: Entities that provide treatment services, sourcing from National Directory
  Of Mental Health Treatment Facilities.
title: Treatment Provider
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 9037 instances of this class.
examples:
- value: rural:treatmentprovider/TP_4956
from_schema: rural-kg
slots:
- rural_treatmentprovider_providesService
- rural_treatmentprovider_inCity
- rural_treatmentprovider_name
- rural_treatmentprovider_alias
- rural_treatmentprovider_address
- rural_treatmentprovider_phone
- rural_treatmentprovider_zipcode
class_uri: rural:treatmentprovider/TreatmentProvider

```
</details>

### Induced

<details>
```yaml
name: rural_treatmentprovider_TreatmentProvider
description: Entities that provide treatment services, sourcing from National Directory
  Of Mental Health Treatment Facilities.
title: Treatment Provider
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 9037 instances of this class.
examples:
- value: rural:treatmentprovider/TP_4956
from_schema: rural-kg
attributes:
  rural_treatmentprovider_providesService:
    name: rural_treatmentprovider_providesService
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 442841 occurrences with subject type rural_treatmentprovider_TreatmentProvider
      and object type rural_mentalhealthservice_MentalHealthService.
    examples:
    - value: rural:treatmentprovider/TP_2411 rural:treatmentprovider/providesService
        rural:mentalhealthservice/MHS_FPSY
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:treatmentprovider/providesService
    alias: rural_treatmentprovider_providesService
    owner: rural_treatmentprovider_TreatmentProvider
    domain_of:
    - rural_treatmentprovider_TreatmentProvider
    range: rural_mentalhealthservice_MentalHealthService
  rural_treatmentprovider_inCity:
    name: rural_treatmentprovider_inCity
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 8117 occurrences with subject type rural_treatmentprovider_TreatmentProvider
      and object type rural_administrativearea_City.
    - 920 occurrences with subject type rural_treatmentprovider_TreatmentProvider
      and object type uri.
    examples:
    - value: rural:treatmentprovider/TP_2390 rural:treatmentprovider/inCity rural:administrativearea/City_1840000494
    - value: rural:treatmentprovider/TP_1871 rural:treatmentprovider/inCity rural:administrativearea/City_None
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:treatmentprovider/inCity
    alias: rural_treatmentprovider_inCity
    owner: rural_treatmentprovider_TreatmentProvider
    domain_of:
    - rural_treatmentprovider_TreatmentProvider
    range: Any
    any_of:
    - range: rural_administrativearea_City
    - range: uri
  rural_treatmentprovider_name:
    name: rural_treatmentprovider_name
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider
      and object type string.
    examples:
    - value: rural:treatmentprovider/TP_4974 rural:treatmentprovider/name Greater
        Nashua Mental Health
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:treatmentprovider/name
    alias: rural_treatmentprovider_name
    owner: rural_treatmentprovider_TreatmentProvider
    domain_of:
    - rural_treatmentprovider_TreatmentProvider
    range: string
  rural_treatmentprovider_alias:
    name: rural_treatmentprovider_alias
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider
      and object type string.
    examples:
    - value: rural:treatmentprovider/TP_174 rural:treatmentprovider/alias NaN
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:treatmentprovider/alias
    alias: rural_treatmentprovider_alias
    owner: rural_treatmentprovider_TreatmentProvider
    domain_of:
    - rural_treatmentprovider_TreatmentProvider
    range: string
  rural_treatmentprovider_address:
    name: rural_treatmentprovider_address
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider
      and object type string.
    examples:
    - value: rural:treatmentprovider/TP_3251 rural:treatmentprovider/address 10425
        Plaza Americana Drive, NaN
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:treatmentprovider/address
    alias: rural_treatmentprovider_address
    owner: rural_treatmentprovider_TreatmentProvider
    domain_of:
    - rural_treatmentprovider_TreatmentProvider
    range: string
  rural_treatmentprovider_phone:
    name: rural_treatmentprovider_phone
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider
      and object type string.
    examples:
    - value: rural:treatmentprovider/TP_2685 rural:treatmentprovider/phone 574-533-1234
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:treatmentprovider/phone
    alias: rural_treatmentprovider_phone
    owner: rural_treatmentprovider_TreatmentProvider
    domain_of:
    - rural_treatmentprovider_TreatmentProvider
    range: string
  rural_treatmentprovider_zipcode:
    name: rural_treatmentprovider_zipcode
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 9037 occurrences with subject type rural_treatmentprovider_TreatmentProvider
      and object type string.
    examples:
    - value: rural:treatmentprovider/TP_4583 rural:treatmentprovider/zipcode 64108
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:treatmentprovider/zipcode
    alias: rural_treatmentprovider_zipcode
    owner: rural_treatmentprovider_TreatmentProvider
    domain_of:
    - rural_treatmentprovider_TreatmentProvider
    range: string
class_uri: rural:treatmentprovider/TreatmentProvider

```
</details>