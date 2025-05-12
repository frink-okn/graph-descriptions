

# Slot: scales_hasIdbFiscalyr


_No slot (predicate) description specified_






This slot occurs 2 times.


URI: [scales:hasIdbFiscalyr](http://schemas.scales-okn.org/rdf/scales#hasIdbFiscalyr)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | double | scales:/CaseCriminal | 2017.0 | 2 |
| scales_Case | double | scales:/CaseCriminal | 2017.0 | 2 |




## LinkML Source

<details>

```yaml
name: scales_hasIdbFiscalyr
annotations:
  count:
    tag: count
    value: 2
description: No slot (predicate) description specified
examples:
- object:
    example_object: '2017.0'
    example_object_type: double
    example_predicate: scales:hasIdbFiscalyr
    example_subject: scales:/CaseCriminal
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: '2017.0'
    example_object_type: double
    example_predicate: scales:hasIdbFiscalyr
    example_subject: scales:/CaseCriminal
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbFiscalyr
alias: scales_hasIdbFiscalyr
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: double

```
</details>