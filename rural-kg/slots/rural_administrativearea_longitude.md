

# Slot: rural_administrativearea_longitude


_No slot (predicate) description specified_





URI: [rural:administrativearea/longitude](http://sail.ua.edu/ruralkg/administrativearea/longitude)



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
| rural_administrativearea_City → float | rural:administrativearea/City_1630023540 | rural:administrativearea/longitude | -66.0388 |


## Comments

* 31120 occurrences with subject type rural_administrativearea_City and object type float.

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
description: No slot (predicate) description specified
comments:
- 31120 occurrences with subject type rural_administrativearea_City and object type
  float.
examples:
- description: rural_administrativearea_City → float
  object:
    example_object: '-66.0388'
    example_predicate: rural:administrativearea/longitude
    example_subject: rural:administrativearea/City_1630023540
from_schema: rural-kg
rank: 1000
slot_uri: rural:administrativearea/longitude
alias: rural_administrativearea_longitude
domain_of:
- rural_administrativearea_City
range: float

```
</details>