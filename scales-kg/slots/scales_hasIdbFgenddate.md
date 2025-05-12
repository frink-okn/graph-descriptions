

# Slot: scales_hasIdbFgenddate


_No slot (predicate) description specified_






This slot occurs 167 times.


URI: [scales:hasIdbFgenddate](http://schemas.scales-okn.org/rdf/scales#hasIdbFgenddate)



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
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:/CaseCriminal | 01/01/1900 | 167 |
| scales_Case | string | scales:/CaseCriminal | 01/01/1900 | 167 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbFgenddate
annotations:
  count:
    tag: count
    value: 167
description: No slot (predicate) description specified
examples:
- object:
    example_object: 01/01/1900
    example_object_type: string
    example_predicate: scales:hasIdbFgenddate
    example_subject: scales:/CaseCriminal
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: 01/01/1900
    example_object_type: string
    example_predicate: scales:hasIdbFgenddate
    example_subject: scales:/CaseCriminal
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbFgenddate
alias: scales_hasIdbFgenddate
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: string

```
</details>