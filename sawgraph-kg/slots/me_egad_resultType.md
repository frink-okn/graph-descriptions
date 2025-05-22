

# Slot: egad - result type (me_egad_resultType)


_No slot (predicate) description specified_






This slot occurs 576763 times.


URI: [me_egad:resultType](http://sawgraph.spatialai.org/v1/me-egad#resultType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ResultType](../classes/MeEgadEGAD-ResultType.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-PFAS-Observation | me_egad_EGAD-ResultType | me_egad_data:observation.AAL210144001R.20210112.1763231 | me_egad_data:resultType.TRG | 576763 |
| me_egad_EGAD-PFAS-Observation | owl_NamedIndividual | me_egad_data:observation.AAL210144001R.20210112.1763231 | me_egad_data:resultType.TRG | 576763 |




## LinkML Source

<details>

```yaml
name: me_egad_resultType
annotations:
  count:
    tag: count
    value: 576763
description: No slot (predicate) description specified
title: egad - result type
examples:
- object:
    example_object: me_egad_data:resultType.TRG
    example_object_type: me_egad_EGAD-ResultType
    example_predicate: me_egad:resultType
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
- object:
    example_object: me_egad_data:resultType.TRG
    example_object_type: owl_NamedIndividual
    example_predicate: me_egad:resultType
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
from_schema: sawgraph-kg
rank: 1000
slot_uri: me_egad:resultType
alias: me_egad_resultType
domain_of:
- me_egad_EGAD-PFAS-Observation
subproperty_of: coso_observationAnnotation
range: Any
any_of:
- range: me_egad_EGAD-ResultType
- range: owl_NamedIndividual

```
</details>