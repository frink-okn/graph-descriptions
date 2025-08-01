

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence


_No slot (predicate) description specified_






This slot occurs 675670 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/Sentence](http://release.niem.gov/niem/domains/jxdm/7.2/Sentence)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) | No class (type) description specified |  yes  |
| [ScalesParty](../classes/ScalesParty.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2Sentence](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Sentence.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | [http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSentence](../slots/http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSentence.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2Sentence](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Sentence.md) |
| [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterAction.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2Sentence](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Sentence.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2Sentence](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Sentence.md) |
| [ScalesParty](../classes/ScalesParty.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2Sentence](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Sentence.md) | range | [HttpRelease.niem.govNiemDomainsJxdm7.2Sentence](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Sentence.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_Party | http___release.niem.gov_niem_domains_jxdm_7.2_Sentence | scales:Agent/ga-clayton-state;;0:00-cr-01074_a1 | scales:Sentence/ga-clayton-state;;0:00-cr-01074_de32_s0 | 319576 |
| http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction | http___release.niem.gov_niem_domains_jxdm_7.2_Sentence | scales:DocketEntry/ga-clayton-state;;0:00-cr-00001_de10 | scales:Sentence/ga-clayton-state;;0:00-cr-00001_de10_s0 | 356094 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
annotations:
  count:
    tag: count
    value: 675670
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Sentence/ga-clayton-state;;0:00-cr-01074_de32_s0
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/Sentence
    example_subject: scales:Agent/ga-clayton-state;;0:00-cr-01074_a1
    example_subject_type: scales_Party
- object:
    example_object: scales:Sentence/ga-clayton-state;;0:00-cr-00001_de10_s0
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/Sentence
    example_subject: scales:DocketEntry/ga-clayton-state;;0:00-cr-00001_de10
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/Sentence
alias: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_RegisterAction
- scales_Party
range: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence

```
</details>