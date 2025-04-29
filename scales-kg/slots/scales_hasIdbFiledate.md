

# Slot: scales_hasIdbFiledate


_No slot (predicate) description specified_






This slot occurs 327 times.


URI: [scales:hasIdbFiledate](http://schemas.scales-okn.org/rdf/scales#hasIdbFiledate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | datetime | scales:/CaseCivil | 2016-04-29T00:00:00 | 327 |
| scales_Case | datetime | scales:/CaseCivil | 2016-04-29T00:00:00 | 327 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbFiledate
annotations:
  count:
    tag: count
    value: 327
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2016-04-29T00:00:00'
    example_object_type: datetime
    example_predicate: scales:hasIdbFiledate
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '2016-04-29T00:00:00'
    example_object_type: datetime
    example_predicate: scales:hasIdbFiledate
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbFiledate
alias: scales_hasIdbFiledate
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: datetime

```
</details>