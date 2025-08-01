

# Slot: niem50_CaseSubCategoryText


_No slot (predicate) description specified_






This slot occurs 1863523 times.


URI: [niem50:CaseSubCategoryText](http://release.niem.gov/niem/niem-core/5.0/CaseSubCategoryText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | string | scales:/CivilCase/akd;;1:16-cv-00001 | 510 Motions To Vacate Sentence | 1863523 |




## LinkML Source

<details>

```yaml
name: niem50_CaseSubCategoryText
annotations:
  count:
    tag: count
    value: 1863523
description: No slot (predicate) description specified
examples:
- object:
    example_object: 510 Motions To Vacate Sentence
    example_object_type: string
    example_predicate: niem50:CaseSubCategoryText
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
from_schema: scales-kg
rank: 1000
slot_uri: niem50:CaseSubCategoryText
alias: niem50_CaseSubCategoryText
domain_of:
- scales_CivilCase
range: string

```
</details>