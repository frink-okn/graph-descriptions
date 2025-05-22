

# Slot: from sample point (coso_fromSamplePoint)


_No slot (predicate) description specified_






This slot occurs 23037 times.


URI: [coso:fromSamplePoint](http://w3id.org/coso/v1/contaminoso#fromSamplePoint)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[CosoSamplePoint](../classes/CosoSamplePoint.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-Sample | me_egad_EGAD-SamplePoint | me_egad_data:sample.AAL210144001R.20210112 | me_egad_data:samplePoint.146496 | 23037 |




## LinkML Source

<details>

```yaml
name: coso_fromSamplePoint
annotations:
  count:
    tag: count
    value: 23037
description: No slot (predicate) description specified
title: from sample point
examples:
- object:
    example_object: me_egad_data:samplePoint.146496
    example_object_type: me_egad_EGAD-SamplePoint
    example_predicate: coso:fromSamplePoint
    example_subject: me_egad_data:sample.AAL210144001R.20210112
    example_subject_type: me_egad_EGAD-Sample
from_schema: sawgraph-kg
rank: 1000
domain: coso_MaterialSample
slot_uri: coso:fromSamplePoint
alias: coso_fromSamplePoint
domain_of:
- me_egad_EGAD-Sample
range: Any
any_of:
- range: me_egad_EGAD-SamplePoint
- range: coso_SamplePoint

```
</details>