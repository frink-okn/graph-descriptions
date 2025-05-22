

# Slot: observed at sample point (coso_observedAtSamplePoint)


_No slot (predicate) description specified_






This slot occurs 577112 times.


URI: [coso:observedAtSamplePoint](http://w3id.org/coso/v1/contaminoso#observedAtSamplePoint)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[CosoSamplePoint](../classes/CosoSamplePoint.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-PFAS-Observation | me_egad_EGAD-SamplePoint | me_egad_data:observation.AAL210144001R.20210112.1763231 | me_egad_data:samplePoint.146496 | 577112 |




## LinkML Source

<details>

```yaml
name: coso_observedAtSamplePoint
annotations:
  count:
    tag: count
    value: 577112
description: No slot (predicate) description specified
title: observed at sample point
examples:
- object:
    example_object: me_egad_data:samplePoint.146496
    example_object_type: me_egad_EGAD-SamplePoint
    example_predicate: coso:observedAtSamplePoint
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
from_schema: sawgraph-kg
rank: 1000
domain: coso_ContaminantSampleObservation
slot_uri: coso:observedAtSamplePoint
alias: coso_observedAtSamplePoint
domain_of:
- me_egad_EGAD-PFAS-Observation
subproperty_of: coso_observedAtPoint
range: Any
any_of:
- range: me_egad_EGAD-SamplePoint
- range: coso_SamplePoint

```
</details>