

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge


_No slot (predicate) description specified_






This slot occurs 6948 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge](http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | uri | scales:/CaseCivil | scales:/Agent/casd;;3:16-cv-01644_a2 | 6948 |
| scales_Case | uri | scales:/CaseCivil | scales:/Agent/casd;;3:16-cv-01644_a2 | 6948 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
annotations:
  count:
    tag: count
    value: 6948
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Agent/casd;;3:16-cv-01644_a2
    example_object_type: uri
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:/Agent/casd;;3:16-cv-01644_a2
    example_object_type: uri
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseJudge
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseJudge
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: uri

```
</details>