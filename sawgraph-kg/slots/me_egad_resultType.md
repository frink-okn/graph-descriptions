

# Slot: egad - result type (me_egad_resultType)




This slot occurs 576763 times.


URI: [me_egad:resultType](http://sawgraph.spatialai.org/v1/me-egad#resultType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ResultType](../classes/MeEgadEGAD-ResultType.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[CosoObservationAnnotation](../classes/CosoObservationAnnotation.md)







## LinkML Source

<details>

```yaml
name: me_egad_resultType
title: egad - result type
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: me_egad:resultType
alias: me_egad_resultType
domain_of:
- me_egad_EGAD-PFAS-Observation
subproperty_of: coso_observationAnnotation
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: me_egad_EGAD-ResultType
- range: owl_Thing
- range: owl_NamedIndividual
- range: coso_ObservationAnnotation

```
</details>