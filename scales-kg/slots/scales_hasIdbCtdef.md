

# Slot: scales_hasIdbCtdef


_No slot (predicate) description specified_






This slot occurs 2 times.


URI: [scales:hasIdbCtdef](http://schemas.scales-okn.org/rdf/scales#hasIdbCtdef)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | double | scales:/CaseCriminal | 1.0 | 2 |
| scales_Case | double | scales:/CaseCriminal | 1.0 | 2 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbCtdef
annotations:
  count:
    tag: count
    value: 2
description: No slot (predicate) description specified
examples:
- object:
    example_object: '1.0'
    example_object_type: double
    example_predicate: scales:hasIdbCtdef
    example_subject: scales:/CaseCriminal
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '1.0'
    example_object_type: double
    example_predicate: scales:hasIdbCtdef
    example_subject: scales:/CaseCriminal
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbCtdef
alias: scales_hasIdbCtdef
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: double

```
</details>