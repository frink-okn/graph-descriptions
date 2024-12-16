

# Class: No class (type) name specified (rural_administrativearea_State)


_No class (type) description specified_





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
| [rural_administrativearea_abbreviation](../slots/rural_administrativearea_abbreviation.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 56 occurrences with subject type rural_administrativearea_State and object type string. | direct |
| [rural_administrativearea_containsPlace](../slots/rural_administrativearea_containsPlace.md) | 0..1 <br/> [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) | No slot (predicate) description specified <br/> 3253 occurrences with subject type rural_administrativearea_State and object type rural_administrativearea_County. | direct |
| [rural_administrativearea_fips](../slots/rural_administrativearea_fips.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 3253 occurrences with subject type rural_administrativearea_County and object type string.<br/>56 occurrences with subject type rural_administrativearea_State and object type string. | direct |
| [rural_administrativearea_name](../slots/rural_administrativearea_name.md) | 0..1 <br/> [xsd:string](xsd:string) | No slot (predicate) description specified <br/> 31120 occurrences with subject type rural_administrativearea_City and object type string.<br/>3253 occurrences with subject type rural_administrativearea_County and object type string.<br/>56 occurrences with subject type rural_administrativearea_State and object type string. | direct |









## Comments

* Represents individual states within U.S.

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
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 56 occurrences.
comments:
- Represents individual states within U.S.
from_schema: rural-kg
rank: 1000
is_a: rural_administrativearea_AdministrativeArea
slots:
- rural_administrativearea_abbreviation
- rural_administrativearea_containsPlace
- rural_administrativearea_fips
- rural_administrativearea_name
class_uri: rural:administrativearea/State

```
</details>

### Induced

<details>
```yaml
name: rural_administrativearea_State
conforms_to: No schema conformance document specified
description: No class (type) description specified
title: No class (type) name specified
notes:
- Class with 56 occurrences.
comments:
- Represents individual states within U.S.
from_schema: rural-kg
rank: 1000
is_a: rural_administrativearea_AdministrativeArea
attributes:
  rural_administrativearea_abbreviation:
    name: rural_administrativearea_abbreviation
    description: No slot (predicate) description specified
    comments:
    - 56 occurrences with subject type rural_administrativearea_State and object type
      string.
    examples:
    - description: rural_administrativearea_State → string
      object:
        example_object: AK
        example_predicate: rural:administrativearea/abbreviation
        example_subject: rural:administrativearea/State_AK
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/abbreviation
    alias: rural_administrativearea_abbreviation
    owner: rural_administrativearea_State
    domain_of:
    - rural_administrativearea_State
    range: string
  rural_administrativearea_containsPlace:
    name: rural_administrativearea_containsPlace
    description: No slot (predicate) description specified
    comments:
    - 3253 occurrences with subject type rural_administrativearea_State and object
      type rural_administrativearea_County.
    examples:
    - description: rural_administrativearea_State → rural_administrativearea_County
      object:
        example_object: rural:administrativearea/County_56045
        example_predicate: rural:administrativearea/containsPlace
        example_subject: rural:administrativearea/State_WY
    from_schema: rural-kg
    rank: 1000
    slot_uri: rural:administrativearea/containsPlace
    alias: rural_administrativearea_containsPlace
    owner: rural_administrativearea_State
    domain_of:
    - rural_administrativearea_State
    range: rural_administrativearea_County
  rural_administrativearea_fips:
    name: rural_administrativearea_fips
    description: No slot (predicate) description specified
    comments:
    - 3253 occurrences with subject type rural_administrativearea_County and object
      type string.
    - 56 occurrences with subject type rural_administrativearea_State and object type
      string.
    examples:
    - description: rural_administrativearea_County → string
      object:
        example_object: '01001'
        example_predicate: rural:administrativearea/fips
        example_subject: rural:administrativearea/County_01001
    - description: rural_administrativearea_State → string
      object:
        example_object: '02'
        example_predicate: rural:administrativearea/fips
        example_subject: rural:administrativearea/State_AK
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
    description: No slot (predicate) description specified
    comments:
    - 31120 occurrences with subject type rural_administrativearea_City and object
      type string.
    - 3253 occurrences with subject type rural_administrativearea_County and object
      type string.
    - 56 occurrences with subject type rural_administrativearea_State and object type
      string.
    examples:
    - description: rural_administrativearea_City → string
      object:
        example_object: Caguas
        example_predicate: rural:administrativearea/name
        example_subject: rural:administrativearea/City_1630023540
    - description: rural_administrativearea_County → string
      object:
        example_object: Autauga
        example_predicate: rural:administrativearea/name
        example_subject: rural:administrativearea/County_01001
    - description: rural_administrativearea_State → string
      object:
        example_object: Alaska
        example_predicate: rural:administrativearea/name
        example_subject: rural:administrativearea/State_AK
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