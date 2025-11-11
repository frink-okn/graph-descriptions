

# Slot: observation annotation (coso_observationAnnotation)


_A relation between an observation of a contaminant and additional metadata about the observation._






This slot occurs 1153526 times.


URI: [coso:observationAnnotation](http://w3id.org/coso/v1/contaminoso#observationAnnotation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[CosoObservationAnnotation](../classes/CosoObservationAnnotation.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ResultType](../classes/MeEgadEGAD-ResultType.md)







## LinkML Source

<details>

```yaml
name: coso_observationAnnotation
description: A relation between an observation of a contaminant and additional metadata
  about the observation.
title: observation annotation
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:observationAnnotation
alias: coso_observationAnnotation
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- me_egad_EGAD-PFAS-Observation
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: owl_NamedIndividual
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ResultType
- range: owl_Thing
- range: coso_ObservationAnnotation
- range: me_egad_EGAD-ResultType

```
</details>