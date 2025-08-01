

# Slot: niem50_EntityName


_No slot (predicate) description specified_






This slot occurs 4241878 times.


URI: [niem50:EntityName](http://release.niem.gov/niem/niem-core/5.0/EntityName)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |
| [ScalesParty](../classes/ScalesParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | string | scales:/Agent/akd;;1:16-cr-00001_a0 | SCALES-Party-Hash-01169B980BF3557176ECC743C5841A32 | 2586246 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty | string | scales:/Agent/akd;;1:16-cr-00001_a1 | USA | 1337860 |
| scales_Party | string | scales:/Agent/akd;;1:16-cv-00008_a7 | State of Alaska | 317772 |




## LinkML Source

<details>

```yaml
name: niem50_EntityName
annotations:
  count:
    tag: count
    value: 4241878
description: No slot (predicate) description specified
examples:
- object:
    example_object: SCALES-Party-Hash-01169B980BF3557176ECC743C5841A32
    example_object_type: string
    example_predicate: niem50:EntityName
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a0
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- object:
    example_object: USA
    example_object_type: string
    example_predicate: niem50:EntityName
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a1
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- object:
    example_object: State of Alaska
    example_object_type: string
    example_predicate: niem50:EntityName
    example_subject: scales:/Agent/akd;;1:16-cv-00008_a7
    example_subject_type: scales_Party
from_schema: scales-kg
rank: 1000
slot_uri: niem50:EntityName
alias: niem50_EntityName
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingParty
- scales_Party
range: string

```
</details>