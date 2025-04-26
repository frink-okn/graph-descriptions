

# Slot: scales_hasIdbDef


_No slot (predicate) description specified_






This slot occurs 1034 times.


URI: [scales:hasIdbDef](http://schemas.scales-okn.org/rdf/scales#hasIdbDef)



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
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:/CaseCivil | "BABIES ""R"" US, INC., ET AL" | 1034 |
| scales_Case | string | scales:/CaseCivil | "BABIES ""R"" US, INC., ET AL" | 1034 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbDef
annotations:
  count:
    tag: count
    value: 1034
description: No slot (predicate) description specified
examples:
- object:
    example_object: '"BABIES ""R"" US, INC., ET AL"'
    example_object_type: string
    example_predicate: scales:hasIdbDef
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '"BABIES ""R"" US, INC., ET AL"'
    example_object_type: string
    example_predicate: scales:hasIdbDef
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbDef
alias: scales_hasIdbDef
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: string

```
</details>