

# Slot: scales_BookingCase


_No slot (predicate) description specified_






This slot occurs 218359 times.


URI: [scales:BookingCase](http://schemas.scales-okn.org/rdf/scales#BookingCase)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Booking](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Booking.md) | No class (type) description specified |  yes  |







## Properties

* Range: [ScalesCriminalCase](../classes/ScalesCriminalCase.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Booking | scales_CriminalCase | scales:Booking/ga-fulton-01/10000019 | scales:Case/ga-fulton-01-18CR000562G | 218359 |




## LinkML Source

<details>

```yaml
name: scales_BookingCase
annotations:
  count:
    tag: count
    value: 218359
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Case/ga-fulton-01-18CR000562G
    example_object_type: scales_CriminalCase
    example_predicate: scales:BookingCase
    example_subject: scales:Booking/ga-fulton-01/10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Booking
from_schema: scales-kg
rank: 1000
slot_uri: scales:BookingCase
alias: scales_BookingCase
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Booking
range: scales_CriminalCase

```
</details>