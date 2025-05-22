

# Slot: observed time (coso_observedTime)


_No slot (predicate) description specified_






This slot occurs 576799 times.


URI: [coso:observedTime](http://w3id.org/coso/v1/contaminoso#observedTime)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-PFAS-Observation | date | me_egad_data:observation.AAL210144001R.20210112.1763231 | 2021-01-12 | 576799 |




## LinkML Source

<details>

```yaml
name: coso_observedTime
annotations:
  count:
    tag: count
    value: 576799
description: No slot (predicate) description specified
title: observed time
examples:
- object:
    example_object: '2021-01-12'
    example_object_type: date
    example_predicate: coso:observedTime
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
from_schema: sawgraph-kg
rank: 1000
domain: coso_ContaminantObservation
slot_uri: coso:observedTime
alias: coso_observedTime
domain_of:
- me_egad_EGAD-PFAS-Observation
range: date

```
</details>