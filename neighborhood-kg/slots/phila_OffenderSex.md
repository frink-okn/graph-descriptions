

# Slot: phila_OffenderSex


_No slot (predicate) description specified_





URI: [phila:OffenderSex](https://metadata.phila.gov/OffenderSex)



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
| phila_Incident → string | phila:OBJ_11856539 | phila:OffenderSex | F |


## Comments

* 15328 occurrences with subject type phila_Incident and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-information-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:OffenderSex |
| native | neighborhood-information-kg/:phila_OffenderSex |




## LinkML Source

<details>
```yaml
name: phila_OffenderSex
description: No slot (predicate) description specified
comments:
- 15328 occurrences with subject type phila_Incident and object type string.
examples:
- description: phila_Incident → string
  object:
    example_object: F
    example_object_type: string
    example_predicate: phila:OffenderSex
    example_subject: phila:OBJ_11856539
    example_subject_type: phila_Incident
from_schema: neighborhood-information-kg
rank: 1000
slot_uri: phila:OffenderSex
alias: phila_OffenderSex
domain_of:
- phila_Incident
range: string

```
</details>