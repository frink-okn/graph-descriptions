

# Slot: niem50_CaseDocketID


_No slot (predicate) description specified_






This slot occurs 3673384 times.


URI: [niem50:CaseDocketID](http://release.niem.gov/niem/niem-core/5.0/CaseDocketID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CriminalCase | string | scales:Case/ga-fulton-01-00-CR-244366 | 00-CR-244366 | 2222787 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:CivilCase | 0:15-cv-04235 | 374788 |
| scales_CivilCase | string | scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001 | 2000CM00001 P | 1075809 |




## LinkML Source

<details>

```yaml
name: niem50_CaseDocketID
annotations:
  count:
    tag: count
    value: 3673384
description: No slot (predicate) description specified
examples:
- object:
    example_object: 00-CR-244366
    example_object_type: string
    example_predicate: niem50:CaseDocketID
    example_subject: scales:Case/ga-fulton-01-00-CR-244366
    example_subject_type: scales_CriminalCase
- object:
    example_object: 0:15-cv-04235
    example_object_type: string
    example_predicate: niem50:CaseDocketID
    example_subject: scales:CivilCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: 2000CM00001 P
    example_object_type: string
    example_predicate: niem50:CaseDocketID
    example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
    example_subject_type: scales_CivilCase
from_schema: scales-kg
rank: 1000
slot_uri: niem50:CaseDocketID
alias: niem50_CaseDocketID
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
- scales_CivilCase
- scales_CriminalCase
range: string

```
</details>