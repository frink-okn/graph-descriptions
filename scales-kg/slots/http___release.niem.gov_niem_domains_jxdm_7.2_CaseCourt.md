

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt


_No slot (predicate) description specified_






This slot occurs 3207183 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt](http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2Court](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Court.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_Case | http___release.niem.gov_niem_domains_jxdm_7.2_Court | scales:CivilCase | scales:Court/akd | 188 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | http___release.niem.gov_niem_domains_jxdm_7.2_Court | scales:CivilCase | scales:Court/akd | 188 |
| scales_CivilCase | string | scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001 | ga-clayton-magistrate-civil | 1075809 |
| scales_CriminalCase | string | scales:Case/ga-clayton-magistrate;;0:00-bc-00001 | ga-clayton-magistrate | 2131186 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
annotations:
  count:
    tag: count
    value: 3207183
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Court/akd
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Court
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
    example_subject: scales:CivilCase
    example_subject_type: scales_Case
- object:
    example_object: scales:Court/akd
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Court
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
    example_subject: scales:CivilCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: ga-clayton-magistrate-civil
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
    example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: ga-clayton-magistrate
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
    example_subject: scales:Case/ga-clayton-magistrate;;0:00-bc-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: http___release.niem.gov_niem_domains_jxdm_7.2_Court
- range: string

```
</details>