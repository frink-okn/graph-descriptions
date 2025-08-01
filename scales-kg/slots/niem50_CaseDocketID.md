

# Slot: niem50_CaseDocketID


_No slot (predicate) description specified_






This slot occurs 4164091 times.


URI: [niem50:CaseDocketID](http://release.niem.gov/niem/niem-core/5.0/CaseDocketID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | string | scales:/CivilCase/akd;;1:16-cv-00001 | 1:16-cv-00001 | 1795343 |
| scales_CriminalCase | string | scales:/CriminalCase/akd;;1:16-cr-00001 | 1:16-cr-00001 | 2368748 |




## LinkML Source

<details>

```yaml
name: niem50_CaseDocketID
annotations:
  count:
    tag: count
    value: 4164091
description: No slot (predicate) description specified
examples:
- object:
    example_object: 1:16-cv-00001
    example_object_type: string
    example_predicate: niem50:CaseDocketID
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: 1:16-cr-00001
    example_object_type: string
    example_predicate: niem50:CaseDocketID
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: niem50:CaseDocketID
alias: niem50_CaseDocketID
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: string

```
</details>