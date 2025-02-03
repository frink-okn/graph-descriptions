

# Class: ServiceChannel (hsdo_ServiceChannel)


_A means for accessing a service, e.g. a government office location, web site, or phone number._





URI: [hsdo:ServiceChannel](http://schema.org/ServiceChannel)






```mermaid
 classDiagram
    class HsdoServiceChannel
    click HsdoServiceChannel href "../HsdoServiceChannel"
      HsdoServiceChannel : hsdo_disambiguatingDescription
        
      HsdoServiceChannel : hsdo_serviceLocation
        
          
    
    
    HsdoServiceChannel --> "0..1" HsdoPlace : hsdo_serviceLocation
    click HsdoPlace href "../HsdoPlace"

        
      HsdoServiceChannel : hsdo_servicePhone
        
          
    
    
    HsdoServiceChannel --> "0..1" HsdoContactPoint : hsdo_servicePhone
    click HsdoContactPoint href "../HsdoContactPoint"

        
      HsdoServiceChannel : hsdo_serviceUrl
        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [hsdo_serviceLocation](hsdo_serviceLocation.md) | 0..1 <br/> [HsdoPlace](HsdoPlace.md) | No slot (predicate) description specified <br/> 87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_Place. | direct |
| [hsdo_disambiguatingDescription](hsdo_disambiguatingDescription.md) | 0..1 <br/> [String](String.md) | No slot (predicate) description specified <br/> 174 occurrences with subject type hsdo_ServiceChannel and object type string. | direct |
| [hsdo_serviceUrl](hsdo_serviceUrl.md) | 0..1 <br/> [Uri](Uri.md) | No slot (predicate) description specified <br/> 188 occurrences with subject type hsdo_ServiceChannel and object type uri. | direct |
| [hsdo_servicePhone](hsdo_servicePhone.md) | 0..1 <br/> [HsdoContactPoint](HsdoContactPoint.md) | No slot (predicate) description specified <br/> 87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_ContactPoint. | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HsdoService](HsdoService.md) | [hsdo_availableChannel](hsdo_availableChannel.md) | range | [HsdoServiceChannel](HsdoServiceChannel.md) |






## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:ServiceChannel |
| native | dream-kg/:HsdoServiceChannel |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: hsdo_ServiceChannel
conforms_to: No schema conformance document specified
description: A means for accessing a service, e.g. a government office location, web
  site, or phone number.
title: ServiceChannel
notes:
- Class with 174 occurrences.
from_schema: dream-kg
rank: 1000
slots:
- hsdo_serviceLocation
- hsdo_disambiguatingDescription
- hsdo_serviceUrl
- hsdo_servicePhone
class_uri: hsdo:ServiceChannel

```
</details>

### Induced

<details>
```yaml
name: hsdo_ServiceChannel
conforms_to: No schema conformance document specified
description: A means for accessing a service, e.g. a government office location, web
  site, or phone number.
title: ServiceChannel
notes:
- Class with 174 occurrences.
from_schema: dream-kg
rank: 1000
attributes:
  hsdo_serviceLocation:
    name: hsdo_serviceLocation
    description: No slot (predicate) description specified
    comments:
    - 87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_Place.
    examples:
    - description: hsdo_ServiceChannel → hsdo_Place
      object:
        example_object: dreamkg:service/location/6710596967858176
        example_object_type: hsdo_Place
        example_predicate: hsdo:serviceLocation
        example_subject: dreamkg:service/channel/P-6710596967858176
        example_subject_type: hsdo_ServiceChannel
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:serviceLocation
    alias: hsdo_serviceLocation
    owner: hsdo_ServiceChannel
    domain_of:
    - hsdo_ServiceChannel
    range: hsdo_Place
  hsdo_disambiguatingDescription:
    name: hsdo_disambiguatingDescription
    description: No slot (predicate) description specified
    comments:
    - 174 occurrences with subject type hsdo_ServiceChannel and object type string.
    examples:
    - description: hsdo_ServiceChannel → string
      object:
        example_object: Aunt Bertha
        example_object_type: string
        example_predicate: hsdo:disambiguatingDescription
        example_subject: dreamkg:service/channel/AB-4542572480692224
        example_subject_type: hsdo_ServiceChannel
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:disambiguatingDescription
    alias: hsdo_disambiguatingDescription
    owner: hsdo_ServiceChannel
    domain_of:
    - hsdo_ServiceChannel
    range: string
  hsdo_serviceUrl:
    name: hsdo_serviceUrl
    description: No slot (predicate) description specified
    comments:
    - 188 occurrences with subject type hsdo_ServiceChannel and object type uri.
    examples:
    - description: hsdo_ServiceChannel → uri
      object:
        example_object: https://www.auntbertha.com//child-guidance-resource-centers-%2528cgrc%2529--philadelphia-pa--drug-and-alcohol-services/4542572480692224?postal=19139
        example_object_type: uri
        example_predicate: hsdo:serviceUrl
        example_subject: dreamkg:service/channel/AB-4542572480692224
        example_subject_type: hsdo_ServiceChannel
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:serviceUrl
    alias: hsdo_serviceUrl
    owner: hsdo_ServiceChannel
    domain_of:
    - hsdo_ServiceChannel
    range: uri
  hsdo_servicePhone:
    name: hsdo_servicePhone
    description: No slot (predicate) description specified
    comments:
    - 87 occurrences with subject type hsdo_ServiceChannel and object type hsdo_ContactPoint.
    examples:
    - description: hsdo_ServiceChannel → hsdo_ContactPoint
      object:
        example_object: dreamkg:service/phone/6710596967858176
        example_object_type: hsdo_ContactPoint
        example_predicate: hsdo:servicePhone
        example_subject: dreamkg:service/channel/P-6710596967858176
        example_subject_type: hsdo_ServiceChannel
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:servicePhone
    alias: hsdo_servicePhone
    owner: hsdo_ServiceChannel
    domain_of:
    - hsdo_ServiceChannel
    range: hsdo_ContactPoint
class_uri: hsdo:ServiceChannel

```
</details>