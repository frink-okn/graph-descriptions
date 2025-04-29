

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction


_No slot (predicate) description specified_






This slot occurs 182022 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction](http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) |
| [ScalesCase](../classes/ScalesCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md) | any_of[range] | [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction | uri | scales:/DocketTable/casd;;3:16-cv-01644 | scales:/DocketEntry/casd;;3:16-cv-01644_de0 | 182022 |
| http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions | uri | scales:/DocketTable/casd;;3:16-cv-01644 | scales:/DocketEntry/casd;;3:16-cv-01644_de0 | 182022 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
annotations:
  count:
    tag: count
    value: 182022
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/DocketEntry/casd;;3:16-cv-01644_de0
    example_object_type: uri
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction
    example_subject: scales:/DocketTable/casd;;3:16-cv-01644
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
- object:
    example_object: scales:/DocketEntry/casd;;3:16-cv-01644_de0
    example_object_type: uri
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction
    example_subject: scales:/DocketTable/casd;;3:16-cv-01644
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/RegisterAction
alias: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
- http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
range: uri

```
</details>