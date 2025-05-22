

# Slot: egad - sample collection method (me_egad_sampleCollectionMethod)


_No slot (predicate) description specified_






This slot occurs 22690 times.


URI: [me_egad:sampleCollectionMethod](http://sawgraph.spatialai.org/v1/me-egad#sampleCollectionMethod)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleCollectionMethod](../classes/MeEgadEGAD-SampleCollectionMethod.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-Sample | me_egad_EGAD-SampleCollectionMethod | me_egad_data:sample.AAL210144001R.20210112 | me_egad_data:samplingMethod.GS | 22690 |
| me_egad_EGAD-Sample | owl_NamedIndividual | me_egad_data:sample.AAL210144001R.20210112 | me_egad_data:samplingMethod.GS | 22690 |




## LinkML Source

<details>

```yaml
name: me_egad_sampleCollectionMethod
annotations:
  count:
    tag: count
    value: 22690
description: No slot (predicate) description specified
title: egad - sample collection method
examples:
- object:
    example_object: me_egad_data:samplingMethod.GS
    example_object_type: me_egad_EGAD-SampleCollectionMethod
    example_predicate: me_egad:sampleCollectionMethod
    example_subject: me_egad_data:sample.AAL210144001R.20210112
    example_subject_type: me_egad_EGAD-Sample
- object:
    example_object: me_egad_data:samplingMethod.GS
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:sampleCollectionMethod
    example_subject: me_egad_data:sample.AAL210144001R.20210112
    example_subject_type: me_egad_EGAD-Sample
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:sampleCollectionMethod
alias: me_egad_sampleCollectionMethod
domain_of:
- me_egad_EGAD-Sample
subproperty_of: coso_sampleAnnotation
range: Any
any_of:
- range: me_egad_EGAD-SampleCollectionMethod
- range: owl_NamedIndividual

```
</details>