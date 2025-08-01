

# Slot: niem50_ActivityDate


_No slot (predicate) description specified_






This slot occurs 904252 times.


URI: [niem50:ActivityDate](http://release.niem.gov/niem/niem-core/5.0/ActivityDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Booking](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Booking.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Arrest](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Arrest.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Release](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Release.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Booking | date | scales:Booking/ga-fulton-01/10000019 | 2018-04-18 | 419406 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Release | date | scales:Release/ga-fulton-01/10000019 | 2018-04-18 | 400567 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Arrest | date | scales:Arrest/ga-atlanta-pd-100720495 | 2014-05-03 | 84279 |




## LinkML Source

<details>

```yaml
name: niem50_ActivityDate
annotations:
  count:
    tag: count
    value: 904252
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2018-04-18'
    example_object_type: date
    example_predicate: niem50:ActivityDate
    example_subject: scales:Booking/ga-fulton-01/10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Booking
- object:
    example_object: '2018-04-18'
    example_object_type: date
    example_predicate: niem50:ActivityDate
    example_subject: scales:Release/ga-fulton-01/10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Release
- object:
    example_object: '2014-05-03'
    example_object_type: date
    example_predicate: niem50:ActivityDate
    example_subject: scales:Arrest/ga-atlanta-pd-100720495
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Arrest
from_schema: scales-kg
rank: 1000
slot_uri: niem50:ActivityDate
alias: niem50_ActivityDate
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Arrest
- http___release.niem.gov_niem_domains_jxdm_7.2_Booking
- http___release.niem.gov_niem_domains_jxdm_7.2_Release
range: date

```
</details>