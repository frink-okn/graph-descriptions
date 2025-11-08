

# Slot: has result (coso_hasResult)


_A relation between an observation of a contaminant and the measurement that is the result of the observation._






This slot occurs 1282200 times.


URI: [coso:hasResult](http://w3id.org/coso/v1/contaminoso#hasResult)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Us-wqp#Single-PFAS-Concentration.md)&nbsp;or&nbsp;<br />[SosaResult](../classes/SosaResult.md)&nbsp;or&nbsp;<br />[CosoContaminantMeasurement](../classes/CosoContaminantMeasurement.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[QudtQuantifiable](../classes/QudtQuantifiable.md)&nbsp;or&nbsp;<br />[QudtQuantity](../classes/QudtQuantity.md)&nbsp;or&nbsp;<br />[QudtConcept](../classes/QudtConcept.md)&nbsp;or&nbsp;<br />[StadDatapoint](../classes/StadDatapoint.md)







## LinkML Source

<details>

```yaml
name: coso_hasResult
description: A relation between an observation of a contaminant and the measurement
  that is the result of the observation.
title: has result
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:hasResult
alias: coso_hasResult
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- http___w3id.org_sawgraph_v1_us-wqp#Observation
- me_egad_EGAD-PFAS-Observation
subproperty_of: sosa_hasResult
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
- range: me_egad_EGAD-SinglePFAS-Concentration
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
- range: me_egad_EGAD-AggregatePFAS-Concentration
- range: http___w3id.org_sawgraph_v1_us-wqp#Single-PFAS-Concentration
- range: sosa_Result
- range: coso_ContaminantMeasurement
- range: owl_Thing
- range: qudt_Quantifiable
- range: qudt_Quantity
- range: qudt_Concept
- range: stad_Datapoint

```
</details>