

# Slot: niem50_PersonFullName


_No slot (predicate) description specified_






This slot occurs 17954252 times.


URI: [niem50:PersonFullName](http://release.niem.gov/niem/niem-core/5.0/PersonFullName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseJudge.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Attorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Attorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |
| [ScalesParty](../classes/ScalesParty.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | string | scales:/Agent/akd;;1:16-cr-00001_a2 | Timothy M. Burgess | 1216331 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney | string | scales:/Agent/akd;;1:16-cr-00001_a3 | Matthew McCrary Scoble | 2823772 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney | string | scales:/Agent/akd;;1:16-cr-00001_a5 | Jack S. Schmidt | 2755161 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Attorney | string | scales:/Agent/akd;;1:16-cv-00008_a22 | Mary Ann Lundquist | 537560 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Judge | string | scales:/JudgeEntity/SJ000001 | Stephen H Locher | 5385 |
| scales_Party | string | scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a0 | BRAZELTON TROY DBA | 7044753 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | string | scales:Agent/ga-fulton-01/10000019 | SCALES-Party-Hash-2DB6296D52E366F752379C777C9BE051 | 363500 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge | string | scales:Judge/ga-clayton-magistrate-civil;;0:00-cm-00001_3 | BAIRD | 3207790 |




## LinkML Source

<details>

```yaml
name: niem50_PersonFullName
annotations:
  count:
    tag: count
    value: 17954252
  string:
    tag: string
    value: 1216331
description: No slot (predicate) description specified
examples:
- object:
    example_object: Timothy M. Burgess
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a2
    example_subject_type: None
- object:
    example_object: Matthew McCrary Scoble
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a3
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- object:
    example_object: Jack S. Schmidt
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a5
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
- object:
    example_object: Mary Ann Lundquist
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:/Agent/akd;;1:16-cv-00008_a22
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
- object:
    example_object: Stephen H Locher
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:/JudgeEntity/SJ000001
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
- object:
    example_object: BRAZELTON TROY DBA
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00001_a0
    example_subject_type: scales_Party
- object:
    example_object: SCALES-Party-Hash-2DB6296D52E366F752379C777C9BE051
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:Agent/ga-fulton-01/10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- object:
    example_object: BAIRD
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:Judge/ga-clayton-magistrate-civil;;0:00-cm-00001_3
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
from_schema: scales-kg
rank: 1000
slot_uri: niem50:PersonFullName
alias: niem50_PersonFullName
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
- http___release.niem.gov_niem_domains_jxdm_7.2_Judge
- scales_Party
range: string

```
</details>