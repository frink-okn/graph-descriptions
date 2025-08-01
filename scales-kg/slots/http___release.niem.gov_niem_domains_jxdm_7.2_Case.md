

# Slot: http___release.niem.gov_niem_domains_jxdm_7.2_Case


_No slot (predicate) description specified_






This slot occurs 864700 times.


URI: [http://release.niem.gov/niem/domains/jxdm/7.2/Case](http://release.niem.gov/niem/domains/jxdm/7.2/Case)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ScalesCivilCase](../classes/ScalesCivilCase.md)&nbsp;or&nbsp;<br />[ScalesCriminalCase](../classes/ScalesCriminalCase.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| None | scales_CivilCase | _:@0 | scales:/CivilCase/almd;;2:16-cv-00274 | 718739 |
| None | scales_CriminalCase | _:@0 | scales:/CriminalCase/ared;;4:16-cr-00286 | 145961 |




## LinkML Source

<details>

```yaml
name: http___release.niem.gov_niem_domains_jxdm_7.2_Case
annotations:
  count:
    tag: count
    value: 864700
  scales_CivilCase:
    tag: scales_CivilCase
    value: 718739
  scales_CriminalCase:
    tag: scales_CriminalCase
    value: 145961
description: No slot (predicate) description specified
examples:
- object:
    example_object: scales:/CivilCase/almd;;2:16-cv-00274
    example_object_type: scales_CivilCase
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/Case
    example_subject: _:@0
    example_subject_type: None
- object:
    example_object: scales:/CriminalCase/ared;;4:16-cr-00286
    example_object_type: scales_CriminalCase
    example_predicate: http://release.niem.gov/niem/domains/jxdm/7.2/Case
    example_subject: _:@0
    example_subject_type: None
from_schema: scales-kg
rank: 1000
slot_uri: http://release.niem.gov/niem/domains/jxdm/7.2/Case
alias: http___release.niem.gov_niem_domains_jxdm_7.2_Case
range: Any
any_of:
- range: scales_CivilCase
- range: scales_CriminalCase

```
</details>