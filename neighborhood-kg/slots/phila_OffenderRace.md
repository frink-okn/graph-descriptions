

# Slot: phila_OffenderRace


_No slot (predicate) description specified_





URI: [phila:OffenderRace](https://metadata.phila.gov/OffenderRace)



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
| phila_Incident → string | phila:OBJ_11856539 | phila:OffenderRace | B |


## Comments

* 15205 occurrences with subject type phila_Incident and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-information-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:OffenderRace |
| native | neighborhood-information-kg/:phila_OffenderRace |




## LinkML Source

<details>
```yaml
name: phila_OffenderRace
description: No slot (predicate) description specified
comments:
- 15205 occurrences with subject type phila_Incident and object type string.
examples:
- description: phila_Incident → string
  object:
    example_object: B
    example_object_type: string
    example_predicate: phila:OffenderRace
    example_subject: phila:OBJ_11856539
    example_subject_type: phila_Incident
from_schema: neighborhood-information-kg
rank: 1000
slot_uri: phila:OffenderRace
alias: phila_OffenderRace
domain_of:
- phila_Incident
range: string

```
</details>