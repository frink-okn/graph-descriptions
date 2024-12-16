

# Slot: rural_administrativearea_fips


_No slot (predicate) description specified_





URI: [rural:administrativearea/fips](http://sail.ua.edu/ruralkg/administrativearea/fips)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaState](../classes/RuralAdministrativeareaState.md) | No class (type) description specified |  no  |
| [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_administrativearea_County → string | rural:administrativearea/County_01001 | rural:administrativearea/fips | 01001 |
| rural_administrativearea_State → string | rural:administrativearea/State_AK | rural:administrativearea/fips | 02 |


## Comments

* 3253 occurrences with subject type rural_administrativearea_County and object type string.
* 56 occurrences with subject type rural_administrativearea_State and object type string.

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
description: No slot (predicate) description specified
comments:
- 3253 occurrences with subject type rural_administrativearea_County and object type
  string.
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
domain_of:
- rural_administrativearea_County
- rural_administrativearea_State
range: string

```
</details>