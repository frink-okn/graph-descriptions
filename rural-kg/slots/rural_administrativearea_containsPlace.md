

# Slot: rural_administrativearea_containsPlace


_TODO -- tell the world what this slot (predicate) describes._





URI: [rural:administrativearea/containsPlace](http://sail.ua.edu/ruralkg/administrativearea/containsPlace)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaState](../classes/RuralAdministrativeareaState.md) | Represents individual states within U |  no  |







## Properties

* Range: [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md)






## Examples

| Value |
| --- |
| rural:administrativearea/State_TX rural:administrativearea/containsPlace rural:administrativearea/County_48021 |

## Comments

* 3253 occurrences with subject type rural_administrativearea_State and object type rural_administrativearea_County.

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
| self | rural:administrativearea/containsPlace |
| native | rural-kg/:rural_administrativearea_containsPlace |




## LinkML Source

<details>
```yaml
name: rural_administrativearea_containsPlace
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 3253 occurrences with subject type rural_administrativearea_State and object type
  rural_administrativearea_County.
examples:
- value: rural:administrativearea/State_TX rural:administrativearea/containsPlace
    rural:administrativearea/County_48021
from_schema: rural-kg
rank: 1000
slot_uri: rural:administrativearea/containsPlace
alias: rural_administrativearea_containsPlace
domain_of:
- rural_administrativearea_State
range: rural_administrativearea_County

```
</details>