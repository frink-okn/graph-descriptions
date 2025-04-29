

# Slot: scales_hasIdbFsev1


_No slot (predicate) description specified_






This slot occurs 60 times.


URI: [scales:hasIdbFsev1](http://schemas.scales-okn.org/rdf/scales#hasIdbFsev1)



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
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:/CaseCriminal | 013 | 60 |
| scales_Case | string | scales:/CaseCriminal | 013 | 60 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbFsev1
annotations:
  count:
    tag: count
    value: 60
description: No slot (predicate) description specified
examples:
- object:
    example_object: '013'
    example_object_type: string
    example_predicate: scales:hasIdbFsev1
    example_subject: scales:/CaseCriminal
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '013'
    example_object_type: string
    example_predicate: scales:hasIdbFsev1
    example_subject: scales:/CaseCriminal
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbFsev1
alias: scales_hasIdbFsev1
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: string

```
</details>