

# Slot: rural_administrativearea_ranking


_No slot (predicate) description specified_





URI: [rural:administrativearea/ranking](http://sail.ua.edu/ruralkg/administrativearea/ranking)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [RuralAdministrativeareaCity](../classes/RuralAdministrativeareaCity.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:integer](xsd:integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| rural_administrativearea_City → integer | rural:administrativearea/City_1630023540 | rural:administrativearea/ranking | 2 |


## Comments

* 31120 occurrences with subject type rural_administrativearea_City and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: rural-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | rural:administrativearea/ranking |
| native | rural-kg/:rural_administrativearea_ranking |




## LinkML Source

<details>
```yaml
name: rural_administrativearea_ranking
description: No slot (predicate) description specified
comments:
- 31120 occurrences with subject type rural_administrativearea_City and object type
  integer.
examples:
- description: rural_administrativearea_City → integer
  object:
    example_object: '2'
    example_predicate: rural:administrativearea/ranking
    example_subject: rural:administrativearea/City_1630023540
from_schema: rural-kg
rank: 1000
slot_uri: rural:administrativearea/ranking
alias: rural_administrativearea_ranking
domain_of:
- rural_administrativearea_City
range: integer

```
</details>