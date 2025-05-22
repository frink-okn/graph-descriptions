

# Slot: of substance (coso_ofSubstance)


_No slot (predicate) description specified_






This slot occurs 576763 times.


URI: [coso:ofSubstance](http://w3id.org/coso/v1/contaminoso#ofSubstance)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[B4df387098a2ec498fe4c9889d19680a0](../classes/B4df387098a2ec498fe4c9889d19680a0.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| me_egad_EGAD-PFAS-Observation | uri | me_egad_data:observation.AAL210144001R.20210112.1763231 | me_egad:parameter.PFOS_A | 576763 |




## LinkML Source

<details>

```yaml
name: coso_ofSubstance
annotations:
  count:
    tag: count
    value: 576763
description: No slot (predicate) description specified
title: of substance
examples:
- object:
    example_object: me_egad:parameter.PFOS_A
    example_object_type: uri
    example_predicate: coso:ofSubstance
    example_subject: me_egad_data:observation.AAL210144001R.20210112.1763231
    example_subject_type: me_egad_EGAD-PFAS-Observation
from_schema: sawgraph-kg
rank: 1000
domain: coso_ContaminantObservation
slot_uri: coso:ofSubstance
alias: coso_ofSubstance
domain_of:
- me_egad_EGAD-PFAS-Observation
range: Any
any_of:
- range: __B4df387098a2ec498fe4c9889d19680a0
- range: uri

```
</details>