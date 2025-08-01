

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty


_No slot (predicate) description specified_






This slot occurs 6231746 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty](http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md)&nbsp;or&nbsp;<br />[ScalesParty](../classes/ScalesParty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | [http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSubject](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSubject.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | scales:/CivilCase/akd;;1:16-cv-00001 | scales:/Agent/akd;;1:16-cv-00001_a1 | 2398285 |
| scales_CriminalCase | http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | scales:/CriminalCase/akd;;1:16-cr-00001 | scales:/Agent/akd;;1:16-cr-00001_a0 | 406320 |
| scales_CivilCase | scales_Party | scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001 | scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a2 | 1271152 |
| scales_CriminalCase | scales_Party | scales:Case/ga-clayton-magistrate;;0:00-bc-00001 | scales:Agent/ga-clayton-magistrate;;0:00-bc-00001_a0 | 2155989 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
annotations:
  count:
    tag: count
    value: 6231746
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Agent/akd;;1:16-cv-00001_a1
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:/Agent/akd;;1:16-cr-00001_a0
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
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
- scales_CivilCase
- scales_CriminalCase
range: Any
any_of:
- range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- range: scales_Party

```
</details>