

# Slot: phila_age_of


_No slot (predicate) description specified_





URI: [phila:age_of](https://metadata.phila.gov/age_of)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [PhilaIncident](../classes/PhilaIncident.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:integer](xsd:integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| phila_Incident → integer | phila:OBJ_11856539 | phila:age_of | 64 |


## Comments

* 15093 occurrences with subject type phila_Incident and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-information-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:age_of |
| native | neighborhood-information-kg/:phila_age_of |




## LinkML Source

<details>
```yaml
name: phila_age_of
description: No slot (predicate) description specified
comments:
- 15093 occurrences with subject type phila_Incident and object type integer.
examples:
- description: phila_Incident → integer
  object:
    example_object: '64'
    example_object_type: integer
    example_predicate: phila:age_of
    example_subject: phila:OBJ_11856539
    example_subject_type: phila_Incident
from_schema: neighborhood-information-kg
rank: 1000
slot_uri: phila:age_of
alias: phila_age_of
domain_of:
- phila_Incident
range: integer

```
</details>