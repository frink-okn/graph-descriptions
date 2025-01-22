

# Slot: phila_OffenderInjured


_No slot (predicate) description specified_





URI: [phila:OffenderInjured](https://metadata.phila.gov/OffenderInjured)



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
| phila_Incident → boolean | phila:OBJ_11856539 | phila:OffenderInjured | false |


## Comments

* 15328 occurrences with subject type phila_Incident and object type boolean.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-information-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:OffenderInjured |
| native | neighborhood-information-kg/:phila_OffenderInjured |




## LinkML Source

<details>
```yaml
name: phila_OffenderInjured
description: No slot (predicate) description specified
comments:
- 15328 occurrences with subject type phila_Incident and object type boolean.
examples:
- description: phila_Incident → boolean
  object:
    example_object: 'false'
    example_object_type: boolean
    example_predicate: phila:OffenderInjured
    example_subject: phila:OBJ_11856539
    example_subject_type: phila_Incident
from_schema: neighborhood-information-kg
rank: 1000
slot_uri: phila:OffenderInjured
alias: phila_OffenderInjured
domain_of:
- phila_Incident
range: boolean

```
</details>