

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty


_No slot (predicate) description specified_






This slot occurs 4892601 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty](http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md)&nbsp;or&nbsp;<br />[ScalesParty](../classes/ScalesParty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty | scales:/CivilCase/akd;;1:16-cv-00001 | scales:/Agent/akd;;1:16-cv-00001_a0 | 1191370 |
| scales_CriminalCase | http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty | scales:/CriminalCase/akd;;1:16-cr-00001 | scales:/Agent/akd;;1:16-cr-00001_a1 | 146490 |
| scales_CivilCase | scales_Party | scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001 | scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a0 | 1488332 |
| scales_CriminalCase | scales_Party | scales:Case/ga-clayton-magistrate;;0:00-co-00002 | scales:Agent/ga-clayton-magistrate;;0:00-co-00002_a0 | 2066409 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
annotations:
  count:
    tag: count
    value: 4892601
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Agent/akd;;1:16-cv-00001_a0
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:/Agent/akd;;1:16-cr-00001_a1
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
- object:
    example_object: scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a0
    example_object_type: scales_Party
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
    example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:Agent/ga-clayton-magistrate;;0:00-co-00002_a0
    example_object_type: scales_Party
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
    example_subject: scales:Case/ga-clayton-magistrate;;0:00-co-00002
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- range: scales_Party

```
</details>