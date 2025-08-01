

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt


_No slot (predicate) description specified_






This slot occurs 4072490 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt](http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2Court](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Court.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | http___release.niem.gov_niem_domains_jxdm_7.2_Court | scales:/CivilCase/akd;;1:16-cv-00001 | scales:/Court/akd | 718739 |
| scales_CriminalCase | http___release.niem.gov_niem_domains_jxdm_7.2_Court | scales:/CriminalCase/akd;;1:16-cr-00001 | scales:/Court/akd | 145961 |
| scales_CivilCase | string | scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001 | ga-clayton-magistrate-civil | 1076604 |
| scales_CriminalCase | string | scales:Case/ga-clayton-magistrate;;0:00-bc-00001 | ga-clayton-magistrate | 2131186 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
annotations:
  count:
    tag: count
    value: 4072490
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Court/akd
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Court
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:/Court/akd
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Court
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
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
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: string
- range: http___release.niem.gov_niem_domains_jxdm_7.2_Court

```
</details>