

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_ReleaseDate


_No slot (predicate) description specified_






This slot occurs 400567 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/ReleaseDate](http://release.niem.gov/niem/domains/jxdm/7.2/ReleaseDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Charge | date | scales:Charge/fulton-01-10000019 | 2018-04-18 | 400567 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_ReleaseDate
annotations:
  count:
    tag: count
    value: 400567
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2018-04-18'
    example_object_type: date
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ReleaseDate
    example_subject: scales:Charge/fulton-01-10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/ReleaseDate
alias: http___release.niem.gov_niem_domains_jxdm_7.2_ReleaseDate
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Charge
range: date

```
</details>