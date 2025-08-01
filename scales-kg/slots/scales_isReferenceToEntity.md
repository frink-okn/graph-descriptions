

# Slot: scales_isReferenceToEntity


_No slot (predicate) description specified_






This slot occurs 363466 times.


URI: [scales:isReferenceToEntity](http://schemas.scales-okn.org/rdf/scales#isReferenceToEntity)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | uri | scales:Agent/ga-fulton-01/10000019 | scales:AgentParty/2DB6296D52E366F752379C777C9BE051 | 363466 |




## LinkML Source

<details>

```yaml
name: scales_isReferenceToEntity
annotations:
  count:
    tag: count
    value: 363466
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:AgentParty/2DB6296D52E366F752379C777C9BE051
    example_object_type: uri
    example_predicate: scales:isReferenceToEntity
    example_subject: scales:Agent/ga-fulton-01/10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
from_schema: scales-kg
rank: 1000
slot_uri: scales:isReferenceToEntity
alias: scales_isReferenceToEntity
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
range: uri

```
</details>