

# Slot: scales_DocketTable


_No slot (predicate) description specified_






This slot occurs 4160501 times.


URI: [scales:DocketTable](http://schemas.scales-okn.org/rdf/scales#DocketTable)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions | scales:/CivilCase/akd;;1:16-cv-00001 | scales:/DocketTable/akd;;1:16-cv-00001 | 1795338 |
| scales_CivilCase | http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction | scales:/CivilCase/akd;;1:16-cv-00001 | scales:/DocketTable/akd;;1:16-cv-00001 | 710901 |
| scales_CriminalCase | http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions | scales:/CriminalCase/akd;;1:16-cr-00001 | scales:/DocketTable/akd;;1:16-cr-00001 | 2365163 |
| scales_CriminalCase | http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction | scales:/CriminalCase/akd;;1:16-cr-00001 | scales:/DocketTable/akd;;1:16-cr-00001 | 145842 |




## LinkML Source

<details>

```yaml
name: scales_DocketTable
annotations:
  count:
    tag: count
    value: 4160501
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/DocketTable/akd;;1:16-cv-00001
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    example_predicate: scales:DocketTable
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:/DocketTable/akd;;1:16-cv-00001
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    example_predicate: scales:DocketTable
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:/DocketTable/akd;;1:16-cr-00001
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    example_predicate: scales:DocketTable
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
- object:
    example_object: scales:/DocketTable/akd;;1:16-cr-00001
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
    example_predicate: scales:DocketTable
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:DocketTable
alias: scales_DocketTable
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
- range: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction

```
</details>