

# Slot: scales_hasIdbTypetrn


_No slot (predicate) description specified_






This slot occurs 2 times.


URI: [scales:hasIdbTypetrn](http://schemas.scales-okn.org/rdf/scales#hasIdbTypetrn)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:/CaseCriminal | -8 | 1 |
| scales_Case | string | scales:/CaseCriminal | -8 | 1 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | integer | scales:/CaseCriminal | -8 | 1 |
| scales_Case | integer | scales:/CaseCriminal | -8 | 1 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbTypetrn
annotations:
  count:
    tag: count
    value: 2
description: No slot (predicate) description specified
examples:
- object:
    example_object: '-8'
    example_object_type: string
    example_predicate: scales:hasIdbTypetrn
    example_subject: scales:/CaseCriminal
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '-8'
    example_object_type: string
    example_predicate: scales:hasIdbTypetrn
    example_subject: scales:/CaseCriminal
    example_subject_type: scales_Case
- object:
    example_object: '-8'
    example_object_type: integer
    example_predicate: scales:hasIdbTypetrn
    example_subject: scales:/CaseCriminal
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '-8'
    example_object_type: integer
    example_predicate: scales:hasIdbTypetrn
    example_subject: scales:/CaseCriminal
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTypetrn
alias: scales_hasIdbTypetrn
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: Any
any_of:
- range: integer
- range: string

```
</details>