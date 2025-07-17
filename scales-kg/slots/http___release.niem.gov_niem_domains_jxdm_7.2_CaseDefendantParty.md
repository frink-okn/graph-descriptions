

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty


_No slot (predicate) description specified_






This slot occurs 6012142 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty](http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md)&nbsp;or&nbsp;<br />[ScalesParty](../classes/ScalesParty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |
| [ScalesCase](../classes/ScalesCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_Case | http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | scales:CivilCase | scales:Agent/akd;;1:16-cv-00001_a1 | 2586246 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | scales:CivilCase | scales:Agent/akd;;1:16-cv-00001_a1 | 2586246 |
| scales_CivilCase | scales_Party | scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001 | scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a2 | 1269907 |
| scales_CriminalCase | scales_Party | scales:Case/ga-clayton-magistrate;;0:00-bc-00001 | scales:Agent/ga-clayton-magistrate;;0:00-bc-00001_a0 | 2155989 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
annotations:
  count:
    tag: count
    value: 6012142
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Agent/akd;;1:16-cv-00001_a1
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
    example_subject: scales:CivilCase
    example_subject_type: scales_Case
- object:
    example_object: scales:Agent/akd;;1:16-cv-00001_a1
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
    example_subject: scales:CivilCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a2
    example_object_type: scales_Party
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
    example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:Agent/ga-clayton-magistrate;;0:00-bc-00001_a0
    example_object_type: scales_Party
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
    example_subject: scales:Case/ga-clayton-magistrate;;0:00-bc-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- range: scales_Party

```
</details>