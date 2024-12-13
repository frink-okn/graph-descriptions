

# Slot: rural_administrativearea_name


_No slot description provided_





URI: [rural:administrativearea/name](http://sail.ua.edu/ruralkg/administrativearea/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md) | City entities within a county or state |  no  |
| [RuralAdministrativeareaState](../classes/RuralAdministrativeareaState.md) | Represents individual states within U |  no  |
| [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) | Defines counties within a state |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None |  |  |  |
| None |  |  |  |
| None |  |  |  |


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
description: No slot description provided
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
- value: rural:administrativearea/City_1840007332 rural:administrativearea/name Greenwood
- value: rural:administrativearea/County_54083 rural:administrativearea/name Randolph
- value: rural:administrativearea/State_CO rural:administrativearea/name Colorado
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