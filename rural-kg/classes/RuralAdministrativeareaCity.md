

# Class: TODO -- what's a good name for what this class (type) describes? (rural_administrativearea_City)


_TODO -- tell the world what this class (type) describes._





URI: [rural:administrativearea/City](http://sail.ua.edu/ruralkg/administrativearea/City)






```mermaid
 classDiagram
    class RuralAdministrativeareaCity
    click RuralAdministrativeareaCity href "../RuralAdministrativeareaCity"
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




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [rural_administrativearea_primaryCounty](../slots/rural_administrativearea_primaryCounty.md) | 0..1 <br/> [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_administrativearea_ranking](../slots/rural_administrativearea_ranking.md) | 0..1 <br/> [xsd:integer](http://www.w3.org/2001/XMLSchema#integer) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_administrativearea_longitude](../slots/rural_administrativearea_longitude.md) | 0..1 <br/> [xsd:float](http://www.w3.org/2001/XMLSchema#float) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_administrativearea_latitude](../slots/rural_administrativearea_latitude.md) | 0..1 <br/> [xsd:float](http://www.w3.org/2001/XMLSchema#float) | TODO -- tell the world what this slot (predicate) describes | direct |
| [rural_administrativearea_name](../slots/rural_administrativearea_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | TODO -- tell the world what this slot (predicate) describes | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [RuralTreatmentproviderTreatmentProvider](../classes/RuralTreatmentproviderTreatmentProvider.md) | [rural_treatmentprovider_inCity](../slots/rural_treatmentprovider_inCity.md) | any_of[range] | [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md) |







## Examples

| Value |
| --- |
| rural:administrativearea/City_1840153044 |

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
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 31120 instances of this class.
examples:
- value: rural:administrativearea/City_1840153044
from_schema: rural-kg
slots:
- rural_administrativearea_primaryCounty
- rural_administrativearea_ranking
- rural_administrativearea_longitude
- rural_administrativearea_latitude
- rural_administrativearea_name
class_uri: rural:administrativearea/City

```
</details>

### Induced

<details>
```yaml
name: rural_administrativearea_City
description: TODO -- tell the world what this class (type) describes.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 31120 instances of this class.
examples:
- value: rural:administrativearea/City_1840153044
from_schema: rural-kg
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
    - value: rural:administrativearea/City_1840007376 rural:administrativearea/primaryCounty
        rural:administrativearea/County_18105
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
    - value: rural:administrativearea/City_1840017024 rural:administrativearea/ranking
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
    - value: rural:administrativearea/City_1840019111 rural:administrativearea/longitude
        -117.3472
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/longitude
    alias: rural_administrativearea_longitude
    owner: rural_administrativearea_City
    domain_of:
    - rural_administrativearea_City
    range: float
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
    - value: rural:administrativearea/City_1840038822 rural:administrativearea/latitude
        40.249
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/latitude
    alias: rural_administrativearea_latitude
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
    - value: rural:administrativearea/City_1840017624 rural:administrativearea/name
        El Granada
    - value: rural:administrativearea/County_37133 rural:administrativearea/name Onslow
    - value: rural:administrativearea/State_AR rural:administrativearea/name Arkansas
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
class_uri: rural:administrativearea/City

```
</details>