

# Slot: niem50_PersonRaceText


_No slot (predicate) description specified_






This slot occurs 450612 times.


URI: [niem50:PersonRaceText](http://release.niem.gov/niem/niem-core/5.0/PersonRaceText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |
| [Niem50Person](../classes/Niem50Person.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Judge | string | scales:/JudgeEntity/SJ000002 | White | 3762 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | string | scales:Agent/ga-fulton-01/10000019 | B | 363414 |
| niem50_Person | string | scales:ArrestSubject/ga-atlanta-pd-100720495 | B | 83436 |




## LinkML Source

<details>

```yaml
name: niem50_PersonRaceText
annotations:
  count:
    tag: count
    value: 450612
description: No slot (predicate) description specified
examples:
- object:
    example_object: White
    example_object_type: string
    example_predicate: niem50:PersonRaceText
    example_subject: scales:/JudgeEntity/SJ000002
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
- object:
    example_object: B
    example_object_type: string
    example_predicate: niem50:PersonRaceText
    example_subject: scales:Agent/ga-fulton-01/10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- object:
    example_object: B
    example_object_type: string
    example_predicate: niem50:PersonRaceText
    example_subject: scales:ArrestSubject/ga-atlanta-pd-100720495
    example_subject_type: niem50_Person
from_schema: scales-kg
rank: 1000
slot_uri: niem50:PersonRaceText
alias: niem50_PersonRaceText
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- http___release.niem.gov_niem_domains_jxdm_7.2_Judge
- niem50_Person
range: string

```
</details>