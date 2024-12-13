

# Slot: rural_administrativearea_fips


_No slot description provided_





URI: [rural:administrativearea/fips](http://sail.ua.edu/ruralkg/administrativearea/fips)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaState](../classes/RuralAdministrativeareaState.md) | Represents individual states within U |  no  |
| [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) | Defines counties within a state |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| None |  |  |  |
| None |  |  |  |


## Comments

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
| self | rural:administrativearea/fips |
| native | rural-kg/:rural_administrativearea_fips |




## LinkML Source

<details>
```yaml
name: rural_administrativearea_fips
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 3253 occurrences with subject type rural_administrativearea_County and object type
  string.
- 56 occurrences with subject type rural_administrativearea_State and object type
  string.
examples:
- value: rural:administrativearea/County_48409 rural:administrativearea/fips 48409
- value: rural:administrativearea/State_UT rural:administrativearea/fips 49
from_schema: rural-kg
rank: 1000
slot_uri: rural:administrativearea/fips
alias: rural_administrativearea_fips
domain_of:
- rural_administrativearea_County
- rural_administrativearea_State
range: string

```
</details>