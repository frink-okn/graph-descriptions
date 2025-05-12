

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge


_No slot (predicate) description specified_






This slot occurs 6280 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge](http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | http___release.niem.gov_niem_domains_jxdm_7.2_Charge | scales:/CaseCriminal | scales:/Charge/casd;;3:17-cr-00001_c0-1 | 6280 |
| scales_Case | http___release.niem.gov_niem_domains_jxdm_7.2_Charge | scales:/CaseCriminal | scales:/Charge/casd;;3:17-cr-00001_c0-1 | 6280 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_CaseCharge
annotations:
  count:
    tag: count
    value: 6280
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Charge/casd;;3:17-cr-00001_c0-1
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
    example_subject: scales:/CaseCriminal
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:/Charge/casd;;3:17-cr-00001_c0-1
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/CaseCharge
    example_subject: scales:/CaseCriminal
    example_subject_type: scales_Case
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