

# Slot: niem50_StartDate


_No slot (predicate) description specified_






This slot occurs 3217514 times.


URI: [niem50:StartDate](http://release.niem.gov/niem/niem-core/5.0/StartDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | date | scales:CivilCase | 2002-01-02 | 10519 |
| scales_CivilCase | date | scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001 | 2000-01-10 | 1075809 |
| scales_CriminalCase | date | scales:Case/ga-clayton-magistrate;;0:00-bc-00001 | 2000-01-05 | 2131186 |




## LinkML Source

<details>

```yaml
name: niem50_StartDate
annotations:
  count:
    tag: count
    value: 3217514
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2002-01-02'
    example_object_type: date
    example_predicate: niem50:StartDate
    example_subject: scales:CivilCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '2000-01-10'
    example_object_type: date
    example_predicate: niem50:StartDate
    example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: '2000-01-05'
    example_object_type: date
    example_predicate: niem50:StartDate
    example_subject: scales:Case/ga-clayton-magistrate;;0:00-bc-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: niem50:StartDate
alias: niem50_StartDate
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
- scales_CivilCase
- scales_CriminalCase
range: date

```
</details>