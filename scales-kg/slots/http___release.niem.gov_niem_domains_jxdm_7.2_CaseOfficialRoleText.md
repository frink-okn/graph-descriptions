

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseOfficialRoleText


_No slot (predicate) description specified_






This slot occurs 1713199 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseOfficialRoleText](http://release.niem.gov/niem/domains/jxdm/7.2/CaseOfficialRoleText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Attorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Attorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | string | scales:/Agent/akd;;1:16-cr-00001_a2 | Assigned Judge | 1216331 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney | string | scales:/Agent/akd;;1:16-cr-00001_a4 | Retained | 280534 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney | string | scales:/Agent/akd;;1:16-cr-00001_a5 | Assistant US Attorney | 204677 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Attorney | string | scales:/Agent/almd;;1:16-cr-00571_a20 | Retained | 11657 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseOfficialRoleText
annotations:
  count:
    tag: count
    value: 1713199
  string:
    tag: string
    value: 1216331
description: No slot (predicate) description specified
examples:
- object:
    example_object: Assigned Judge
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseOfficialRoleText
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a2
    example_subject_type: None
- object:
    example_object: Retained
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseOfficialRoleText
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a4
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- object:
    example_object: Assistant US Attorney
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseOfficialRoleText
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a5
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
- object:
    example_object: Retained
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseOfficialRoleText
    example_subject: scales:/Agent/almd;;1:16-cr-00571_a20
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseOfficialRoleText
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseOfficialRoleText
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
range: string

```
</details>