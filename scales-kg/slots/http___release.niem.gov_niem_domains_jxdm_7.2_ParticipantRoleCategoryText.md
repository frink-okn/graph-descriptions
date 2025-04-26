

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText


_No slot (predicate) description specified_






This slot occurs 16341 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText](http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesParty](../classes/ScalesParty.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty | string | scales:/Agent/casd;;3:16-cv-01644_a0 | Petitioner | 5633 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | string | scales:/Agent/casd;;3:16-cv-01644_a1 | Respondent | 8389 |
| scales_Party | string | scales:/Agent/casd;;3:16-cv-01645_a3 | Counter Claimant | 2319 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
annotations:
  count:
    tag: count
    value: 16341
description: No slot (predicate) description specified
examples:
- object:
    example_object: Petitioner
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
    example_subject: scales:/Agent/casd;;3:16-cv-01644_a0
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- object:
    example_object: Respondent
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
    example_subject: scales:/Agent/casd;;3:16-cv-01644_a1
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- object:
    example_object: Counter Claimant
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
    example_subject: scales:/Agent/casd;;3:16-cv-01645_a3
    example_subject_type: scales_Party
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/ParticipantRoleCategoryText
alias: http___release.niem.gov_niem_domains_jxdm_7.2_ParticipantRoleCategoryText
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- scales_Party
range: string

```
</details>