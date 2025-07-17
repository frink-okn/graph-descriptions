

# Slot: scales_DocketTable


_No slot (predicate) description specified_






This slot occurs 3295006 times.


URI: [scales:DocketTable](http://schemas.scales-okn.org/rdf/scales#DocketTable)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |







## Properties

* Range: [HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2RegisterOfActions.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| scales_CriminalCase | http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions | scales:Case/ga-fulton-01-00-CR-244366 | scales:DocketTable/ga-fulton-01-00-CR-244366 | 2219202 |
| scales_CivilCase | http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions | scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001 | scales:DocketTable/ga-clayton-magistrate-civil;;0:00-cm-00001 | 1075804 |




## LinkML Source

<details>

```yaml
name: scales_DocketTable
annotations:
  count:
    tag: count
    value: 3295006
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:DocketTable/ga-fulton-01-00-CR-244366
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    example_predicate: scales:DocketTable
    example_subject: scales:Case/ga-fulton-01-00-CR-244366
    example_subject_type: scales_CriminalCase
- object:
    example_object: scales:DocketTable/ga-clayton-magistrate-civil;;0:00-cm-00001
    example_object_type: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions
    example_predicate: scales:DocketTable
    example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
    example_subject_type: scales_CivilCase
from_schema: scales-kg
rank: 1000
slot_uri: scales:DocketTable
alias: scales_DocketTable
domain_of:
- scales_CivilCase
- scales_CriminalCase
range: http___release.niem.gov_niem_domains_jxdm_7.2_RegisterOfActions

```
</details>