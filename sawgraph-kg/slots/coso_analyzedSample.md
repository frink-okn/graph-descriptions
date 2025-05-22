

# Slot: analyzed sample (coso_analyzedSample)


_No slot (predicate) description specified_






This slot occurs 576763 times.


URI: [coso:analyzedSample](http://w3id.org/coso/v1/contaminoso#analyzedSample)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[CosoMaterialSample](../classes/CosoMaterialSample.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-PFAS-Observation | me_egad_EGAD-Sample | me_egad_data:observation.AAL210144001R.20210112.1763231 | me_egad_data:sample.AAL210144001R.20210112 | 576763 |




## LinkML Source

<details>

```yaml
name: coso_analyzedSample
annotations:
  count:
    tag: count
    value: 576763
description: No slot (predicate) description specified
title: analyzed sample
examples:
- object:
    example_object: me_egad_data:sample.AAL210144001R.20210112
    example_object_type: me_egad_EGAD-Sample
    example_predicate: coso:analyzedSample
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
from_schema: sawgraph-kg
rank: 1000
domain: coso_ContaminantSampleObservation
slot_uri: coso:analyzedSample
alias: coso_analyzedSample
domain_of:
- me_egad_EGAD-PFAS-Observation
subproperty_of: coso_hasAnyFeatureOfInterest
range: Any
any_of:
- range: coso_MaterialSample
- range: me_egad_EGAD-Sample

```
</details>