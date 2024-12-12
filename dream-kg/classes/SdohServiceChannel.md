

# Class: ServiceChannel (sdoh_ServiceChannel)


_A means for accessing a service, e.g. a government office location, web site, or phone number._





URI: [sdoh:ServiceChannel](http://schema.org/ServiceChannel)






```mermaid
 classDiagram
    class SdohServiceChannel
    click SdohServiceChannel href "../SdohServiceChannel"
      SdohServiceChannel : sdoh_disambiguatingDescription
        
          
    
    
    SdohServiceChannel --> "0..1" String : sdoh_disambiguatingDescription
    click String href "../String"

        
      SdohServiceChannel : sdoh_serviceLocation
        
          
    
    
    SdohServiceChannel --> "0..1" SdohPlace : sdoh_serviceLocation
    click SdohPlace href "../SdohPlace"

        
      SdohServiceChannel : sdoh_servicePhone
        
          
    
    
    SdohServiceChannel --> "0..1" SdohContactPoint : sdoh_servicePhone
    click SdohContactPoint href "../SdohContactPoint"

        
      SdohServiceChannel : sdoh_serviceUrl
        
          
    
    
    SdohServiceChannel --> "0..1" Uri : sdoh_serviceUrl
    click Uri href "../Uri"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sdoh_disambiguatingDescription](../slots/sdoh_disambiguatingDescription.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot description provided | direct |
| [sdoh_serviceUrl](../slots/sdoh_serviceUrl.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) | No slot description provided | direct |
| [sdoh_servicePhone](../slots/sdoh_servicePhone.md) | 0..1 <br/> [SdohContactPoint](../classes/SdohContactPoint.md) | No slot description provided | direct |
| [sdoh_serviceLocation](../slots/sdoh_serviceLocation.md) | 0..1 <br/> [SdohPlace](../classes/SdohPlace.md) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohService](../classes/SdohService.md) | [sdoh_availableChannel](../slots/sdoh_availableChannel.md) | range | [SdohServiceChannel](../classes/SdohServiceChannel.md) |







## Examples

| Value |
| --- |
| dreamkg:service/channel/AB-5925873791401984 |

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
| self | sdoh:ServiceChannel |
| native | dream-kg/:SdohServiceChannel |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_ServiceChannel
description: A means for accessing a service, e.g. a government office location, web
  site, or phone number.
title: ServiceChannel
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 174 occurences.
examples:
- value: dreamkg:service/channel/AB-5925873791401984
from_schema: dream-kg
rank: 1000
slots:
- sdoh_disambiguatingDescription
- sdoh_serviceUrl
- sdoh_servicePhone
- sdoh_serviceLocation
class_uri: sdoh:ServiceChannel

```
</details>

### Induced

<details>
```yaml
name: sdoh_ServiceChannel
description: A means for accessing a service, e.g. a government office location, web
  site, or phone number.
title: ServiceChannel
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 174 occurences.
examples:
- value: dreamkg:service/channel/AB-5925873791401984
from_schema: dream-kg
rank: 1000
attributes:
  sdoh_disambiguatingDescription:
    name: sdoh_disambiguatingDescription
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 174 occurrences with subject type sdoh_ServiceChannel and object type string.
    examples:
    - value: dreamkg:service/channel/P-5147295688687616 sdoh:disambiguatingDescription
        Provider
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:disambiguatingDescription
    alias: sdoh_disambiguatingDescription
    owner: sdoh_ServiceChannel
    domain_of:
    - sdoh_ServiceChannel
    range: string
  sdoh_serviceUrl:
    name: sdoh_serviceUrl
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 188 occurrences with subject type sdoh_ServiceChannel and object type uri.
    examples:
    - value: dreamkg:service/channel/P-5390636500647936 sdoh:serviceUrl https://www.vccphilly.org/ccdc.php
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:serviceUrl
    alias: sdoh_serviceUrl
    owner: sdoh_ServiceChannel
    domain_of:
    - sdoh_ServiceChannel
    range: uri
  sdoh_servicePhone:
    name: sdoh_servicePhone
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_ServiceChannel and object type sdoh_ContactPoint.
    examples:
    - value: dreamkg:service/channel/P-5728648493531136 sdoh:servicePhone dreamkg:service/phone/5728648493531136
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:servicePhone
    alias: sdoh_servicePhone
    owner: sdoh_ServiceChannel
    domain_of:
    - sdoh_ServiceChannel
    range: sdoh_ContactPoint
  sdoh_serviceLocation:
    name: sdoh_serviceLocation
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_ServiceChannel and object type sdoh_Place.
    examples:
    - value: dreamkg:service/channel/P-5640139036164096 sdoh:serviceLocation dreamkg:service/location/5640139036164096
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:serviceLocation
    alias: sdoh_serviceLocation
    owner: sdoh_ServiceChannel
    domain_of:
    - sdoh_ServiceChannel
    range: sdoh_Place
class_uri: sdoh:ServiceChannel

```
</details>