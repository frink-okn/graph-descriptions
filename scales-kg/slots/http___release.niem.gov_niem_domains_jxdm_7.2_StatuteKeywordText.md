

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText


_No slot (predicate) description specified_






This slot occurs 211 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText](http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText)



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
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:/CaseCivil | 00:0000 Cause Code Unknown | 211 |
| scales_Case | string | scales:/CaseCivil | 00:0000 Cause Code Unknown | 211 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText
annotations:
  count:
    tag: count
    value: 211
description: No slot (predicate) description specified
examples:
- object:
    example_object: 00:0000 Cause Code Unknown
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: 00:0000 Cause Code Unknown
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText
alias: http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: string

```
</details>