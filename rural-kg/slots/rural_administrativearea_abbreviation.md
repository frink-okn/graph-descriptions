

# Slot: rural_administrativearea_abbreviation


_No slot (predicate) description specified_





URI: [rural:administrativearea/abbreviation](http://sail.ua.edu/ruralkg/administrativearea/abbreviation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaState](../classes/RuralAdministrativeareaState.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_administrativearea_State → string | rural:administrativearea/State_AK | rural:administrativearea/abbreviation | AK |


## Comments

* 56 occurrences with subject type rural_administrativearea_State and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:administrativearea/abbreviation |
| native | rural-kg/:rural_administrativearea_abbreviation |




## LinkML Source

<details>
```yaml
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
domain_of:
- rural_administrativearea_State
range: string

```
</details>