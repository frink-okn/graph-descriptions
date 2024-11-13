

# Class: TODO -- what's a good name for what this class (type) describes? (sdoh_ServiceChannel)


_TODO -- tell the world what this class (type) describes._





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
| [sdoh_serviceLocation](../slots/sdoh_serviceLocation.md) | 0..1 <br/> [SdohPlace](../classes/SdohPlace.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_servicePhone](../slots/sdoh_servicePhone.md) | 0..1 <br/> [SdohContactPoint](../classes/SdohContactPoint.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_disambiguatingDescription](../slots/sdoh_disambiguatingDescription.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_serviceUrl](../slots/sdoh_serviceUrl.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohService](../classes/SdohService.md) | [sdoh_availableChannel](../slots/sdoh_availableChannel.md) | range | [SdohServiceChannel](../classes/SdohServiceChannel.md) |







## Examples

| Value |
| --- |
| dreamkg:service/channel/AB-4955538569953280 |

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
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 174 instances of this class.
examples:
- value: dreamkg:service/channel/AB-4955538569953280
from_schema: dream-kg
slots:
- sdoh_serviceLocation
- sdoh_servicePhone
- sdoh_disambiguatingDescription
- sdoh_serviceUrl
class_uri: sdoh:ServiceChannel

```
</details>

### Induced

<details>
```yaml
name: sdoh_ServiceChannel
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 174 instances of this class.
examples:
- value: dreamkg:service/channel/AB-4955538569953280
from_schema: dream-kg
attributes:
  sdoh_serviceLocation:
    name: sdoh_serviceLocation
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_ServiceChannel and object type sdoh_Place.
    examples:
    - value: dreamkg:service/channel/P-6566876511207424 sdoh:serviceLocation dreamkg:service/location/6566876511207424
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:serviceLocation
    alias: sdoh_serviceLocation
    owner: sdoh_ServiceChannel
    domain_of:
    - sdoh_ServiceChannel
    range: sdoh_Place
  sdoh_servicePhone:
    name: sdoh_servicePhone
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 87 occurrences with subject type sdoh_ServiceChannel and object type sdoh_ContactPoint.
    examples:
    - value: dreamkg:service/channel/P-6494806799548416 sdoh:servicePhone dreamkg:service/phone/6494806799548416
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:servicePhone
    alias: sdoh_servicePhone
    owner: sdoh_ServiceChannel
    domain_of:
    - sdoh_ServiceChannel
    range: sdoh_ContactPoint
  sdoh_disambiguatingDescription:
    name: sdoh_disambiguatingDescription
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 174 occurrences with subject type sdoh_ServiceChannel and object type string.
    examples:
    - value: dreamkg:service/channel/P-4895435468308480 sdoh:disambiguatingDescription
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
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 188 occurrences with subject type sdoh_ServiceChannel and object type uri.
    examples:
    - value: dreamkg:service/channel/P-4785885511417856 sdoh:serviceUrl https://www.bebashi.org/hunger-relief/
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:serviceUrl
    alias: sdoh_serviceUrl
    owner: sdoh_ServiceChannel
    domain_of:
    - sdoh_ServiceChannel
    range: uri
class_uri: sdoh:ServiceChannel

```
</details>