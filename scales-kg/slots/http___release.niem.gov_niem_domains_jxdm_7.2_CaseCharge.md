

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge


_No slot (predicate) description specified_






This slot occurs 389366 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge](http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_Case | http___release.niem.gov_niem_domains_jxdm_7.2_Charge | scales:CriminalCase | scales:Charge/akd;;1:16-cr-00001_c0-1-3 | 389366 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | http___release.niem.gov_niem_domains_jxdm_7.2_Charge | scales:CriminalCase | scales:Charge/akd;;1:16-cr-00001_c0-1-3 | 389366 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
annotations:
  count:
    tag: count
    value: 389366
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Charge/akd;;1:16-cr-00001_c0-1-3
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
    example_subject: scales:CriminalCase
    example_subject_type: scales_Case
- object:
    example_object: scales:Charge/akd;;1:16-cr-00001_c0-1-3
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
    example_subject: scales:CriminalCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
alias: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: http___release.niem.gov_niem_domains_jxdm_7.2_Charge

```
</details>