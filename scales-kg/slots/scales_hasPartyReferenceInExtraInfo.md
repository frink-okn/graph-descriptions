

# Slot: scales_hasPartyReferenceInExtraInfo


_No slot (predicate) description specified_






This slot occurs 149 times.


URI: [scales:hasPartyReferenceInExtraInfo](http://schemas.scales-okn.org/rdf/scales#hasPartyReferenceInExtraInfo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | uri | scales:/Agent/casd;;3:16-cv-01667_a1 | scales:/PartyEntity/SPID-INDUSTRY-ST-010-000002068 | 137 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty | uri | scales:/Agent/casd;;3:16-cv-01713_a0 | scales:/PartyEntity/SPID-INDUSTRY-ST-016-000023681 | 12 |




## LinkML Source

<details>

```yaml
name: scales_hasPartyReferenceInExtraInfo
annotations:
  count:
    tag: count
    value: 149
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/PartyEntity/SPID-INDUSTRY-ST-010-000002068
    example_object_type: uri
    example_predicate: scales:hasPartyReferenceInExtraInfo
    example_subject: scales:/Agent/casd;;3:16-cv-01667_a1
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- object:
    example_object: scales:/PartyEntity/SPID-INDUSTRY-ST-016-000023681
    example_object_type: uri
    example_predicate: scales:hasPartyReferenceInExtraInfo
    example_subject: scales:/Agent/casd;;3:16-cv-01713_a0
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasPartyReferenceInExtraInfo
alias: scales_hasPartyReferenceInExtraInfo
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
range: uri

```
</details>