

# Slot: niem50_JurisdictionText


_No slot (predicate) description specified_






This slot occurs 3926555 times.


URI: [niem50:JurisdictionText](http://release.niem.gov/niem/niem-core/5.0/JurisdictionText)



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
| scales_CivilCase | string | scales:/CivilCase/akd;;1:16-cv-00001 | U.S. Government Defendant | 1795338 |
| scales_CriminalCase | string | scales:/CriminalCase/txed;;4:17-cr-00092 | Ct. 1s | 2131217 |




## LinkML Source

<details>

```yaml
name: niem50_JurisdictionText
annotations:
  count:
    tag: count
    value: 3926555
description: No slot (predicate) description specified
examples:
- object:
    example_object: U.S. Government Defendant
    example_object_type: string
    example_predicate: niem50:JurisdictionText
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: Ct. 1s
    example_object_type: string
    example_predicate: niem50:JurisdictionText
    example_subject: scales:/CriminalCase/txed;;4:17-cr-00092
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: niem50:JurisdictionText
alias: niem50_JurisdictionText
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: string

```
</details>