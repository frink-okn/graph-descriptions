

# Slot: niem50_CaseDocketID


_No slot (predicate) description specified_






This slot occurs 5000 times.


URI: [niem50:CaseDocketID](http://release.niem.gov/niem/niem-core/5.0/CaseDocketID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:/CaseCivil | 3:16-cv-01644 | 5000 |
| scales_Case | string | scales:/CaseCivil | 3:16-cv-01644 | 5000 |




## LinkML Source

<details>

```yaml
name: niem50_CaseDocketID
annotations:
  count:
    tag: count
    value: 5000
description: No slot (predicate) description specified
examples:
- object:
    example_object: 3:16-cv-01644
    example_object_type: string
    example_predicate: niem50:CaseDocketID
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: 3:16-cv-01644
    example_object_type: string
    example_predicate: niem50:CaseDocketID
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: niem50:CaseDocketID
alias: niem50_CaseDocketID
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: string

```
</details>