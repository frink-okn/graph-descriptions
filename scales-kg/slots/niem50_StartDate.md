

# Slot: niem50_StartDate


_No slot (predicate) description specified_






This slot occurs 4072490 times.


URI: [niem50:StartDate](http://release.niem.gov/niem/niem-core/5.0/StartDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | date | scales:/CivilCase/akd;;1:16-cv-00001 | 2016-01-04 | 1795343 |
| scales_CriminalCase | date | scales:/CriminalCase/akd;;1:16-cr-00001 | 2016-02-03 | 2277147 |




## LinkML Source

<details>

```yaml
name: niem50_StartDate
annotations:
  count:
    tag: count
    value: 4072490
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2016-01-04'
    example_object_type: date
    example_predicate: niem50:StartDate
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: '2016-02-03'
    example_object_type: date
    example_predicate: niem50:StartDate
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: niem50:StartDate
alias: niem50_StartDate
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: date

```
</details>