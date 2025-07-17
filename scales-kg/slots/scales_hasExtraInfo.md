

# Slot: scales_hasExtraInfo


_No slot (predicate) description specified_






This slot occurs 861769 times.


URI: [scales:hasExtraInfo](http://schemas.scales-okn.org/rdf/scales#hasExtraInfo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | No class (type) description specified |  yes  |
| [ScalesParty](../classes/ScalesParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | string | scales:Agent/akd;;1:16-cr-00004_a0 | doing business as
Northstar Gift Shop | 671599 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty | string | scales:Agent/akd;;1:16-cv-00003_a0 | Soc. Sec. #XXX-XX-0767 | 147013 |
| scales_Party | string | scales:Agent/akd;;3:16-cv-00062_a4 | husband and wife | 43157 |




## LinkML Source

<details>

```yaml
name: scales_hasExtraInfo
annotations:
  count:
    tag: count
    value: 861769
description: No slot (predicate) description specified
examples:
- object:
    example_object: 'doing business as

      Northstar Gift Shop'
    example_object_type: string
    example_predicate: scales:hasExtraInfo
    example_subject: scales:Agent/akd;;1:16-cr-00004_a0
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- object:
    example_object: 'Soc. Sec. #XXX-XX-0767'
    example_object_type: string
    example_predicate: scales:hasExtraInfo
    example_subject: scales:Agent/akd;;1:16-cv-00003_a0
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- object:
    example_object: husband and wife
    example_object_type: string
    example_predicate: scales:hasExtraInfo
    example_subject: scales:Agent/akd;;3:16-cv-00062_a4
    example_subject_type: scales_Party
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasExtraInfo
alias: scales_hasExtraInfo
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- scales_Party
range: string

```
</details>