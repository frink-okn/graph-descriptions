

# Slot: egad - associated site (me_egad_associatedSite)


_No slot (predicate) description specified_






This slot occurs 8405 times.


URI: [me_egad:associatedSite](http://sawgraph.spatialai.org/v1/me-egad#associatedSite)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-Site](../classes/MeEgadEGAD-Site.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-SamplePoint | me_egad_EGAD-PFAS-Site | me_egad_data:samplePoint.100410 | me_egad_data:site.29410 | 8405 |
| me_egad_EGAD-SamplePoint | me_egad_EGAD-Site | me_egad_data:samplePoint.100410 | me_egad_data:site.29410 | 8208 |




## LinkML Source

<details>

```yaml
name: me_egad_associatedSite
annotations:
  count:
    tag: count
    value: 8405
description: No slot (predicate) description specified
title: egad - associated site
examples:
- object:
    example_object: me_egad_data:site.29410
    example_object_type: me_egad_EGAD-PFAS-Site
    example_predicate: me_egad:associatedSite
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
- object:
    example_object: me_egad_data:site.29410
    example_object_type: me_egad_EGAD-Site
    example_predicate: me_egad:associatedSite
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:associatedSite
alias: me_egad_associatedSite
domain_of:
- me_egad_EGAD-SamplePoint
range: Any
any_of:
- range: me_egad_EGAD-PFAS-Site
- range: me_egad_EGAD-Site

```
</details>