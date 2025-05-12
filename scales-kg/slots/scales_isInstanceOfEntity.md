

# Slot: scales_isInstanceOfEntity


_No slot (predicate) description specified_






This slot occurs 12697 times.


URI: [scales:isInstanceOfEntity](http://schemas.scales-okn.org/rdf/scales#isInstanceOfEntity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |
| [ScalesParty](../classes/ScalesParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2Judge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Judge.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | uri | scales:/Agent/casd;;3:16-cv-01644_a1 | scales:/PartyEntity/SPID-GOVERNMENT-ST-025-000001969 | 1778 |
| None | http___release.niem.gov_niem_domains_jxdm_7.2_Judge | scales:/Agent/casd;;3:17-cr-03540_a2 | scales:/JudgeEntity/SJ002053 | 6947 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty | uri | scales:/Agent/casd;;3:16-cv-01645_a0 | scales:/PartyEntity/SPID-INDUSTRY-ST-020-000011105 | 3765 |
| scales_Party | uri | scales:/Agent/casd;;3:16-cv-01645_a3 | scales:/PartyEntity/SPID-INDUSTRY-ST-008-000022280 | 207 |




## LinkML Source

<details>

```yaml
name: scales_isInstanceOfEntity
annotations:
  count:
    tag: count
    value: 12697
  http___release.niem.gov_niem_domains_jxdm_7.2_Judge:
    tag: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    value: 6947
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/PartyEntity/SPID-GOVERNMENT-ST-025-000001969
    example_object_type: uri
    example_predicate: scales:isInstanceOfEntity
    example_subject: scales:/Agent/casd;;3:16-cv-01644_a1
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- object:
    example_object: scales:/JudgeEntity/SJ002053
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Judge
    example_predicate: scales:isInstanceOfEntity
    example_subject: scales:/Agent/casd;;3:17-cr-03540_a2
    example_subject_type: None
- object:
    example_object: scales:/PartyEntity/SPID-INDUSTRY-ST-020-000011105
    example_object_type: uri
    example_predicate: scales:isInstanceOfEntity
    example_subject: scales:/Agent/casd;;3:16-cv-01645_a0
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- object:
    example_object: scales:/PartyEntity/SPID-INDUSTRY-ST-008-000022280
    example_object_type: uri
    example_predicate: scales:isInstanceOfEntity
    example_subject: scales:/Agent/casd;;3:16-cv-01645_a3
    example_subject_type: scales_Party
from_schema: scales-kg
rank: 1000
slot_uri: scales:isInstanceOfEntity
alias: scales_isInstanceOfEntity
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- scales_Party
range: Any
any_of:
- range: uri
- range: http___release.niem.gov_niem_domains_jxdm_7.2_Judge

```
</details>