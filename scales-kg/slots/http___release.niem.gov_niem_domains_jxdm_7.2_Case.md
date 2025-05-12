

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_Case


_No slot (predicate) description specified_






This slot occurs 5000 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/Case](http://release.niem.gov/niem/domains/jxdm/7.2/Case)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md)&nbsp;or&nbsp;<br />[ScalesCase](../classes/ScalesCase.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [scales_hasMemberCase](../slots/scales_hasMemberCase.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) |
| [ScalesCase](../classes/ScalesCase.md) | [scales_hasRelatedCase](../slots/scales_hasRelatedCase.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) |
| [ScalesCase](../classes/ScalesCase.md) | [scales_hasMemberCase](../slots/scales_hasMemberCase.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | http___release.niem.gov_niem_domains_jxdm_7.2_Case | _:b999 | scales:/CaseCriminal | 5000 |
| None | scales_Case | _:b999 | scales:/CaseCriminal | 5000 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_Case
annotations:
  count:
    tag: count
    value: 5000
  http___release.niem.gov_niem_domains_jxdm_7.2_Case:
    tag: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    value: 5000
  scales_Case:
    tag: scales_Case
    value: 5000
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/CaseCriminal
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/Case
    example_subject: _:b999
    example_subject_type: None
- object:
    example_object: scales:/CaseCriminal
    example_object_type: scales_Case
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/Case
    example_subject: _:b999
    example_subject_type: None
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/Case
alias: http___release.niem.gov_niem_domains_jxdm_7.2_Case
range: Any
any_of:
- range: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- range: scales_Case

```
</details>