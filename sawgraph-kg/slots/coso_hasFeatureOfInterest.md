

# Slot: has feature of interest (coso_hasFeatureOfInterest)


_No slot (predicate) description specified_






This slot occurs 577112 times.


URI: [coso:hasFeatureOfInterest](http://w3id.org/coso/v1/contaminoso#hasFeatureOfInterest)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampledFeature](../classes/MeEgadEGAD-SampledFeature.md)&nbsp;or&nbsp;<br />[CosoFeature](../classes/CosoFeature.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-PFAS-Observation | me_egad_EGAD-SampledFeature | me_egad_data:observation.AAL210144001R.20210112.1763231 | me_egad_data:sampledFeature.146496 | 577112 |




## LinkML Source

<details>

```yaml
name: coso_hasFeatureOfInterest
annotations:
  count:
    tag: count
    value: 577112
description: No slot (predicate) description specified
title: has feature of interest
examples:
- object:
    example_object: me_egad_data:sampledFeature.146496
    example_object_type: me_egad_EGAD-SampledFeature
    example_predicate: coso:hasFeatureOfInterest
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
from_schema: sawgraph-kg
rank: 1000
slot_uri: coso:hasFeatureOfInterest
alias: coso_hasFeatureOfInterest
domain_of:
- me_egad_EGAD-PFAS-Observation
subproperty_of: coso_hasAnyFeatureOfInterest
range: Any
any_of:
- range: me_egad_EGAD-SampledFeature
- range: coso_Feature

```
</details>