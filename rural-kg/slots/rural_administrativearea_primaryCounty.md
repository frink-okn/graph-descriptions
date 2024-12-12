

# Slot: rural_administrativearea_primaryCounty


_No slot description provided_





URI: [rural:administrativearea/primaryCounty](http://sail.ua.edu/ruralkg/administrativearea/primaryCounty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md) | City entities within a county or state |  no  |







## Properties

* Range: [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md)






## Examples

| Value |
| --- |
| rural:administrativearea/City_1840009099 rural:administrativearea/primaryCounty rural:administrativearea/County_19055 |

## Comments

* 31120 occurrences with subject type rural_administrativearea_City and object type rural_administrativearea_County.

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
| self | rural:administrativearea/primaryCounty |
| native | rural-kg/:rural_administrativearea_primaryCounty |




## LinkML Source

<details>
```yaml
name: rural_administrativearea_primaryCounty
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 31120 occurrences with subject type rural_administrativearea_City and object type
  rural_administrativearea_County.
examples:
- value: rural:administrativearea/City_1840009099 rural:administrativearea/primaryCounty
    rural:administrativearea/County_19055
from_schema: rural-kg
rank: 1000
slot_uri: rural:administrativearea/primaryCounty
alias: rural_administrativearea_primaryCounty
domain_of:
- rural_administrativearea_City
range: rural_administrativearea_County

```
</details>