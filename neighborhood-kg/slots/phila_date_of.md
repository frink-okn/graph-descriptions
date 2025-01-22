

# Slot: phila_date_of


_No slot (predicate) description specified_





URI: [phila:date_of](https://metadata.phila.gov/date_of)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [PhilaIncident](../classes/PhilaIncident.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:date](xsd:date)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| phila_Incident → date | phila:OBJ_11856539 | phila:date_of | 2022-12-21 |


## Comments

* 15328 occurrences with subject type phila_Incident and object type date.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-information-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:date_of |
| native | neighborhood-information-kg/:phila_date_of |




## LinkML Source

<details>
```yaml
name: phila_date_of
description: No slot (predicate) description specified
comments:
- 15328 occurrences with subject type phila_Incident and object type date.
examples:
- description: phila_Incident → date
  object:
    example_object: '2022-12-21'
    example_object_type: date
    example_predicate: phila:date_of
    example_subject: phila:OBJ_11856539
    example_subject_type: phila_Incident
from_schema: neighborhood-information-kg
rank: 1000
slot_uri: phila:date_of
alias: phila_date_of
domain_of:
- phila_Incident
range: date

```
</details>