

# Slot: phila_is_fatal


_No slot (predicate) description specified_





URI: [phila:is_fatal](https://metadata.phila.gov/is_fatal)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [PhilaIncident](../classes/PhilaIncident.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:boolean](xsd:boolean)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| phila_Incident → boolean | phila:OBJ_11856539 | phila:is_fatal | false |


## Comments

* 15205 occurrences with subject type phila_Incident and object type boolean.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-information-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:is_fatal |
| native | neighborhood-information-kg/:phila_is_fatal |




## LinkML Source

<details>
```yaml
name: phila_is_fatal
description: No slot (predicate) description specified
comments:
- 15205 occurrences with subject type phila_Incident and object type boolean.
examples:
- description: phila_Incident → boolean
  object:
    example_object: 'false'
    example_object_type: boolean
    example_predicate: phila:is_fatal
    example_subject: phila:OBJ_11856539
    example_subject_type: phila_Incident
from_schema: neighborhood-information-kg
rank: 1000
slot_uri: phila:is_fatal
alias: phila_is_fatal
domain_of:
- phila_Incident
range: boolean

```
</details>