

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge


_No slot (predicate) description specified_






This slot occurs 607725 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge](http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CriminalCase | http___release.niem.gov_niem_domains_jxdm_7.2_Charge | scales:/CriminalCase/akd;;1:16-cr-00001 | scales:/Charge/akd;;1:16-cr-00001_c0-1-3 | 607725 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
annotations:
  count:
    tag: count
    value: 607725
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Charge/akd;;1:16-cr-00001_c0-1-3
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
    example_subject: scales:/CriminalCase/akd;;1:16-cr-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
domain_of:
- scales_CriminalCase
range: http___release.niem.gov_niem_domains_jxdm_7.2_Charge

```
</details>