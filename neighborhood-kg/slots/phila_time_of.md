

# Slot: phila_time_of


_No slot (predicate) description specified_





URI: [phila:time_of](https://metadata.phila.gov/time_of)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [PhilaIncident](../classes/PhilaIncident.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:time](xsd:time)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| phila_Incident → time | phila:OBJ_11856539 | phila:time_of | 00:13:00 |


## Comments

* 15205 occurrences with subject type phila_Incident and object type time.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-information-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:time_of |
| native | neighborhood-information-kg/:phila_time_of |




## LinkML Source

<details>
```yaml
name: phila_time_of
description: No slot (predicate) description specified
comments:
- 15205 occurrences with subject type phila_Incident and object type time.
examples:
- description: phila_Incident → time
  object:
    example_object: 00:13:00
    example_object_type: time
    example_predicate: phila:time_of
    example_subject: phila:OBJ_11856539
    example_subject_type: phila_Incident
from_schema: neighborhood-information-kg
rank: 1000
slot_uri: phila:time_of
alias: phila_time_of
domain_of:
- phila_Incident
range: time

```
</details>