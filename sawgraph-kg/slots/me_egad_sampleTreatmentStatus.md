

# Slot: egad - sample treatment status (me_egad_sampleTreatmentStatus)




This slot occurs 15610 times.


URI: [me_egad:sampleTreatmentStatus](http://sawgraph.spatialai.org/v1/me-egad#sampleTreatmentStatus)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleTreatmentStatus](../classes/MeEgadEGAD-SampleTreatmentStatus.md)&nbsp;or&nbsp;<br />[CosoSampleAnnotation](../classes/CosoSampleAnnotation.md)







## LinkML Source

<details>

```yaml
name: me_egad_sampleTreatmentStatus
title: egad - sample treatment status
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: me_egad:sampleTreatmentStatus
alias: me_egad_sampleTreatmentStatus
domain_of:
- me_egad_EGAD-Sample
subproperty_of: coso_sampleAnnotation
union_of:
- owl_Thing
- coso_MaterialSample
- sosa_Sample
range: Any
any_of:
- range: owl_Thing
- range: owl_NamedIndividual
- range: me_egad_EGAD-SampleTreatmentStatus
- range: coso_SampleAnnotation

```
</details>