

# Slot: scales_hasIdbStatuscd


_No slot (predicate) description specified_






This slot occurs 4 times.


URI: [scales:hasIdbStatuscd](http://schemas.scales-okn.org/rdf/scales#hasIdbStatuscd)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:/CaseCivil | L | 4 |
| scales_Case | string | scales:/CaseCivil | L | 4 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbStatuscd
annotations:
  count:
    tag: count
    value: 4
description: No slot (predicate) description specified
examples:
- object:
    example_object: L
    example_object_type: string
    example_predicate: scales:hasIdbStatuscd
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: L
    example_object_type: string
    example_predicate: scales:hasIdbStatuscd
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbStatuscd
alias: scales_hasIdbStatuscd
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: string

```
</details>