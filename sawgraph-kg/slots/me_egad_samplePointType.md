

# Slot: egad - sample point type (me_egad_samplePointType)


_No slot (predicate) description specified_






This slot occurs 16345 times.


URI: [me_egad:samplePointType](http://sawgraph.spatialai.org/v1/me-egad#samplePointType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SamplePointType](../classes/MeEgadEGAD-SamplePointType.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-SamplePoint | me_egad_EGAD-SamplePointType | me_egad_data:samplePoint.100410 | me_egad_data:featureType.MW | 8021 |
| me_egad_EGAD-SamplePoint | owl_NamedIndividual | me_egad_data:samplePoint.100410 | me_egad_data:featureType.MW | 8021 |
| me_egad_EGAD-SamplePoint | uri | me_egad_data:samplePoint.100410 | me_egad:featureType.MW | 8324 |




## LinkML Source

<details>

```yaml
name: me_egad_samplePointType
annotations:
  count:
    tag: count
    value: 16345
description: No slot (predicate) description specified
title: egad - sample point type
examples:
- object:
    example_object: me_egad_data:featureType.MW
    example_object_type: me_egad_EGAD-SamplePointType
    example_predicate: me_egad:samplePointType
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
- object:
    example_object: me_egad_data:featureType.MW
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:samplePointType
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
- object:
    example_object: me_egad:featureType.MW
    example_object_type: uri
    example_predicate: me_egad:samplePointType
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:samplePointType
alias: me_egad_samplePointType
domain_of:
- me_egad_EGAD-SamplePoint
range: Any
any_of:
- range: me_egad_EGAD-SamplePointType
- range: uri
- range: owl_NamedIndividual

```
</details>