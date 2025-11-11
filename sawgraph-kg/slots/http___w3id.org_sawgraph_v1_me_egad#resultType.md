

# Slot: egad - result type (http___w3id.org_sawgraph_v1_me-egad#resultType)




This slot occurs 576763 times.


URI: [http://w3id.org/sawgraph/v1/me-egad#resultType](http://w3id.org/sawgraph/v1/me-egad#resultType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ResultType.md)&nbsp;or&nbsp;<br />[CosoObservationAnnotation](../classes/CosoObservationAnnotation.md)







## LinkML Source

<details>

```yaml
name: http___w3id.org_sawgraph_v1_me-egad#resultType
title: egad - result type
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: http://w3id.org/sawgraph/v1/me-egad#resultType
alias: http___w3id.org_sawgraph_v1_me_egad#resultType
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
subproperty_of: coso_observationAnnotation
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: owl_Thing
- range: owl_NamedIndividual
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ResultType
- range: coso_ObservationAnnotation

```
</details>