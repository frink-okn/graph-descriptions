

# Class: TODO -- what's a good name for what this class (type) describes? (rural_administrativearea_State)


_Represents individual states within U.S._





URI: [rural:administrativearea/State](http://sail.ua.edu/ruralkg/administrativearea/State)






```mermaid
 classDiagram
    class RuralAdministrativeareaState
    click RuralAdministrativeareaState href "../RuralAdministrativeareaState"
      RuralAdministrativeareaAdministrativeArea <|-- RuralAdministrativeareaState
        click RuralAdministrativeareaAdministrativeArea href "../RuralAdministrativeareaAdministrativeArea"
      
      RuralAdministrativeareaState : rural_administrativearea_abbreviation
        
          
    
    
    RuralAdministrativeareaState --> "0..1" String : rural_administrativearea_abbreviation
    click String href "../String"

        
      RuralAdministrativeareaState : rural_administrativearea_containsPlace
        
          
    
    
    RuralAdministrativeareaState --> "0..1" RuralAdministrativeareaCounty : rural_administrativearea_containsPlace
    click RuralAdministrativeareaCounty href "../RuralAdministrativeareaCounty"

        
      RuralAdministrativeareaState : rural_administrativearea_fips
        
          
    
    
    RuralAdministrativeareaState --> "0..1" String : rural_administrativearea_fips
    click String href "../String"

        
      RuralAdministrativeareaState : rural_administrativearea_name
        
          
    
    
    RuralAdministrativeareaState --> "0..1" String : rural_administrativearea_name
    click String href "../String"

        
      
```





## Inheritance
* [RuralAdministrativeareaAdministrativeArea](../classes/RuralAdministrativeareaAdministrativeArea.md)
    * **RuralAdministrativeareaState**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [rural_administrativearea_containsPlace](../slots/rural_administrativearea_containsPlace.md) | 0..1 <br/> [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) | No slot description provided | direct |
| [rural_administrativearea_abbreviation](../slots/rural_administrativearea_abbreviation.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [rural_administrativearea_fips](../slots/rural_administrativearea_fips.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |
| [rural_administrativearea_name](../slots/rural_administrativearea_name.md) | 0..1 <br/> [xsd:string](http://www.w3.org/2001/XMLSchema#string) | No slot description provided | direct |










## Examples

| Value |
| --- |
| rural:administrativearea/State_MS |

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
| self | rural:administrativearea/State |
| native | rural-kg/:RuralAdministrativeareaState |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: rural_administrativearea_State
description: Represents individual states within U.S.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 56 instances of this class.
examples:
- value: rural:administrativearea/State_MS
from_schema: rural-kg
rank: 1000
is_a: rural_administrativearea_AdministrativeArea
slots:
- rural_administrativearea_containsPlace
- rural_administrativearea_abbreviation
- rural_administrativearea_fips
- rural_administrativearea_name
class_uri: rural:administrativearea/State

```
</details>

### Induced

<details>
```yaml
name: rural_administrativearea_State
description: Represents individual states within U.S.
title: TODO -- what's a good name for what this class (type) describes?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- There are 56 instances of this class.
examples:
- value: rural:administrativearea/State_MS
from_schema: rural-kg
rank: 1000
is_a: rural_administrativearea_AdministrativeArea
attributes:
  rural_administrativearea_containsPlace:
    name: rural_administrativearea_containsPlace
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3253 occurrences with subject type rural_administrativearea_State and object
      type rural_administrativearea_County.
    examples:
    - value: rural:administrativearea/State_TX rural:administrativearea/containsPlace
        rural:administrativearea/County_48021
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/containsPlace
    alias: rural_administrativearea_containsPlace
    owner: rural_administrativearea_State
    domain_of:
    - rural_administrativearea_State
    range: rural_administrativearea_County
  rural_administrativearea_abbreviation:
    name: rural_administrativearea_abbreviation
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 56 occurrences with subject type rural_administrativearea_State and object type
      string.
    examples:
    - value: rural:administrativearea/State_MN rural:administrativearea/abbreviation
        MN
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/abbreviation
    alias: rural_administrativearea_abbreviation
    owner: rural_administrativearea_State
    domain_of:
    - rural_administrativearea_State
    range: string
  rural_administrativearea_fips:
    name: rural_administrativearea_fips
    description: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 3253 occurrences with subject type rural_administrativearea_County and object
      type string.
    - 56 occurrences with subject type rural_administrativearea_State and object type
      string.
    examples:
    - value: rural:administrativearea/County_48409 rural:administrativearea/fips 48409
    - value: rural:administrativearea/State_UT rural:administrativearea/fips 49
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/fips
    alias: rural_administrativearea_fips
    owner: rural_administrativearea_State
    domain_of:
    - rural_administrativearea_County
    - rural_administrativearea_State
    range: string
  rural_administrativearea_name:
    name: rural_administrativearea_name
    description: No slot description provided
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
    owner: rural_administrativearea_State
    domain_of:
    - rural_administrativearea_City
    - rural_administrativearea_County
    - rural_administrativearea_State
    range: string
class_uri: rural:administrativearea/State

```
</details>