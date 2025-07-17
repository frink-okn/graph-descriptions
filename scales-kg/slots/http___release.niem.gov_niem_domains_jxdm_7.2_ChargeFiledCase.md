

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeFiledCase


_No slot (predicate) description specified_






This slot occurs 218359 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/ChargeFiledCase](http://release.niem.gov/niem/domains/jxdm/7.2/ChargeFiledCase)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No class (type) description specified |  yes  |







## Properties

* Range: [ScalesCriminalCase](../classes/ScalesCriminalCase.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Charge | scales_CriminalCase | scales:Charge/fulton-01-10000019 | scales:Case/ga-fulton-01-18CR000562G | 218359 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeFiledCase
annotations:
  count:
    tag: count
    value: 218359
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Case/ga-fulton-01-18CR000562G
    example_object_type: scales_CriminalCase
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeFiledCase
    example_subject: scales:Charge/fulton-01-10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeFiledCase
alias: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeFiledCase
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Charge
range: scales_CriminalCase

```
</details>