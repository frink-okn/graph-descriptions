

# Slot: niem50_CaseSubCategoryText


_No slot (predicate) description specified_





URI: [niem50:CaseSubCategoryText](http://release.niem.gov/niem/niem-core/5.0/CaseSubCategoryText)



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
| scales_Case → string | scales/CaseCivil | niem50:CaseSubCategoryText | 110 Insurance |


## Comments

* 104 occurrences with subject type scales_Case and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg-new




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | niem50:CaseSubCategoryText |
| native | scales-kg-new/:niem50_CaseSubCategoryText |




## LinkML Source

<details>

```yaml
name: niem50_CaseSubCategoryText
description: No slot (predicate) description specified
comments:
- 104 occurrences with subject type scales_Case and object type string.
examples:
- description: scales_Case → string
  object:
    example_object: 110 Insurance
    example_object_type: string
    example_predicate: niem50:CaseSubCategoryText
    example_subject: scales/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg-new
rank: 1000
slot_uri: niem50:CaseSubCategoryText
alias: niem50_CaseSubCategoryText
domain_of:
- scales_Case
range: string

```
</details>