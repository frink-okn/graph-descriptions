

# Slot: scales_Party


_No slot (predicate) description specified_






This slot occurs 380621 times.


URI: [scales:Party](http://schemas.scales-okn.org/rdf/scales#Party)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [ScalesParty](../classes/ScalesParty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCase](../classes/ScalesCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCase](../classes/ScalesCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCase](../classes/ScalesCase.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_Case | scales_Party | scales:CivilCase | scales:Agent/akd;;1:16-cv-00008_a7 | 317772 |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | scales_Party | scales:CivilCase | scales:Agent/akd;;1:16-cv-00008_a7 | 317772 |
| scales_CivilCase | scales_Party | scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00017 | scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00017_a3 | 61431 |
| scales_CriminalCase | scales_Party | scales:Case/ga-clayton-state;;0:04-cr-02869 | scales:Agent/ga-clayton-state;;0:04-cr-02869_a2 | 1418 |




## LinkML Source

<details>

```yaml
name: scales_Party
annotations:
  count:
    tag: count
    value: 380621
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:Agent/akd;;1:16-cv-00008_a7
    example_object_type: scales_Party
    example_predicate: scales:Party
    example_subject: scales:CivilCase
    example_subject_type: scales_Case
- object:
    example_object: scales:Agent/akd;;1:16-cv-00008_a7
    example_object_type: scales_Party
    example_predicate: scales:Party
    example_subject: scales:CivilCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: scales:Agent/ga-clayton-magistrate-civil;;0:00-cm-00017_a3
    example_object_type: scales_Party
    example_predicate: scales:Party
    example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00017
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:Agent/ga-clayton-state;;0:04-cr-02869_a2
    example_object_type: scales_Party
    example_predicate: scales:Party
    example_subject: scales:Case/ga-clayton-state;;0:04-cr-02869
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:Party
alias: scales_Party
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
- scales_CivilCase
- scales_CriminalCase
range: scales_Party

```
</details>