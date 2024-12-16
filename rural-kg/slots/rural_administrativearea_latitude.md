

# Slot: rural_administrativearea_latitude


_No slot (predicate) description specified_





URI: [rural:administrativearea/latitude](http://sail.ua.edu/ruralkg/administrativearea/latitude)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:float](xsd:float)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_administrativearea_City → float | rural:administrativearea/City_1630023540 | rural:administrativearea/latitude | 18.2319 |


## Comments

* 31120 occurrences with subject type rural_administrativearea_City and object type float.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:administrativearea/latitude |
| native | rural-kg/:rural_administrativearea_latitude |




## LinkML Source

<details>
```yaml
name: rural_administrativearea_latitude
description: No slot (predicate) description specified
comments:
- 31120 occurrences with subject type rural_administrativearea_City and object type
  float.
examples:
- description: rural_administrativearea_City → float
  object:
    example_object: '18.2319'
    example_predicate: rural:administrativearea/latitude
    example_subject: rural:administrativearea/City_1630023540
from_schema: rural-kg
rank: 1000
slot_uri: rural:administrativearea/latitude
alias: rural_administrativearea_latitude
domain_of:
- rural_administrativearea_City
range: float

```
</details>