

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge


_No slot (predicate) description specified_






This slot occurs 6280 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge](http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | http___release.niem.gov_niem_domains_jxdm_7.2_Charge | scales:/Agent/casd;;3:17-cr-00001_a0 | scales:/Charge/casd;;3:17-cr-00001_c0-1 | 6280 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
annotations:
  count:
    tag: count
    value: 6280
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Charge/casd;;3:17-cr-00001_c0-1
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
    example_subject: scales:/Agent/casd;;3:17-cr-00001_a0
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
alias: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
range: http___release.niem.gov_niem_domains_jxdm_7.2_Charge

```
</details>