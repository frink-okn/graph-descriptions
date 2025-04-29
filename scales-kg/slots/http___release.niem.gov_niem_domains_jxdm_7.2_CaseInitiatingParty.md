

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty


_No slot (predicate) description specified_






This slot occurs 5633 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty](http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) |
| [ScalesCase](../classes/ScalesCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty | scales:/CaseCivil | scales:/Agent/casd;;3:16-cv-01644_a0 | 5633 |
| scales_Case | http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty | scales:/CaseCivil | scales:/Agent/casd;;3:16-cv-01644_a0 | 5633 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
annotations:
  count:
    tag: count
    value: 5633
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Agent/casd;;3:16-cv-01644_a0
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:/Agent/casd;;3:16-cv-01644_a0
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseInitiatingParty
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty

```
</details>