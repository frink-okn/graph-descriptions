

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText


_No slot (predicate) description specified_






This slot occurs 718593 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText](http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | string | scales:/CivilCase/akd;;1:16-cv-00001 | 28:2255 Motion to Vacate | 718593 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText
annotations:
  count:
    tag: count
    value: 718593
description: No slot (predicate) description specified
examples:
- object:
    example_object: 28:2255 Motion to Vacate
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText
    example_subject: scales:/CivilCase/akd;;1:16-cv-00001
    example_subject_type: scales_CivilCase
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/StatuteKeywordText
alias: http___release.niem.gov_niem_domains_jxdm_7.2_StatuteKeywordText
domain_of:
- scales_CivilCase
range: string

```
</details>