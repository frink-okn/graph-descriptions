

# Class: Place (sdoh_Place)


_Entities that have a somewhat fixed, physical extension._





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
| [sdoh_containedInPlace](../slots/sdoh_containedInPlace.md) | 0..1 <br/> [SdohAdministrativeArea](../classes/SdohAdministrativeArea.md) | The basic containment relation between a place and one that contains it | direct |
| [sdoh_latitude](../slots/sdoh_latitude.md) | 0..1 <br/> [xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal) | The latitude of a location | direct |
| [sdoh_hasMap](../slots/sdoh_hasMap.md) | 0..1 <br/> [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI) | A URL to a map of the place | direct |
| [sdoh_longitude](../slots/sdoh_longitude.md) | 0..1 <br/> [xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal) | The longitude of a location | direct |
| [sdoh_address](../slots/sdoh_address.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | Physical address of the item | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [SdohServiceChannel](../classes/SdohServiceChannel.md) | [sdoh_serviceLocation](../slots/sdoh_serviceLocation.md) | range | [SdohPlace](../classes/SdohPlace.md) |







## Examples

| Value |
| --- |
| dreamkg:service/location/5730442313465856 |

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
description: Entities that have a somewhat fixed, physical extension.
title: Place
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 87 instances of this class.
examples:
- value: dreamkg:service/location/5730442313465856
from_schema: dream-kg
slots:
- sdoh_containedInPlace
- sdoh_latitude
- sdoh_hasMap
- sdoh_longitude
- sdoh_address
class_uri: sdoh:Place

```
</details>

### Induced

<details>
```yaml
name: sdoh_Place
description: Entities that have a somewhat fixed, physical extension.
title: Place
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 87 instances of this class.
examples:
- value: dreamkg:service/location/5730442313465856
from_schema: dream-kg
attributes:
  sdoh_containedInPlace:
    name: sdoh_containedInPlace
    description: The basic containment relation between a place and one that contains
      it.
    title: containedInPlace
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 88 occurrences with subject type sdoh_Place and object type sdoh_AdministrativeArea.
    examples:
    - value: dreamkg:service/location/5922109384294400 sdoh:containedInPlace dreamkg:zip/19103
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
    description: The latitude of a location. For example ```37.42242``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System)).
    title: latitude
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 89 occurrences with subject type sdoh_Place and object type decimal.
    examples:
    - value: dreamkg:service/location/5175494499368960 sdoh:latitude 39.9879752
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:latitude
    alias: sdoh_latitude
    owner: sdoh_Place
    domain_of:
    - sdoh_Place
    range: decimal
  sdoh_hasMap:
    name: sdoh_hasMap
    description: A URL to a map of the place.
    title: hasMap
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 88 occurrences with subject type sdoh_Place and object type uri.
    examples:
    - value: dreamkg:service/location/6494806799548416 sdoh:hasMap https://www.google.com/maps/?q=900+West+Jefferson+Street,+Philadelphia,+PA+19122/
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
    description: The longitude of a location. For example ```-122.08585``` ([WGS 84](https://en.wikipedia.org/wiki/World_Geodetic_System)).
    title: longitude
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 89 occurrences with subject type sdoh_Place and object type decimal.
    examples:
    - value: dreamkg:service/location/5552002522939392 sdoh:longitude -75.1637779
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:longitude
    alias: sdoh_longitude
    owner: sdoh_Place
    domain_of:
    - sdoh_Place
    range: decimal
  sdoh_address:
    name: sdoh_address
    description: Physical address of the item.
    title: address
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 93 occurrences with subject type sdoh_Place and object type string.
    examples:
    - value: dreamkg:service/location/5518091445075968 sdoh:address 4943 North 5th
        Street, Philadelphia, PA 19120
    from_schema: dream-kg
    rank: 1000
    slot_uri: sdoh:address
    alias: sdoh_address
    owner: sdoh_Place
    domain_of:
    - sdoh_Place
    range: string
class_uri: sdoh:Place

```
</details>