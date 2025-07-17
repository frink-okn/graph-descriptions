

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSentence


_No slot (predicate) description specified_






This slot occurs 244007 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSentence](http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSentence)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Charge](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Charge.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2Sentence](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Sentence.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Charge | http___release.niem.gov_niem_domains_jxdm_7.2_Sentence | scales:Charge/ga-clayton-state;;0:00-cr-01074_c1 | scales:Sentence/ga-clayton-state;;0:00-cr-01074_de32_s0 | 66752 |
| None | http___release.niem.gov_niem_domains_jxdm_7.2_Sentence | scales:Charge/ga-clayton-state;;0:00-cr-01074_c2 | scales:Sentence/ga-clayton-state;;0:00-cr-01074_de34_s0 | 177255 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSentence
annotations:
  count:
    tag: count
    value: 244007
  http___release.niem.gov_niem_domains_jxdm_7.2_Sentence:
    tag: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
    value: 177255
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Sentence/ga-clayton-state;;0:00-cr-01074_de32_s0
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSentence
    example_subject: scales:Charge/ga-clayton-state;;0:00-cr-01074_c1
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Charge
- object:
    example_object: scales:Sentence/ga-clayton-state;;0:00-cr-01074_de34_s0
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSentence
    example_subject: scales:Charge/ga-clayton-state;;0:00-cr-01074_c2
    example_subject_type: None
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/ChargeSentence
alias: http___release.niem.gov_niem_domains_jxdm_7.2_ChargeSentence
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Charge
range: http___release.niem.gov_niem_domains_jxdm_7.2_Sentence

```
</details>