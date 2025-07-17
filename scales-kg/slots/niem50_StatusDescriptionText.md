

# Slot: niem50_StatusDescriptionText


_No slot (predicate) description specified_






This slot occurs 3206999 times.


URI: [niem50:StatusDescriptionText](http://release.niem.gov/niem/niem-core/5.0/StatusDescriptionText)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCriminalCase](../classes/ScalesCriminalCase.md) | No class (type) description specified |  yes  |
| [HttpRelease.niem.govNiemDomainsJxdm7.2Case](../classes/HttpRelease.niem.govNiemDomainsJxdm7.2Case.md) | No class (type) description specified |  yes  |
| [ScalesCivilCase](../classes/ScalesCivilCase.md) | No class (type) description specified |  yes  |
| [ScalesCase](../classes/ScalesCase.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| http___release.niem.gov_niem_domains_jxdm_7.2_Case | string | scales:CivilCase | closed | 4 |
| scales_CivilCase | string | scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001 | closed | 1075809 |
| scales_CriminalCase | string | scales:Case/ga-clayton-magistrate;;0:00-bc-00001 | other | 2131186 |




## LinkML Source

<details>

```yaml
name: niem50_StatusDescriptionText
annotations:
  count:
    tag: count
    value: 3206999
description: No slot (predicate) description specified
examples:
- object:
    example_object: closed
    example_object_type: string
    example_predicate: niem50:StatusDescriptionText
    example_subject: scales:CivilCase
    example_subject_type: http___release.niem.gov_niem_domains_jxdm_7.2_Case
- object:
    example_object: closed
    example_object_type: string
    example_predicate: niem50:StatusDescriptionText
    example_subject: scales:Case/ga-clayton-magistrate-civil;;0:00-cm-00001
    example_subject_type: scales_CivilCase
- object:
    example_object: other
    example_object_type: string
    example_predicate: niem50:StatusDescriptionText
    example_subject: scales:Case/ga-clayton-magistrate;;0:00-bc-00001
    example_subject_type: scales_CriminalCase
from_schema: scales-kg
rank: 1000
slot_uri: niem50:StatusDescriptionText
alias: niem50_StatusDescriptionText
domain_of:
- http___release.niem.gov_niem_domains_jxdm_7.2_Case
- scales_Case
- scales_CivilCase
- scales_CriminalCase
range: string

```
</details>