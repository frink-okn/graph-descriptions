

# Slot: rural_administrativearea_longitude


_No slot description provided_





URI: [rural:administrativearea/longitude](http://sail.ua.edu/ruralkg/administrativearea/longitude)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md) | City entities within a county or state |  no  |







## Properties

* Range: [xsd:float](http://www.w3.org/2001/XMLSchema#float)






## Examples

| Value |
| --- |
| rural:administrativearea/City_1840006391 rural:administrativearea/longitude -77.3285 |

## Comments

* 31120 occurrences with subject type rural_administrativearea_City and object type float.

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
| self | rural:administrativearea/longitude |
| native | rural-kg/:rural_administrativearea_longitude |




## LinkML Source

<details>
```yaml
name: rural_administrativearea_longitude
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 31120 occurrences with subject type rural_administrativearea_City and object type
  float.
examples:
- value: rural:administrativearea/City_1840006391 rural:administrativearea/longitude
    -77.3285
from_schema: rural-kg
rank: 1000
slot_uri: rural:administrativearea/longitude
alias: rural_administrativearea_longitude
domain_of:
- rural_administrativearea_City
range: float

```
</details>