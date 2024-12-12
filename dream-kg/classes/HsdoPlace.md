

# Class: Place (hsdo_Place)


_Entities that have a somewhat fixed, physical extension._





URI: [hsdo:Place](hsdo:Place)






```mermaid
 classDiagram
    class HsdoPlace
    click HsdoPlace href "../HsdoPlace"
      HsdoPlace : hsdo_address
        
          
    
    
    HsdoPlace --> "0..1" String : hsdo_address
    click String href "../String"

        
      HsdoPlace : hsdo_containedInPlace
        
          
    
    
    HsdoPlace --> "0..1" HsdoAdministrativeArea : hsdo_containedInPlace
    click HsdoAdministrativeArea href "../HsdoAdministrativeArea"

        
      HsdoPlace : hsdo_hasMap
        
          
    
    
    HsdoPlace --> "0..1" Uri : hsdo_hasMap
    click Uri href "../Uri"

        
      HsdoPlace : hsdo_latitude
        
          
    
    
    HsdoPlace --> "0..1" Decimal : hsdo_latitude
    click Decimal href "../Decimal"

        
      HsdoPlace : hsdo_longitude
        
          
    
    
    HsdoPlace --> "0..1" Decimal : hsdo_longitude
    click Decimal href "../Decimal"

        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [hsdo_longitude](../slots/hsdo_longitude.md) | 0..1 <br/> [xsd:decimal](xsd:decimal) | No slot (predicate) description specified | direct |
| [hsdo_address](../slots/hsdo_address.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified | direct |
| [hsdo_hasMap](../slots/hsdo_hasMap.md) | 0..1 <br/> [xsd:anyURI](xsd:anyURI) | No slot (predicate) description specified | direct |
| [hsdo_containedInPlace](../slots/hsdo_containedInPlace.md) | 0..1 <br/> [HsdoAdministrativeArea](../classes/HsdoAdministrativeArea.md) | No slot (predicate) description specified | direct |
| [hsdo_latitude](../slots/hsdo_latitude.md) | 0..1 <br/> [xsd:decimal](xsd:decimal) | No slot (predicate) description specified | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HsdoServiceChannel](../classes/HsdoServiceChannel.md) | [hsdo_serviceLocation](../slots/hsdo_serviceLocation.md) | range | [HsdoPlace](../classes/HsdoPlace.md) |







## Examples

| Value |
| --- |
| dreamkg:service/location/5355967947210752 |


## Identifier and Mapping Information







### Schema Source


* from schema: dream-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:Place |
| native | dream-kg/:HsdoPlace |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: hsdo_Place
description: Entities that have a somewhat fixed, physical extension.
title: Place
notes:
- Class with 87 occurrences.
examples:
- value: dreamkg:service/location/5355967947210752
from_schema: dream-kg
rank: 1000
slots:
- hsdo_longitude
- hsdo_address
- hsdo_hasMap
- hsdo_containedInPlace
- hsdo_latitude
class_uri: hsdo:Place

```
</details>

### Induced

<details>
```yaml
name: hsdo_Place
description: Entities that have a somewhat fixed, physical extension.
title: Place
notes:
- Class with 87 occurrences.
examples:
- value: dreamkg:service/location/5355967947210752
from_schema: dream-kg
rank: 1000
attributes:
  hsdo_longitude:
    name: hsdo_longitude
    description: No slot (predicate) description specified
    comments:
    - 89 occurrences with subject type hsdo_Place and object type decimal.
    examples:
    - description: hsdo_Place → decimal
      object:
        example_object: '-75.1619304'
        example_predicate: hsdo:longitude
        example_subject: dreamkg:service/location/6139716755783680
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:longitude
    alias: hsdo_longitude
    owner: hsdo_Place
    domain_of:
    - hsdo_Place
    range: decimal
  hsdo_address:
    name: hsdo_address
    description: No slot (predicate) description specified
    comments:
    - 93 occurrences with subject type hsdo_Place and object type string.
    examples:
    - description: hsdo_Place → string
      object:
        example_object: 2107 West Tioga Street, Philadelphia, PA 19140
        example_predicate: hsdo:address
        example_subject: dreamkg:service/location/5552002522939392
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:address
    alias: hsdo_address
    owner: hsdo_Place
    domain_of:
    - hsdo_Place
    range: string
  hsdo_hasMap:
    name: hsdo_hasMap
    description: No slot (predicate) description specified
    comments:
    - 88 occurrences with subject type hsdo_Place and object type uri.
    examples:
    - description: hsdo_Place → uri
      object:
        example_object: https://www.google.com/maps/?q=2212+Spruce+Street,+Philadelphia,+PA+19103/
        example_predicate: hsdo:hasMap
        example_subject: dreamkg:service/location/5997720409997312
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:hasMap
    alias: hsdo_hasMap
    owner: hsdo_Place
    domain_of:
    - hsdo_Place
    range: uri
  hsdo_containedInPlace:
    name: hsdo_containedInPlace
    description: No slot (predicate) description specified
    comments:
    - 88 occurrences with subject type hsdo_Place and object type hsdo_AdministrativeArea.
    examples:
    - description: hsdo_Place → hsdo_AdministrativeArea
      object:
        example_object: dreamkg:zip/19114
        example_predicate: hsdo:containedInPlace
        example_subject: dreamkg:service/location/6410727744077824
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:containedInPlace
    alias: hsdo_containedInPlace
    owner: hsdo_Place
    domain_of:
    - hsdo_Place
    range: hsdo_AdministrativeArea
  hsdo_latitude:
    name: hsdo_latitude
    description: No slot (predicate) description specified
    comments:
    - 89 occurrences with subject type hsdo_Place and object type decimal.
    examples:
    - description: hsdo_Place → decimal
      object:
        example_object: '40.0453383'
        example_predicate: hsdo:latitude
        example_subject: dreamkg:service/location/5017006984921088
    from_schema: dream-kg
    rank: 1000
    slot_uri: hsdo:latitude
    alias: hsdo_latitude
    owner: hsdo_Place
    domain_of:
    - hsdo_Place
    range: decimal
class_uri: hsdo:Place

```
</details>