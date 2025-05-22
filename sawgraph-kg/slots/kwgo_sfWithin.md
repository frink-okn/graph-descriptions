

# Slot: kwgo_sfWithin


_No slot (predicate) description specified_






This slot occurs 10777 times.


URI: [kwgo:sfWithin](http://stko-kwg.geog.ucsb.edu/lod/ontology/sfWithin)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Site](../classes/MeEgadEGAD-Site.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-SamplePoint | kwgo_S2Cell_Level13 | me_egad_data:samplePoint.100410 | kwgr:s2.level13.5525380644965711872 | 4502 |
| me_egad_EGAD-SamplePoint | uri | me_egad_data:samplePoint.100410 | dcgeoid:2302778255 | 4509 |
| me_egad_EGAD-PFAS-Site | kwgo_S2Cell_Level13 | me_egad_data:site.100843 | kwgr:s2.level13.5525436170302914560 | 883 |
| me_egad_EGAD-Site | kwgo_S2Cell_Level13 | me_egad_data:site.100843 | kwgr:s2.level13.5525436170302914560 | 840 |
| me_egad_EGAD-Site | uri | me_egad_data:site.100843 | dcgeoid:2301902795 | 840 |
| me_egad_EGAD-PFAS-Site | uri | me_egad_data:site.131980 | dcgeoid:2300724775 | 43 |




## LinkML Source

<details>

```yaml
name: kwgo_sfWithin
annotations:
  count:
    tag: count
    value: 10777
description: No slot (predicate) description specified
examples:
- object:
    example_object: kwgr:s2.level13.5525380644965711872
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfWithin
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
- object:
    example_object: dcgeoid:2302778255
    example_object_type: uri
    example_predicate: kwgo:sfWithin
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
- object:
    example_object: kwgr:s2.level13.5525436170302914560
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfWithin
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-PFAS-Site
- object:
    example_object: kwgr:s2.level13.5525436170302914560
    example_object_type: kwgo_S2Cell_Level13
    example_predicate: kwgo:sfWithin
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-Site
- object:
    example_object: dcgeoid:2301902795
    example_object_type: uri
    example_predicate: kwgo:sfWithin
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-Site
- object:
    example_object: dcgeoid:2300724775
    example_object_type: uri
    example_predicate: kwgo:sfWithin
    example_subject: me_egad_data:site.131980
    example_subject_type: me_egad_EGAD-PFAS-Site
from_schema: sawgraph-kg
rank: 1000
slot_uri: kwgo:sfWithin
alias: kwgo_sfWithin
domain_of:
- me_egad_EGAD-PFAS-Site
- me_egad_EGAD-SamplePoint
- me_egad_EGAD-Site
range: Any
any_of:
- range: uri
- range: kwgo_S2Cell_Level13

```
</details>