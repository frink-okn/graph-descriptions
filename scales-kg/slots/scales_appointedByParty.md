

# Slot: scales_appointedByParty


_No slot (predicate) description specified_






This slot occurs 3912 times.


URI: [scales:appointedByParty](http://schemas.scales-okn.org/rdf/scales#appointedByParty)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Judge | string | scales:JudgeEntity/SJ000002 | Democratic | 3912 |




## LinkML Source

<details>

```yaml
name: scales_appointedByParty
annotations:
  count:
    tag: count
    value: 3912
description: No slot (predicate) description specified
examples:
- object:
    example_object: Democratic
    example_object_type: string
    example_predicate: scales:appointedByParty
    example_subject: scales:JudgeEntity/SJ000002
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
from_schema: scales-kg
rank: 1000
slot_uri: scales:appointedByParty
alias: scales_appointedByParty
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Judge
range: string

```
</details>