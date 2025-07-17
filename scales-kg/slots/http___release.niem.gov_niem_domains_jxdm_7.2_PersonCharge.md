

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge


_No slot (predicate) description specified_






This slot occurs 2908749 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge](http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesAgent](../classes/ScalesAgent.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |
| [ScalesParty](../classes/ScalesParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | http___release.niem.gov_niem_domains_jxdm_7.2_Charge | scales:Agent/akd;;1:16-cr-00001_a0 | scales:Charge/akd;;1:16-cr-00001_c0-1-3 | 389366 |
| scales_Party | http___release.niem.gov_niem_domains_jxdm_7.2_Charge | scales:Agent/ga-clayton-magistrate;;0:00-bc-00001_a0 | scales:Charge/ga-clayton-magistrate;;0:00-bc-00001_c0 | 2155917 |
| scales_Agent | http___release.niem.gov_niem_domains_jxdm_7.2_Charge | scales:Agent/10000019_0 | scales:Charge/fulton-01-10000019 | 363466 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
annotations:
  count:
    tag: count
    value: 2908749
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Charge/akd;;1:16-cr-00001_c0-1-3
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
    example_subject: scales:Agent/akd;;1:16-cr-00001_a0
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- object:
    example_object: scales:Charge/ga-clayton-magistrate;;0:00-bc-00001_c0
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
    example_subject: scales:Agent/ga-clayton-magistrate;;0:00-bc-00001_a0
    example_subject_type: scales_Party
- object:
    example_object: scales:Charge/fulton-01-10000019
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
    example_subject: scales:Agent/10000019_0
    example_subject_type: scales_Agent
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/PersonCharge
alias: http___release.niem.gov_niem_domains_jxdm_7.2_PersonCharge
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- scales_Agent
- scales_Party
range: http___release.niem.gov_niem_domains_jxdm_7.2_Charge

```
</details>