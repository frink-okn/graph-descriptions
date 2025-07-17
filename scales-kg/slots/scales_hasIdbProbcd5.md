

# Slot: scales_hasIdbProbcd5


_No slot (predicate) description specified_






This slot occurs 3 times.


URI: [scales:hasIdbProbcd5](http://schemas.scales-okn.org/rdf/scales#hasIdbProbcd5)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:CriminalCase | -8 | 2 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | integer | scales:CriminalCase | -8 | 1 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbProbcd5
annotations:
  count:
    tag: count
    value: 3
description: No slot (predicate) description specified
examples:
- object:
    example_object: '-8'
    example_object_type: string
    example_predicate: scales:hasIdbProbcd5
    example_subject: scales:CriminalCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '-8'
    example_object_type: integer
    example_predicate: scales:hasIdbProbcd5
    example_subject: scales:CriminalCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbProbcd5
alias: scales_hasIdbProbcd5
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: Any
any_of:
- range: string
- range: integer

```
</details>