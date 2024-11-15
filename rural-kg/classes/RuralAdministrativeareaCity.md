

# Class: TODO -- what's a good name for what this class (type) describes? (rural_administrativearea_City)


_City entities within a county or state._





URI: [rural:administrativearea/City](http://sail.ua.edu/ruralkg/administrativearea/City)






```mermaid
 classDiagram
    class RuralAdministrativeareaCity
    click RuralAdministrativeareaCity href "../RuralAdministrativeareaCity"
      RuralAdministrativeareaAdministrativeArea <|-- RuralAdministrativeareaCity
        click RuralAdministrativeareaAdministrativeArea href "../RuralAdministrativeareaAdministrativeArea"
      
      RuralAdministrativeareaCity : rural_administrativearea_latitude
        
          
    
    
    RuralAdministrativeareaCity --> "0..1" Float : rural_administrativearea_latitude
    click Float href "../Float"

        
      RuralAdministrativeareaCity : rural_administrativearea_longitude
        
          
    
    
    RuralAdministrativeareaCity --> "0..1" Float : rural_administrativearea_longitude
    click Float href "../Float"

        
      RuralAdministrativeareaCity : rural_administrativearea_name
        
          
    
    
    RuralAdministrativeareaCity --> "0..1" String : rural_administrativearea_name
    click String href "../String"

        
      RuralAdministrativeareaCity : rural_administrativearea_primaryCounty
        
          
    
    
    RuralAdministrativeareaCity --> "0..1" RuralAdministrativeareaCounty : rural_administrativearea_primaryCounty
    click RuralAdministrativeareaCounty href "../RuralAdministrativeareaCounty"

        
      RuralAdministrativeareaCity : rural_administrativearea_ranking
        
          
    
    
    RuralAdministrativeareaCity --> "0..1" Integer : rural_administrativearea_ranking
    click Integer href "../Integer"

        
      
```





## Inheritance
* [RuralAdministrativeareaAdministrativeArea](../classes/RuralAdministrativeareaAdministrativeArea.md)
    * **RuralAdministrativeareaCity**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [rural_administrativearea_primaryCounty](../slots/rural_administrativearea_primaryCounty.md) | 0..1 <br/> [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_administrativearea_ranking](../slots/rural_administrativearea_ranking.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_administrativearea_longitude](../slots/rural_administrativearea_longitude.md) | 0..1 <br/> [xsd:float](http://www.w3.org/2001/XMLSchema#float) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_administrativearea_name](../slots/rural_administrativearea_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_administrativearea_latitude](../slots/rural_administrativearea_latitude.md) | 0..1 <br/> [xsd:float](http://www.w3.org/2001/XMLSchema#float) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [RuralTreatmentproviderTreatmentProvider](../classes/RuralTreatmentproviderTreatmentProvider.md) | [rural_treatmentprovider_inCity](../slots/rural_treatmentprovider_inCity.md) | any_of[range] | [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md) |







## Examples

| Value |
| --- |
| rural:administrativearea/City_1840011974 |

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
| self | rural:administrativearea/City |
| native | rural-kg/:RuralAdministrativeareaCity |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: rural_administrativearea_City
description: City entities within a county or state.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 31120 instances of this class.
examples:
- value: rural:administrativearea/City_1840011974
from_schema: rural-kg
is_a: rural_administrativearea_AdministrativeArea
slots:
- rural_administrativearea_primaryCounty
- rural_administrativearea_ranking
- rural_administrativearea_longitude
- rural_administrativearea_name
- rural_administrativearea_latitude
class_uri: rural:administrativearea/City

```
</details>

### Induced

<details>
```yaml
name: rural_administrativearea_City
description: City entities within a county or state.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 31120 instances of this class.
examples:
- value: rural:administrativearea/City_1840011974
from_schema: rural-kg
is_a: rural_administrativearea_AdministrativeArea
attributes:
  rural_administrativearea_primaryCounty:
    name: rural_administrativearea_primaryCounty
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 31120 occurrences with subject type rural_administrativearea_City and object
      type rural_administrativearea_County.
    examples:
    - value: rural:administrativearea/City_1840009099 rural:administrativearea/primaryCounty
        rural:administrativearea/County_19055
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/primaryCounty
    alias: rural_administrativearea_primaryCounty
    owner: rural_administrativearea_City
    domain_of:
    - rural_administrativearea_City
    range: rural_administrativearea_County
  rural_administrativearea_ranking:
    name: rural_administrativearea_ranking
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 31120 occurrences with subject type rural_administrativearea_City and object
      type integer.
    examples:
    - value: rural:administrativearea/City_1840007531 rural:administrativearea/ranking
        3
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/ranking
    alias: rural_administrativearea_ranking
    owner: rural_administrativearea_City
    domain_of:
    - rural_administrativearea_City
    range: integer
  rural_administrativearea_longitude:
    name: rural_administrativearea_longitude
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 31120 occurrences with subject type rural_administrativearea_City and object
      type float.
    examples:
    - value: rural:administrativearea/City_1840006391 rural:administrativearea/longitude
        -77.3285
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/longitude
    alias: rural_administrativearea_longitude
    owner: rural_administrativearea_City
    domain_of:
    - rural_administrativearea_City
    range: float
  rural_administrativearea_name:
    name: rural_administrativearea_name
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 31120 occurrences with subject type rural_administrativearea_City and object
      type string.
    - 3253 occurrences with subject type rural_administrativearea_County and object
      type string.
    - 56 occurrences with subject type rural_administrativearea_State and object type
      string.
    examples:
    - value: rural:administrativearea/City_1840007332 rural:administrativearea/name
        Greenwood
    - value: rural:administrativearea/County_54083 rural:administrativearea/name Randolph
    - value: rural:administrativearea/State_CO rural:administrativearea/name Colorado
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/name
    alias: rural_administrativearea_name
    owner: rural_administrativearea_City
    domain_of:
    - rural_administrativearea_City
    - rural_administrativearea_County
    - rural_administrativearea_State
    range: string
  rural_administrativearea_latitude:
    name: rural_administrativearea_latitude
    description: TODO -- tell the world what this slot (predicate) describes.
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 31120 occurrences with subject type rural_administrativearea_City and object
      type float.
    examples:
    - value: rural:administrativearea/City_1840034298 rural:administrativearea/latitude
        40.9497
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/latitude
    alias: rural_administrativearea_latitude
    owner: rural_administrativearea_City
    domain_of:
    - rural_administrativearea_City
    range: float
class_uri: rural:administrativearea/City

```
</details>