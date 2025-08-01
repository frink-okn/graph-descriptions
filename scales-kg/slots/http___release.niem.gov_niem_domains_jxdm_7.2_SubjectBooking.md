

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_SubjectBooking


_No slot (predicate) description specified_






This slot occurs 363466 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/SubjectBooking](http://release.niem.gov/niem/domains/jxdm/7.2/SubjectBooking)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2Booking](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Booking.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | http___release.niem.gov_niem_domains_jxdm_7.2_Booking | scales:Agent/ga-fulton-01/10000019 | scales:Booking/ga-fulton-01/10000019 | 363466 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_SubjectBooking
annotations:
  count:
    tag: count
    value: 363466
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Booking/ga-fulton-01/10000019
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Booking
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/SubjectBooking
    example_subject: scales:Agent/ga-fulton-01/10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/SubjectBooking
alias: http___release.niem.gov_niem_domains_jxdm_7.2_SubjectBooking
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
range: http___release.niem.gov_niem_domains_jxdm_7.2_Booking

```
</details>