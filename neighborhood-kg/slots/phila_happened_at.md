

# Slot: phila_happened_at


_No slot (predicate) description specified_





URI: [phila:happened_at](https://metadata.phila.gov/happened_at)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [PhilaIncident](../classes/PhilaIncident.md) | No class (type) description specified |  no  |







## Properties

* Range: [PhilaCensusTract](../classes/PhilaCensusTract.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| phila_Incident → phila_CensusTract | phila:OBJ_11871866 | phila:happened_at | phila:CT_28902 |


## Comments

* 15328 occurrences with subject type phila_Incident and object type phila_CensusTract.

## Identifier and Mapping Information







### Schema Source


* from schema: neighborhood-information-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | phila:happened_at |
| native | neighborhood-information-kg/:phila_happened_at |




## LinkML Source

<details>
```yaml
name: phila_happened_at
description: No slot (predicate) description specified
comments:
- 15328 occurrences with subject type phila_Incident and object type phila_CensusTract.
examples:
- description: phila_Incident → phila_CensusTract
  object:
    example_object: phila:CT_28902
    example_object_type: phila_CensusTract
    example_predicate: phila:happened_at
    example_subject: phila:OBJ_11871866
    example_subject_type: phila_Incident
from_schema: neighborhood-information-kg
rank: 1000
slot_uri: phila:happened_at
alias: phila_happened_at
domain_of:
- phila_Incident
range: phila_CensusTract

```
</details>