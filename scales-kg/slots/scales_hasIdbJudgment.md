

# Slot: scales_hasIdbJudgment


_No slot (predicate) description specified_






This slot occurs 6 times.


URI: [scales:hasIdbJudgment](http://schemas.scales-okn.org/rdf/scales#hasIdbJudgment)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | double | scales:CivilCase | -8.0 | 6 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbJudgment
annotations:
  count:
    tag: count
    value: 6
description: No slot (predicate) description specified
examples:
- object:
    example_object: '-8.0'
    example_object_type: double
    example_predicate: scales:hasIdbJudgment
    example_subject: scales:CivilCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbJudgment
alias: scales_hasIdbJudgment
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: double

```
</details>