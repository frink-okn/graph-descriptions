

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSubject


_No slot (predicate) description specified_






This slot occurs 363466 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSubject](http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSubject)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Charge | http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | scales:Charge/fulton-01-10000019 | scales:Agent/ga-fulton-01/10000019 | 363466 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSubject
annotations:
  count:
    tag: count
    value: 363466
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Agent/ga-fulton-01/10000019
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSubject
    example_subject: scales:Charge/fulton-01-10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSubject
alias: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSubject
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Charge
range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty

```
</details>