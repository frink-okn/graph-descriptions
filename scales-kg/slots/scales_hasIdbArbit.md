

# Slot: scales_hasIdbArbit


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [scales:hasIdbArbit](http://schemas.scales-okn.org/rdf/scales#hasIdbArbit)



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
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:/CaseCivil | -8 | 1 |
| scales_Case | string | scales:/CaseCivil | -8 | 1 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbArbit
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
examples:
- object:
    example_object: '-8'
    example_object_type: string
    example_predicate: scales:hasIdbArbit
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '-8'
    example_object_type: string
    example_predicate: scales:hasIdbArbit
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbArbit
alias: scales_hasIdbArbit
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: string

```
</details>