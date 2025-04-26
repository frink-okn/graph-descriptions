

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions


_No slot (predicate) description specified_






This slot occurs 5000 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions](http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) |
| [ScalesCase](../classes/ScalesCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction | scales:/CaseCivil | scales:/DocketTable/casd;;3:16-cv-01644 | 4999 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions | scales:/CaseCivil | scales:/DocketTable/casd;;3:16-cv-01644 | 5000 |
| scales_Case | http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction | scales:/CaseCivil | scales:/DocketTable/casd;;3:16-cv-01644 | 4999 |
| scales_Case | http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions | scales:/CaseCivil | scales:/DocketTable/casd;;3:16-cv-01644 | 5000 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
annotations:
  count:
    tag: count
    value: 5000
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/DocketTable/casd;;3:16-cv-01644
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:/DocketTable/casd;;3:16-cv-01644
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:/DocketTable/casd;;3:16-cv-01644
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
- object:
    example_object: scales:/DocketTable/casd;;3:16-cv-01644
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterOfActions
alias: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: Any
any_of:
- range: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
- range: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions

```
</details>