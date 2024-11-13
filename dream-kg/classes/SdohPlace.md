

# Class: TODO -- what's a good name for what this class (type) describes? (sdoh_Place)


_TODO -- tell the world what this class (type) describes._





URI: [sdoh:Place](http://schema.org/Place)






```mermaid
 classDiagram
    class SdohPlace
    click SdohPlace href "../SdohPlace"
      SdohPlace : sdoh_address
        
          
    
    
    SdohPlace --> "0..1" String : sdoh_address
    click String href "../String"

        
      SdohPlace : sdoh_containedInPlace
        
          
    
    
    SdohPlace --> "0..1" SdohAdministrativeArea : sdoh_containedInPlace
    click SdohAdministrativeArea href "../SdohAdministrativeArea"

        
      SdohPlace : sdoh_hasMap
        
          
    
    
    SdohPlace --> "0..1" Uri : sdoh_hasMap
    click Uri href "../Uri"

        
      SdohPlace : sdoh_latitude
        
          
    
    
    SdohPlace --> "0..1" Decimal : sdoh_latitude
    click Decimal href "../Decimal"

        
      SdohPlace : sdoh_longitude
        
          
    
    
    SdohPlace --> "0..1" Decimal : sdoh_longitude
    click Decimal href "../Decimal"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [sdoh_containedInPlace](../slots/sdoh_containedInPlace.md) | 0..1 <br/> [SdohAdministrativeArea](../classes/SdohAdministrativeArea.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_latitude](../slots/sdoh_latitude.md) | 0..1 <br/> [xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_address](../slots/sdoh_address.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_hasMap](../slots/sdoh_hasMap.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | TODO -- tell the world what this slot (predicate) describes | direct |
| [sdoh_longitude](../slots/sdoh_longitude.md) | 0..1 <br/> [xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohServiceChannel](../classes/SdohServiceChannel.md) | [sdoh_serviceLocation](../slots/sdoh_serviceLocation.md) | range | [SdohPlace](../classes/SdohPlace.md) |







## Examples

| Value |
| --- |
| dreamkg:service/location/5161629360586752 |

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
| self | sdoh:Place |
| native | dream-kg/:SdohPlace |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: sdoh_Place
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 87 instances of this class.
examples:
- value: dreamkg:service/location/5161629360586752
from_schema: dream-kg
slots:
- sdoh_containedInPlace
- sdoh_latitude
- sdoh_address
- sdoh_hasMap
- sdoh_longitude
class_uri: sdoh:Place

```
</details>

### Induced

<details>
```yaml
name: sdoh_Place
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 87 instances of this class.
examples:
- value: dreamkg:service/location/5161629360586752
from_schema: dream-kg
attributes:
  sdoh_containedInPlace:
    name: sdoh_containedInPlace
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 88 occurrences with subject type sdoh_Place and object type sdoh_AdministrativeArea.
    examples:
    - value: dreamkg:service/location/5112554392387584 sdoh:containedInPlace dreamkg:zip/19103
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:containedInPlace
    alias: sdoh_containedInPlace
    owner: sdoh_Place
    domain_of:
    - sdoh_Place
    range: sdoh_AdministrativeArea
  sdoh_latitude:
    name: sdoh_latitude
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 89 occurrences with subject type sdoh_Place and object type decimal.
    examples:
    - value: dreamkg:service/location/5367371355914240 sdoh:latitude 39.9479816
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:latitude
    alias: sdoh_latitude
    owner: sdoh_Place
    domain_of:
    - sdoh_Place
    range: decimal
  sdoh_address:
    name: sdoh_address
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 93 occurrences with subject type sdoh_Place and object type string.
    examples:
    - value: dreamkg:service/location/5929367212130304 sdoh:address 5501 Market Street,
        Philadelphia, PA 19139
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:address
    alias: sdoh_address
    owner: sdoh_Place
    domain_of:
    - sdoh_Place
    range: string
  sdoh_hasMap:
    name: sdoh_hasMap
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 88 occurrences with subject type sdoh_Place and object type uri.
    examples:
    - value: dreamkg:service/location/5348732074983424 sdoh:hasMap https://www.google.com/maps/?q=4301+Rising+Sun+Avenue,+Philadelphia,+PA+19140/
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:hasMap
    alias: sdoh_hasMap
    owner: sdoh_Place
    domain_of:
    - sdoh_Place
    range: uri
  sdoh_longitude:
    name: sdoh_longitude
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 89 occurrences with subject type sdoh_Place and object type decimal.
    examples:
    - value: dreamkg:service/location/5367371355914240 sdoh:longitude -75.2001349
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:longitude
    alias: sdoh_longitude
    owner: sdoh_Place
    domain_of:
    - sdoh_Place
    range: decimal
class_uri: sdoh:Place

```
</details>