

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CourtName


_No slot (predicate) description specified_






This slot occurs 94 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CourtName](http://release.niem.gov/niem/domains/jxdm/7.2/CourtName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Court](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Court.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Court | string | scales:Court/akd | District Court, D. Alaska | 94 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CourtName
annotations:
  count:
    tag: count
    value: 94
description: No slot (predicate) description specified
examples:
- object:
    example_object: District Court, D. Alaska
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CourtName
    example_subject: scales:Court/akd
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Court
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CourtName
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CourtName
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Court
range: string

```
</details>