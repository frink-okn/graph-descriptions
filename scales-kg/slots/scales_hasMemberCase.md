

# Slot: scales_hasMemberCase


_No slot (predicate) description specified_






This slot occurs 3 times.


URI: [scales:hasMemberCase](http://schemas.scales-okn.org/rdf/scales#hasMemberCase)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ScalesCase](../classes/ScalesCase.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_Case | scales_Case | scales:CivilCase | scales:CivilCase | 2 |
| scales_Case | http___release.niem.gov_niem_domains_jxdm_7.2_Case | scales:CivilCase | scales:CivilCase | 2 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | scales_Case | scales:CivilCase | scales:CivilCase | 2 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | http___release.niem.gov_niem_domains_jxdm_7.2_Case | scales:CivilCase | scales:CivilCase | 2 |
| None | scales_Case | scales:OtherCase | scales:CivilCase | 1 |
| None | http___release.niem.gov_niem_domains_jxdm_7.2_Case | scales:OtherCase | scales:CivilCase | 1 |




## LinkML Source

<details>

```yaml
name: scales_hasMemberCase
annotations:
  count:
    tag: count
    value: 3
  http___release.niem.gov_niem_domains_jxdm_7.2_Case:
    tag: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    value: 1
  scales_Case:
    tag: scales_Case
    value: 1
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:CivilCase
    example_object_type: scales_Case
    example_predicate: scales:hasMemberCase
    example_subject: scales:CivilCase
    example_subject_type: scales_Case
- object:
    example_object: scales:CivilCase
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    example_predicate: scales:hasMemberCase
    example_subject: scales:CivilCase
    example_subject_type: scales_Case
- object:
    example_object: scales:CivilCase
    example_object_type: scales_Case
    example_predicate: scales:hasMemberCase
    example_subject: scales:CivilCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:CivilCase
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    example_predicate: scales:hasMemberCase
    example_subject: scales:CivilCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:CivilCase
    example_object_type: scales_Case
    example_predicate: scales:hasMemberCase
    example_subject: scales:OtherCase
    example_subject_type: None
- object:
    example_object: scales:CivilCase
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    example_predicate: scales:hasMemberCase
    example_subject: scales:OtherCase
    example_subject_type: None
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasMemberCase
alias: scales_hasMemberCase
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: Any
any_of:
- range: scales_Case
- range: http___release.niem.gov_niem_domains_jxdm_7.2_Case

```
</details>