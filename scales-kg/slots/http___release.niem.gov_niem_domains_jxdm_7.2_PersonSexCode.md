

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_PersonSexCode


_No slot (predicate) description specified_






This slot occurs 448932 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/PersonSexCode](http://release.niem.gov/niem/domains/jxdm/7.2/PersonSexCode)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Niem50Person](../classes/Niem50Person.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty | string | scales:Agent/ga-fulton-01/10000019 | M  | 363445 |
| niem50_Person | string | scales:ArrestSubject/ga-atlanta-pd-100720495 | M | 85487 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_PersonSexCode
annotations:
  count:
    tag: count
    value: 448932
description: No slot (predicate) description specified
examples:
- object:
    example_object: 'M '
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/PersonSexCode
    example_subject: scales:Agent/ga-fulton-01/10000019
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- object:
    example_object: M
    example_object_type: string
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/PersonSexCode
    example_subject: scales:ArrestSubject/ga-atlanta-pd-100720495
    example_subject_type: niem50_Person
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/PersonSexCode
alias: http___release.niem.gov_niem_domains_jxdm_7.2_PersonSexCode
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefendantParty
- niem50_Person
range: string

```
</details>