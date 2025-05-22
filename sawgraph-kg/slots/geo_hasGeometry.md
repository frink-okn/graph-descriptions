

# Slot: geo_hasGeometry


_No slot (predicate) description specified_






This slot occurs 6236 times.


URI: [geo:hasGeometry](http://www.opengis.net/ont/geosparql#hasGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Site](../classes/MeEgadEGAD-Site.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) | No class (type) description specified |  yes  |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[GeoGeometry](../classes/GeoGeometry.md)&nbsp;or&nbsp;<br />[Sf#Point](../classes/Sf#Point.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-SamplePoint | geo_Geometry | me_egad_data:samplePoint.100410 | me_egad_data:samplePoint.geometry.100410 | 4511 |
| me_egad_EGAD-SamplePoint | sf_#Point | me_egad_data:samplePoint.100410 | me_egad_data:samplePoint.geometry.100410 | 4511 |
| me_egad_EGAD-PFAS-Site | geo_Geometry | me_egad_data:site.100843 | me_egad_data:egad.site.geometry.100843 | 1725 |
| me_egad_EGAD-PFAS-Site | sf_#Point | me_egad_data:site.100843 | me_egad_data:egad.site.geometry.100843 | 1725 |
| me_egad_EGAD-Site | geo_Geometry | me_egad_data:site.100843 | me_egad_data:egad.site.geometry.100843 | 1682 |
| me_egad_EGAD-Site | sf_#Point | me_egad_data:site.100843 | me_egad_data:egad.site.geometry.100843 | 1682 |




## LinkML Source

<details>

```yaml
name: geo_hasGeometry
annotations:
  count:
    tag: count
    value: 6236
description: No slot (predicate) description specified
examples:
- object:
    example_object: me_egad_data:samplePoint.geometry.100410
    example_object_type: geo_Geometry
    example_predicate: geo:hasGeometry
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
- object:
    example_object: me_egad_data:samplePoint.geometry.100410
    example_object_type: sf_#Point
    example_predicate: geo:hasGeometry
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
- object:
    example_object: me_egad_data:egad.site.geometry.100843
    example_object_type: geo_Geometry
    example_predicate: geo:hasGeometry
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-PFAS-Site
- object:
    example_object: me_egad_data:egad.site.geometry.100843
    example_object_type: sf_#Point
    example_predicate: geo:hasGeometry
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-PFAS-Site
- object:
    example_object: me_egad_data:egad.site.geometry.100843
    example_object_type: geo_Geometry
    example_predicate: geo:hasGeometry
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-Site
- object:
    example_object: me_egad_data:egad.site.geometry.100843
    example_object_type: sf_#Point
    example_predicate: geo:hasGeometry
    example_subject: me_egad_data:site.100843
    example_subject_type: me_egad_EGAD-Site
from_schema: sawgraph-kg
rank: 1000
slot_uri: geo:hasGeometry
alias: geo_hasGeometry
domain_of:
- me_egad_EGAD-PFAS-Site
- me_egad_EGAD-SamplePoint
- me_egad_EGAD-Site
range: Any
any_of:
- range: geo_Geometry
- range: sf_#Point

```
</details>