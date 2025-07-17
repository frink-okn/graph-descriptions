

# Slot: scales_assignedToDefendant


_No slot (predicate) description specified_






This slot occurs 53962 times.


URI: [scales:assignedToDefendant](http://schemas.scales-okn.org/rdf/scales#assignedToDefendant)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md)&nbsp;or&nbsp;<br />[ScalesParty](../classes/ScalesParty.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | scales:Agent/akd;;1:16-cr-00006_a4 | scales:Agent/akd;;1:16-cr-00006_a1 | 53832 |
| None | scales_Party | scales:Agent/iand;;1:16-cr-00008_a7 | scales:Agent/iand;;1:16-cr-00008_a1 | 111 |
| None | http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty | scales:Agent/ilnd;;1:03-cr-00386_a19 | scales:Agent/ilnd;;1:03-cr-00386_a1 | 19 |




## LinkML Source

<details>

```yaml
name: scales_assignedToDefendant
annotations:
  count:
    tag: count
    value: 53962
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty:
    tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    value: 53832
  http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty:
    tag: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    value: 19
  scales_Party:
    tag: scales_Party
    value: 111
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Agent/akd;;1:16-cr-00006_a1
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
    example_predicate: scales:assignedToDefendant
    example_subject: scales:Agent/akd;;1:16-cr-00006_a4
    example_subject_type: None
- object:
    example_object: scales:Agent/iand;;1:16-cr-00008_a1
    example_object_type: scales_Party
    example_predicate: scales:assignedToDefendant
    example_subject: scales:Agent/iand;;1:16-cr-00008_a7
    example_subject_type: None
- object:
    example_object: scales:Agent/ilnd;;1:03-cr-00386_a1
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
    example_predicate: scales:assignedToDefendant
    example_subject: scales:Agent/ilnd;;1:03-cr-00386_a19
    example_subject_type: None
from_schema: scales-kg
rank: 1000
slot_uri: scales:assignedToDefendant
alias: scales_assignedToDefendant
range: Any
any_of:
- range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- range: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- range: scales_Party

```
</details>