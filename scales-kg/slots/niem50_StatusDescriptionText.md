

# Slot: niem50_StatusDescriptionText


_No slot (predicate) description specified_





URI: [niem50:StatusDescriptionText](http://release.niem.gov/niem/niem-core/5.0/StatusDescriptionText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| scales_Case → string | scales/CaseCivil | niem50:StatusDescriptionText | closed |


## Comments

* 4 occurrences with subject type scales_Case and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | niem50:StatusDescriptionText |
| native | scales-kg-new/:niem50_StatusDescriptionText |




## LinkML Source

<details>

```yaml
name: niem50_StatusDescriptionText
description: No slot (predicate) description specified
comments:
- 4 occurrences with subject type scales_Case and object type string.
examples:
- description: scales_Case → string
  object:
    example_object: closed
    example_object_type: string
    example_predicate: niem50:StatusDescriptionText
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:StatusDescriptionText
alias: niem50_StatusDescriptionText
domain_of:
- scales_Case
range: string

```
</details>