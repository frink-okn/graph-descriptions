

# Slot: coso_analysisMethod


_No slot (predicate) description specified_






This slot occurs 577606 times.


URI: [coso:analysisMethod](http://w3id.org/coso/v1/contaminoso#analysisMethod)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-AnalysisMethod](../classes/MeEgadEGAD-AnalysisMethod.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-PFAS-Observation | me_egad_EGAD-AnalysisMethod | me_egad_data:observation.AAL210144001R.20210112.1763231 | me_egad_data:testMethod.E537M | 577606 |
| me_egad_EGAD-PFAS-Observation | owl_NamedIndividual | me_egad_data:observation.AAL210144001R.20210112.1763231 | me_egad_data:testMethod.E537M | 577606 |




## LinkML Source

<details>

```yaml
name: coso_analysisMethod
annotations:
  count:
    tag: count
    value: 577606
description: No slot (predicate) description specified
examples:
- object:
    example_object: me_egad_data:testMethod.E537M
    example_object_type: me_egad_EGAD-AnalysisMethod
    example_predicate: coso:analysisMethod
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
- object:
    example_object: me_egad_data:testMethod.E537M
    example_object_type: owl_NamedIndividual
    example_predicate: coso:analysisMethod
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
from_schema: sawgraph-kg
rank: 1000
slot_uri: coso:analysisMethod
alias: coso_analysisMethod
domain_of:
- me_egad_EGAD-PFAS-Observation
range: Any
any_of:
- range: me_egad_EGAD-AnalysisMethod
- range: owl_NamedIndividual

```
</details>