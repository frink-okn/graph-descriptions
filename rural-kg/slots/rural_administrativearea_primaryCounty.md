

# Slot: rural_administrativearea_primaryCounty


_No slot (predicate) description specified_





URI: [rural:administrativearea/primaryCounty](http://sail.ua.edu/ruralkg/administrativearea/primaryCounty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md) | No class (type) description specified |  no  |







## Properties

* Range: [RuralAdministrativeareaCounty](../classes/RuralAdministrativeareaCounty.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_administrativearea_City → rural_administrativearea_County | rural:administrativearea/City_1840153164 | rural:administrativearea/primaryCounty | rural:administrativearea/County_06083 |


## Comments

* 31120 occurrences with subject type rural_administrativearea_City and object type rural_administrativearea_County.

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
description: No slot (predicate) description specified
comments:
- 31120 occurrences with subject type rural_administrativearea_City and object type
  rural_administrativearea_County.
examples:
- description: rural_administrativearea_City → rural_administrativearea_County
  object:
    example_object: rural:administrativearea/County_06083
    example_predicate: rural:administrativearea/primaryCounty
    example_subject: rural:administrativearea/City_1840153164
from_schema: rural-kg
rank: 1000
slot_uri: rural:administrativearea/primaryCounty
alias: rural_administrativearea_primaryCounty
domain_of:
- rural_administrativearea_City
range: rural_administrativearea_County

```
</details>