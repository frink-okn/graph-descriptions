

# Slot: niem50_StartDate


_No slot (predicate) description specified_






This slot occurs 327 times.


URI: [niem50:StartDate](http://release.niem.gov/niem/niem-core/5.0/StartDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | date | scales:/CaseCivil | 2016-05-23 | 327 |
| scales_Case | date | scales:/CaseCivil | 2016-05-23 | 327 |




## LinkML Source

<details>

```yaml
name: niem50_StartDate
annotations:
  count:
    tag: count
    value: 327
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2016-05-23'
    example_object_type: date
    example_predicate: niem50:StartDate
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '2016-05-23'
    example_object_type: date
    example_predicate: niem50:StartDate
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: niem50:StartDate
alias: niem50_StartDate
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: date

```
</details>