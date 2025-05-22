

# Slot: kwgo_sfContains


_No slot (predicate) description specified_






This slot occurs 10777 times.


URI: [kwgo:sfContains](http://stko-kwg.geog.ucsb.edu/lod/ontology/sfContains)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-Site](../classes/MeEgadEGAD-Site.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| kwgo_S2Cell_Level13 | me_egad_EGAD-SamplePoint | kwgr:s2.level13.5522341972783661056 | me_egad_data:samplePoint.148241 | 4502 |
| kwgo_S2Cell_Level13 | me_egad_EGAD-PFAS-Site | kwgr:s2.level13.5522342797417381888 | me_egad_data:site.32387 | 883 |
| kwgo_S2Cell_Level13 | me_egad_EGAD-Site | kwgr:s2.level13.5522349016530026496 | me_egad_data:site.32386 | 840 |
| None | me_egad_EGAD-SamplePoint | kwgr:s2.level13.9801268321847345152 | me_egad_data:samplePoint.136911 | 4509 |
| None | me_egad_EGAD-PFAS-Site | kwgr:s2.level13.9935758178975219712 | me_egad_data:site.47292 | 883 |
| None | me_egad_EGAD-Site | kwgr:s2.level13.9935758178975219712 | me_egad_data:site.47292 | 840 |




## LinkML Source

<details>

```yaml
name: kwgo_sfContains
annotations:
  count:
    tag: count
    value: 10777
  me_egad_EGAD-PFAS-Site:
    tag: me_egad_EGAD-PFAS-Site
    value: 883
  me_egad_EGAD-SamplePoint:
    tag: me_egad_EGAD-SamplePoint
    value: 4509
  me_egad_EGAD-Site:
    tag: me_egad_EGAD-Site
    value: 840
description: No slot (predicate) description specified
examples:
- object:
    example_object: me_egad_data:samplePoint.148241
    example_object_type: me_egad_EGAD-SamplePoint
    example_predicate: kwgo:sfContains
    example_subject: kwgr:s2.level13.5522341972783661056
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: me_egad_data:site.32387
    example_object_type: me_egad_EGAD-PFAS-Site
    example_predicate: kwgo:sfContains
    example_subject: kwgr:s2.level13.5522342797417381888
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: me_egad_data:site.32386
    example_object_type: me_egad_EGAD-Site
    example_predicate: kwgo:sfContains
    example_subject: kwgr:s2.level13.5522349016530026496
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: me_egad_data:samplePoint.136911
    example_object_type: me_egad_EGAD-SamplePoint
    example_predicate: kwgo:sfContains
    example_subject: kwgr:s2.level13.9801268321847345152
    example_subject_type: None
- object:
    example_object: me_egad_data:site.47292
    example_object_type: me_egad_EGAD-PFAS-Site
    example_predicate: kwgo:sfContains
    example_subject: kwgr:s2.level13.9935758178975219712
    example_subject_type: None
- object:
    example_object: me_egad_data:site.47292
    example_object_type: me_egad_EGAD-Site
    example_predicate: kwgo:sfContains
    example_subject: kwgr:s2.level13.9935758178975219712
    example_subject_type: None
from_schema: sawgraph-kg
rank: 1000
slot_uri: kwgo:sfContains
alias: kwgo_sfContains
domain_of:
- kwgo_S2Cell_Level13
range: Any
any_of:
- range: me_egad_EGAD-PFAS-Site
- range: me_egad_EGAD-SamplePoint
- range: me_egad_EGAD-Site

```
</details>