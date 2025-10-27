

# Class: RuralAdministrativeareaState


_Represents individual states within U.S._






This class occurs 56 times.


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

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |
| [rural_administrativearea_abbreviation](../slots/rural_administrativearea_abbreviation.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 56 |
| [rural_administrativearea_fips](../slots/rural_administrativearea_fips.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 56 |
| [rural_administrativearea_containsPlace](../slots/rural_administrativearea_containsPlace.md) | 0..1 <br/> [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) |  <br/>  | direct | 3253 |
| [rural_administrativearea_name](../slots/rural_administrativearea_name.md) | 0..1 <br/> [xsd:string](xsd:string) |  <br/>  | direct | 56 |














## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: rural_administrativearea_State
description: Represents individual states within U.S.
from_schema: okns:rural-kg
rank: 1000
is_a: rural_administrativearea_AdministrativeArea
slots:
- rural_administrativearea_abbreviation
- rural_administrativearea_fips
- rural_administrativearea_containsPlace
- rural_administrativearea_name
class_uri: rural:administrativearea/State

```
</details>

### Induced

<details>

```yaml
name: rural_administrativearea_State
description: Represents individual states within U.S.
from_schema: okns:rural-kg
rank: 1000
is_a: rural_administrativearea_AdministrativeArea
attributes:
  rural_administrativearea_abbreviation:
    name: rural_administrativearea_abbreviation
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/abbreviation
    alias: rural_administrativearea_abbreviation
    owner: rural_administrativearea_State
    domain_of:
    - rural_administrativearea_State
    range: string
  rural_administrativearea_fips:
    name: rural_administrativearea_fips
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/fips
    alias: rural_administrativearea_fips
    owner: rural_administrativearea_State
    domain_of:
    - rural_administrativearea_County
    - rural_administrativearea_State
    range: string
  rural_administrativearea_containsPlace:
    name: rural_administrativearea_containsPlace
    from_schema: okns:rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/containsPlace
    alias: rural_administrativearea_containsPlace
    owner: rural_administrativearea_State
    domain_of:
    - rural_administrativearea_State
    range: rural_administrativearea_County
  rural_administrativearea_name:
    name: rural_administrativearea_name
    from_schema: okns:rural-kg
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