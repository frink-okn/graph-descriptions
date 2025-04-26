

# Slot: scales_Party


_No slot (predicate) description specified_






This slot occurs 2319 times.


URI: [scales:Party](http://schemas.scales-okn.org/rdf/scales#Party)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |







## Properties

* Range: [ScalesParty](../classes/ScalesParty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCase](../classes/ScalesCase.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | scales_Party | scales:/CaseCivil | scales:/Agent/casd;;3:16-cv-01645_a3 | 2319 |
| scales_Case | scales_Party | scales:/CaseCivil | scales:/Agent/casd;;3:16-cv-01645_a3 | 2319 |




## LinkML Source

<details>

```yaml
name: scales_Party
annotations:
  count:
    tag: count
    value: 2319
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Agent/casd;;3:16-cv-01645_a3
    example_object_type: scales_Party
    example_predicate: scales:Party
    example_subject: scales:/CaseCivil
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:/Agent/casd;;3:16-cv-01645_a3
    example_object_type: scales_Party
    example_predicate: scales:Party
    example_subject: scales:/CaseCivil
    example_subject_type: scales_Case
from_schema: scales-kg
rank: 1000
slot_uri: scales:Party
alias: scales_Party
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
range: scales_Party

```
</details>