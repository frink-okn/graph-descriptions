

# Slot: egad - sample treatment status (me_egad_sampleTreatmentStatus)


_No slot (predicate) description specified_






This slot occurs 15610 times.


URI: [me_egad:sampleTreatmentStatus](http://sawgraph.spatialai.org/v1/me-egad#sampleTreatmentStatus)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleTreatmentStatus](../classes/MeEgadEGAD-SampleTreatmentStatus.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-Sample | me_egad_EGAD-SampleTreatmentStatus | me_egad_data:sample.AAL217134101.20211228 | me_egad_data:treatmentStatus.N | 15610 |
| me_egad_EGAD-Sample | owl_NamedIndividual | me_egad_data:sample.AAL217134101.20211228 | me_egad_data:treatmentStatus.N | 15610 |




## LinkML Source

<details>

```yaml
name: me_egad_sampleTreatmentStatus
annotations:
  count:
    tag: count
    value: 15610
description: No slot (predicate) description specified
title: egad - sample treatment status
examples:
- object:
    example_object: me_egad_data:treatmentStatus.N
    example_object_type: me_egad_EGAD-SampleTreatmentStatus
    example_predicate: me_egad:sampleTreatmentStatus
    example_subject: me_egad_data:sample.AAL217134101.20211228
    example_subject_type: me_egad_EGAD-Sample
- object:
    example_object: me_egad_data:treatmentStatus.N
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:sampleTreatmentStatus
    example_subject: me_egad_data:sample.AAL217134101.20211228
    example_subject_type: me_egad_EGAD-Sample
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:sampleTreatmentStatus
alias: me_egad_sampleTreatmentStatus
domain_of:
- me_egad_EGAD-Sample
subproperty_of: coso_sampleAnnotation
range: Any
any_of:
- range: me_egad_EGAD-SampleTreatmentStatus
- range: owl_NamedIndividual

```
</details>