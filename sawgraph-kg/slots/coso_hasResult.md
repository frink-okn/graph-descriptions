

# Slot: has result (coso_hasResult)


_No slot (predicate) description specified_






This slot occurs 576763 times.


URI: [coso:hasResult](http://w3id.org/coso/v1/contaminoso#hasResult)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md)&nbsp;or&nbsp;<br />[CosoContaminantMeasurement](../classes/CosoContaminantMeasurement.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-PFAS-Observation | me_egad_EGAD-SinglePFAS-Concentration | me_egad_data:observation.AAL210144001R.20210112.1763231 | me_egad_data:result.L210144001R.AA.20210112.1763231 | 539086 |
| me_egad_EGAD-PFAS-Observation | me_egad_EGAD-AggregatePFAS-Concentration | me_egad_data:observation.AAL210144001R.20210112.DEP18010 | me_egad_data:result.L210144001R.AA.20210112.DEP18010 | 37677 |




## LinkML Source

<details>

```yaml
name: coso_hasResult
annotations:
  count:
    tag: count
    value: 576763
description: No slot (predicate) description specified
title: has result
examples:
- object:
    example_object: me_egad_data:result.L210144001R.AA.20210112.1763231
    example_object_type: me_egad_EGAD-SinglePFAS-Concentration
    example_predicate: coso:hasResult
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
- object:
    example_object: me_egad_data:result.L210144001R.AA.20210112.DEP18010
    example_object_type: me_egad_EGAD-AggregatePFAS-Concentration
    example_predicate: coso:hasResult
    example_subject: me_egad_data:observation.AAL210144001R.20210112.DEP18010
    example_subject_type: me_egad_EGAD-PFAS-Observation
from_schema: sawgraph-kg
rank: 1000
domain: coso_ContaminantObservation
slot_uri: coso:hasResult
alias: coso_hasResult
domain_of:
- me_egad_EGAD-PFAS-Observation
subproperty_of: sosa_hasResult
range: Any
any_of:
- range: me_egad_EGAD-SinglePFAS-Concentration
- range: me_egad_EGAD-AggregatePFAS-Concentration
- range: coso_ContaminantMeasurement

```
</details>