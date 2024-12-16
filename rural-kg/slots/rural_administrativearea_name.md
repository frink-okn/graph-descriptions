

# Slot: rural_administrativearea_name


_No slot (predicate) description specified_





URI: [rural:administrativearea/name](http://sail.ua.edu/ruralkg/administrativearea/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaState](../classes/RuralAdministrativeareaState.md) | No class (type) description specified |  no  |
| [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md) | No class (type) description specified |  no  |
| [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_administrativearea_City → string | rural:administrativearea/City_1630023540 | rural:administrativearea/name | Caguas |
| rural_administrativearea_County → string | rural:administrativearea/County_01001 | rural:administrativearea/name | Autauga |
| rural_administrativearea_State → string | rural:administrativearea/State_AK | rural:administrativearea/name | Alaska |


## Comments

* 31120 occurrences with subject type rural_administrativearea_City and object type string.
* 3253 occurrences with subject type rural_administrativearea_County and object type string.
* 56 occurrences with subject type rural_administrativearea_State and object type string.

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
description: No slot (predicate) description specified
comments:
- 31120 occurrences with subject type rural_administrativearea_City and object type
  string.
- 3253 occurrences with subject type rural_administrativearea_County and object type
  string.
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
domain_of:
- rural_administrativearea_City
- rural_administrativearea_County
- rural_administrativearea_State
range: string

```
</details>