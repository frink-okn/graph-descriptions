

# Slot: niem50_PersonFullName


_No slot (predicate) description specified_






This slot occurs 35009 times.


URI: [niem50:PersonFullName](http://release.niem.gov/niem/niem-core/5.0/PersonFullName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Attorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Attorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | string | scales:/Agent/casd;;3:16-cv-01644_a2 | Judge Gonzalo P. Curiel | 6948 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney | string | scales:/Agent/casd;;3:16-cv-01644_a3 | SCALES-Party-Hash-A832763C1FE77A32B6DE912B9C77F80C | 9088 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney | string | scales:/Agent/casd;;3:16-cv-01644_a5 | Ryan A. Sausedo | 11050 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Attorney | string | scales:/Agent/casd;;3:16-cv-01645_a20 | Benjamin Gilford | 2538 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Judge | string | scales:/JudgeEntity/SJ000002 | Carroll O Switzer | 5385 |




## LinkML Source

<details>

```yaml
name: niem50_PersonFullName
annotations:
  count:
    tag: count
    value: 35009
  string:
    tag: string
    value: 6948
description: No slot (predicate) description specified
examples:
- object:
    example_object: Judge Gonzalo P. Curiel
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:/Agent/casd;;3:16-cv-01644_a2
    example_subject_type: None
- object:
    example_object: SCALES-Party-Hash-A832763C1FE77A32B6DE912B9C77F80C
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:/Agent/casd;;3:16-cv-01644_a3
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
- object:
    example_object: Ryan A. Sausedo
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:/Agent/casd;;3:16-cv-01644_a5
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- object:
    example_object: Benjamin Gilford
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:/Agent/casd;;3:16-cv-01645_a20
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
- object:
    example_object: Carroll O Switzer
    example_object_type: string
    example_predicate: niem50:PersonFullName
    example_subject: scales:/JudgeEntity/SJ000002
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
from_schema: scales-kg
rank: 1000
slot_uri: niem50:PersonFullName
alias: niem50_PersonFullName
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
- http___release.niem.gov_niem_domains_jxdm_7.2_Judge
range: string

```
</details>