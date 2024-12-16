

# Slot: rural_administrativearea_containsPlace


_No slot (predicate) description specified_





URI: [rural:administrativearea/containsPlace](http://sail.ua.edu/ruralkg/administrativearea/containsPlace)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaState](../classes/RuralAdministrativeareaState.md) | No class (type) description specified |  no  |







## Properties

* Range: [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_administrativearea_State → rural_administrativearea_County | rural:administrativearea/State_WY | rural:administrativearea/containsPlace | rural:administrativearea/County_56045 |


## Comments

* 3253 occurrences with subject type rural_administrativearea_State and object type rural_administrativearea_County.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:administrativearea/containsPlace |
| native | rural-kg/:rural_administrativearea_containsPlace |




## LinkML Source

<details>
```yaml
name: rural_administrativearea_containsPlace
description: No slot (predicate) description specified
comments:
- 3253 occurrences with subject type rural_administrativearea_State and object type
  rural_administrativearea_County.
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
domain_of:
- rural_administrativearea_State
range: rural_administrativearea_County

```
</details>