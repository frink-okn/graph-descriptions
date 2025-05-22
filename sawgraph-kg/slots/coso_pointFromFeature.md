

# Slot: point from feature (coso_pointFromFeature)


_No slot (predicate) description specified_






This slot occurs 8040 times.


URI: [coso:pointFromFeature](http://w3id.org/coso/v1/contaminoso#pointFromFeature)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampledFeature](../classes/MeEgadEGAD-SampledFeature.md)&nbsp;or&nbsp;<br />[CosoFeature](../classes/CosoFeature.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-SamplePoint | me_egad_EGAD-SampledFeature | me_egad_data:samplePoint.100410 | me_egad_data:sampledFeature.100410 | 8040 |




## LinkML Source

<details>

```yaml
name: coso_pointFromFeature
annotations:
  count:
    tag: count
    value: 8040
description: No slot (predicate) description specified
title: point from feature
examples:
- object:
    example_object: me_egad_data:sampledFeature.100410
    example_object_type: me_egad_EGAD-SampledFeature
    example_predicate: coso:pointFromFeature
    example_subject: me_egad_data:samplePoint.100410
    example_subject_type: me_egad_EGAD-SamplePoint
from_schema: sawgraph-kg
rank: 1000
domain: coso_Point
slot_uri: coso:pointFromFeature
alias: coso_pointFromFeature
domain_of:
- me_egad_EGAD-SamplePoint
range: Any
any_of:
- range: me_egad_EGAD-SampledFeature
- range: coso_Feature

```
</details>