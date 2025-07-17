

# Slot: scales_hasCommissionDate


_No slot (predicate) description specified_






This slot occurs 4257 times.


URI: [scales:hasCommissionDate](http://schemas.scales-okn.org/rdf/scales#hasCommissionDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Judge | date | scales:JudgeEntity/SJ000009 | 2007-03-14 | 4257 |




## LinkML Source

<details>

```yaml
name: scales_hasCommissionDate
annotations:
  count:
    tag: count
    value: 4257
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2007-03-14'
    example_object_type: date
    example_predicate: scales:hasCommissionDate
    example_subject: scales:JudgeEntity/SJ000009
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasCommissionDate
alias: scales_hasCommissionDate
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Judge
range: date

```
</details>