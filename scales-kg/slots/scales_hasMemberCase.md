

# Slot: scales_hasMemberCase


_No slot (predicate) description specified_





URI: [scales:hasMemberCase](http://schemas.scales-okn.org/rdf/scales#hasMemberCase)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [ScalesCase](../classes/ScalesCase.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| scales_Case → scales_Case | scales/CaseCriminal | scales:hasMemberCase | scales/CaseCivil |
| None → scales_Case | scales/CaseOther | scales:hasMemberCase | scales/CaseCivil |


## Comments

* 2 occurrences with subject type scales_Case and object type scales_Case.
* 1 occurrences with untyped subjects and object type scales_Case.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:hasMemberCase |
| native | scales-kg-new/:scales_hasMemberCase |




## LinkML Source

<details>

```yaml
name: scales_hasMemberCase
description: No slot (predicate) description specified
comments:
- 2 occurrences with subject type scales_Case and object type scales_Case.
- 1 occurrences with untyped subjects and object type scales_Case.
examples:
- description: scales_Case → scales_Case
  object:
    example_object: scales/CaseCivil
    example_object_type: scales_Case
    example_predicate: scales:hasMemberCase
    example_subject: scales/CaseCriminal
    example_subject_type: scales_Case
- description: None → scales_Case
  object:
    example_object: scales/CaseCivil
    example_object_type: scales_Case
    example_predicate: scales:hasMemberCase
    example_subject: scales/CaseOther
    example_subject_type: None
from_schema: scales-kg-new
rank: 1000
slot_uri: scales:hasMemberCase
alias: scales_hasMemberCase
domain_of:
- scales_Case
range: scales_Case

```
</details>