

# Slot: rural_administrativearea_name


_TODO -- tell the world what this slot (predicate) describes._





URI: [rural:administrativearea/name](http://sail.ua.edu/ruralkg/administrativearea/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaState](../classes/RuralAdministrativeareaState.md) | TODO -- tell the world what this class (type) describes |  no  |
| [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md) | TODO -- tell the world what this class (type) describes |  no  |
| [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| rural:administrativearea/City_1840017624 rural:administrativearea/name El Granada |
| rural:administrativearea/County_37133 rural:administrativearea/name Onslow |
| rural:administrativearea/State_AR rural:administrativearea/name Arkansas |

## Comments

* 31120 occurrences with subject type rural_administrativearea_City and object type string.
* 3253 occurrences with subject type rural_administrativearea_County and object type string.
* 56 occurrences with subject type rural_administrativearea_State and object type string.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:administrativearea/name |
| native | rural-kg/:rural_administrativearea_name |




## LinkML Source

<details>
```yaml
name: rural_administrativearea_name
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 31120 occurrences with subject type rural_administrativearea_City and object type
  string.
- 3253 occurrences with subject type rural_administrativearea_County and object type
  string.
- 56 occurrences with subject type rural_administrativearea_State and object type
  string.
examples:
- value: rural:administrativearea/City_1840017624 rural:administrativearea/name El
    Granada
- value: rural:administrativearea/County_37133 rural:administrativearea/name Onslow
- value: rural:administrativearea/State_AR rural:administrativearea/name Arkansas
from_schema: rural-kg
rank: 1000
slot_uri: rural:administrativearea/name
alias: rural_administrativearea_name
domain_of:
- rural_administrativearea_City
- rural_administrativearea_County
- rural_administrativearea_State
range: string

```
</details>