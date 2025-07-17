

# Slot: scales_hasIdbTermdate


_No slot (predicate) description specified_






This slot occurs 7519 times.


URI: [scales:hasIdbTermdate](http://schemas.scales-okn.org/rdf/scales#hasIdbTermdate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | datetime | scales:CivilCase | 1987-12-30T00:00:00 | 7519 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbTermdate
annotations:
  count:
    tag: count
    value: 7519
description: No slot (predicate) description specified
examples:
- object:
    example_object: '1987-12-30T00:00:00'
    example_object_type: datetime
    example_predicate: scales:hasIdbTermdate
    example_subject: scales:CivilCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
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