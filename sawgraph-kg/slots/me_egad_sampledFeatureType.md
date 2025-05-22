

# Slot: me_egad_sampledFeatureType


_No slot (predicate) description specified_






This slot occurs 8021 times.


URI: [me_egad:sampledFeatureType](http://sawgraph.spatialai.org/v1/me-egad#sampledFeatureType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-SampledFeature](../classes/MeEgadEGAD-SampledFeature.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SamplePointType](../classes/MeEgadEGAD-SamplePointType.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-SampledFeature | me_egad_EGAD-SamplePointType | me_egad_data:sampledFeature.100410 | me_egad_data:featureType.MW | 8021 |
| me_egad_EGAD-SampledFeature | owl_NamedIndividual | me_egad_data:sampledFeature.100410 | me_egad_data:featureType.MW | 8021 |




## LinkML Source

<details>

```yaml
name: me_egad_sampledFeatureType
annotations:
  count:
    tag: count
    value: 8021
description: No slot (predicate) description specified
examples:
- object:
    example_object: me_egad_data:featureType.MW
    example_object_type: me_egad_EGAD-SamplePointType
    example_predicate: me_egad:sampledFeatureType
    example_subject: me_egad_data:sampledFeature.100410
    example_subject_type: me_egad_EGAD-SampledFeature
- object:
    example_object: me_egad_data:featureType.MW
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:sampledFeatureType
    example_subject: me_egad_data:sampledFeature.100410
    example_subject_type: me_egad_EGAD-SampledFeature
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:sampledFeatureType
alias: me_egad_sampledFeatureType
domain_of:
- me_egad_EGAD-SampledFeature
range: Any
any_of:
- range: me_egad_EGAD-SamplePointType
- range: owl_NamedIndividual

```
</details>