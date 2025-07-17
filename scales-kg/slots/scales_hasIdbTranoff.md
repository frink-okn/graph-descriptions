

# Slot: scales_hasIdbTranoff


_No slot (predicate) description specified_






This slot occurs 9 times.


URI: [scales:hasIdbTranoff](http://schemas.scales-okn.org/rdf/scales#hasIdbTranoff)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:integer](http://www.w3.org/2001/XMLSchema#integer)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | integer | scales:CriminalCase | -8 | 9 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbTranoff
annotations:
  count:
    tag: count
    value: 9
description: No slot (predicate) description specified
examples:
- object:
    example_object: '-8'
    example_object_type: integer
    example_predicate: scales:hasIdbTranoff
    example_subject: scales:CriminalCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTranoff
alias: scales_hasIdbTranoff
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: integer

```
</details>