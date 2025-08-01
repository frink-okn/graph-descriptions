

# Slot: scales_Firm


_No slot (predicate) description specified_






This slot occurs 2929549 times.


URI: [scales:Firm](http://schemas.scales-okn.org/rdf/scales#Firm)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Attorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Attorney.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney.md) | No class (type) description specified |  yes  |







## Properties

* Range: [ScalesFirm](../classes/ScalesFirm.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Attorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Attorney.md) | [ScalesFirm](../classes/ScalesFirm.md) | range | [ScalesFirm](../classes/ScalesFirm.md) |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefenseAttorney.md) | [ScalesFirm](../classes/ScalesFirm.md) | range | [ScalesFirm](../classes/ScalesFirm.md) |
| [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingAttorney.md) | [ScalesFirm](../classes/ScalesFirm.md) | range | [ScalesFirm](../classes/ScalesFirm.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney | scales_Firm | scales:/Agent/akd;;1:16-cr-00001_a3 | scales:/Agent/akd;;1:16-cr-00001_a7 | 1494159 |
| http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney | scales_Firm | scales:/Agent/akd;;1:16-cr-00001_a5 | scales:/Agent/akd;;1:16-cr-00001_a9 | 1365635 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Attorney | scales_Firm | scales:/Agent/akd;;1:16-cv-00008_a22 | scales:/Agent/akd;;1:16-cv-00008_a28 | 69755 |




## LinkML Source

<details>

```yaml
name: scales_Firm
annotations:
  count:
    tag: count
    value: 2929549
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Agent/akd;;1:16-cr-00001_a7
    example_object_type: scales_Firm
    example_predicate: scales:Firm
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a3
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- object:
    example_object: scales:/Agent/akd;;1:16-cr-00001_a9
    example_object_type: scales_Firm
    example_predicate: scales:Firm
    example_subject: scales:/Agent/akd;;1:16-cr-00001_a5
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
- object:
    example_object: scales:/Agent/akd;;1:16-cv-00008_a28
    example_object_type: scales_Firm
    example_predicate: scales:Firm
    example_subject: scales:/Agent/akd;;1:16-cv-00008_a22
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
from_schema: scales-kg
rank: 1000
slot_uri: scales:Firm
alias: scales_Firm
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Attorney
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseDefenseAttorney
- http___release.niem.gov_niem_domains_jxdm_7.2_CaseInitiatingAttorney
range: scales_Firm

```
</details>