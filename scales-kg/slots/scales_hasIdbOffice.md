

# Slot: scales_hasIdbOffice


_No slot (predicate) description specified_






This slot occurs 2 times.


URI: [scales:hasIdbOffice](http://schemas.scales-okn.org/rdf/scales#hasIdbOffice)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:/CaseCivil | 3 | 2 |
| scales_Case | string | scales:/CaseCivil | 3 | 2 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbOffice
annotations:
  count:
    tag: count
    value: 2
description: No slot (predicate) description specified
examples:
- object:
    example_object: '3'
    example_object_type: string
    example_predicate: scales:hasIdbOffice
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '3'
    example_object_type: string
    example_predicate: scales:hasIdbOffice
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbOffice
alias: scales_hasIdbOffice
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: string

```
</details>