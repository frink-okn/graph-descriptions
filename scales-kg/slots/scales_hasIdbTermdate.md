

# Slot: scales_hasIdbTermdate


_No slot (predicate) description specified_






This slot occurs 808 times.


URI: [scales:hasIdbTermdate](http://schemas.scales-okn.org/rdf/scales#hasIdbTermdate)



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
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | datetime | scales:/CaseCivil | 2016-06-29T00:00:00 | 808 |
| scales_Case | datetime | scales:/CaseCivil | 2016-06-29T00:00:00 | 808 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbTermdate
annotations:
  count:
    tag: count
    value: 808
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2016-06-29T00:00:00'
    example_object_type: datetime
    example_predicate: scales:hasIdbTermdate
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '2016-06-29T00:00:00'
    example_object_type: datetime
    example_predicate: scales:hasIdbTermdate
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTermdate
alias: scales_hasIdbTermdate
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: datetime

```
</details>