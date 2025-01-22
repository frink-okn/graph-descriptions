

# Slot: phila_OffenderWound


_No slot (predicate) description specified_





URI: [phila:OffenderWound](https://metadata.phila.gov/OffenderWound)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [PhilaIncident](../classes/PhilaIncident.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| phila_Incident → string | phila:OBJ_11856539 | phila:OffenderWound | Multiple |


## Comments

* 15200 occurrences with subject type phila_Incident and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-information-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:OffenderWound |
| native | neighborhood-information-kg/:phila_OffenderWound |




## LinkML Source

<details>
```yaml
name: phila_OffenderWound
description: No slot (predicate) description specified
comments:
- 15200 occurrences with subject type phila_Incident and object type string.
examples:
- description: phila_Incident → string
  object:
    example_object: Multiple
    example_object_type: string
    example_predicate: phila:OffenderWound
    example_subject: phila:OBJ_11856539
    example_subject_type: phila_Incident
from_schema: neighborhood-information-kg
rank: 1000
slot_uri: phila:OffenderWound
alias: phila_OffenderWound
domain_of:
- phila_Incident
range: string

```
</details>