

# Slot: observed time (coso_observedTime)


_The time at which the contaminant was observed in the environment._






This slot occurs 1282272 times.


URI: [coso:observedTime](http://w3id.org/coso/v1/contaminoso#observedTime)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime)







## LinkML Source

<details>

```yaml
name: coso_observedTime
description: The time at which the contaminant was observed in the environment.
title: observed time
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:observedTime
alias: coso_observedTime
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- http___w3id.org_sawgraph_v1_us-wqp#Observation
- me_egad_EGAD-PFAS-Observation
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: date
- range: datetime

```
</details>