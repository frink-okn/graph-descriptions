

# Slot: rural_administrativearea_fips


_TODO -- tell the world what this slot (predicate) describes._





URI: [rural:administrativearea/fips](http://sail.ua.edu/ruralkg/administrativearea/fips)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaState](../classes/RuralAdministrativeareaState.md) | TODO -- tell the world what this class (type) describes |  no  |
| [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| rural:administrativearea/County_20185 rural:administrativearea/fips 20185 |
| rural:administrativearea/State_OR rural:administrativearea/fips 41 |

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
description: TODO -- tell the world what this slot (predicate) describes.
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
- value: rural:administrativearea/County_20185 rural:administrativearea/fips 20185
- value: rural:administrativearea/State_OR rural:administrativearea/fips 41
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