

# Slot: scales_Party


_No slot (predicate) description specified_






This slot occurs 380643 times.


URI: [scales:Party](http://schemas.scales-okn.org/rdf/scales#Party)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [ScalesParty](../classes/ScalesParty.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseDefendantParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [ScalesParty](../classes/ScalesParty.md) | range | [ScalesParty](../classes/ScalesParty.md) |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | [HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2CaseInitiatingParty.md) | any_of[range] | [ScalesParty](../classes/ScalesParty.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CivilCase | scales_Party | scales:/CivilCase/akd;;1:16-cv-00008 | scales:/Agent/akd;;1:16-cv-00008_a7 | 360933 |
| scales_CriminalCase | scales_Party | scales:/CriminalCase/almd;;1:16-cr-00571 | scales:/Agent/almd;;1:16-cr-00571_a3 | 19710 |




## LinkML Source

<details>

```yaml
name: scales_Party
annotations:
  count:
    tag: count
    value: 380643
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/Agent/akd;;1:16-cv-00008_a7
    example_object_type: scales_Party
    example_predicate: scales:Party
    example_subject: scales:/CivilCase/akd;;1:16-cv-00008
    example_subject_type: scales_CivilCase
- object:
    example_object: scales:/Agent/almd;;1:16-cr-00571_a3
    example_object_type: scales_Party
    example_predicate: scales:Party
    example_subject: scales:/CriminalCase/almd;;1:16-cr-00571
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:Party
alias: scales_Party
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: scales_Party

```
</details>