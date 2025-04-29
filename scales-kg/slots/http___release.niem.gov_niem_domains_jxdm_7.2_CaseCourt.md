

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt


_No slot (predicate) description specified_






This slot occurs 2 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt](http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2Court](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Court.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | http___release.niem.gov_niem_domains_jxdm_7.2_Court | scales:/CaseCivil | scales:/Court/casd | 2 |
| scales_Case | http___release.niem.gov_niem_domains_jxdm_7.2_Court | scales:/CaseCivil | scales:/Court/casd | 2 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
annotations:
  count:
    tag: count
    value: 2
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Court/casd
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Court
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:/Court/casd
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Court
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCourt
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCourt
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: http___release.niem.gov_niem_domains_jxdm_7.2_Court

```
</details>