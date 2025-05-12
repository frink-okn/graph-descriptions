

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty


_No slot (predicate) description specified_






This slot occurs 8389 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty](http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |
| [ScalesCase](../classes/ScalesCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | scales:/CaseCivil | scales:/Agent/casd;;3:16-cv-01644_a1 | 8389 |
| scales_Case | http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | scales:/CaseCivil | scales:/Agent/casd;;3:16-cv-01644_a1 | 8389 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
annotations:
  count:
    tag: count
    value: 8389
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Agent/casd;;3:16-cv-01644_a1
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:/Agent/casd;;3:16-cv-01644_a1
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseDefendantParty
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty

```
</details>