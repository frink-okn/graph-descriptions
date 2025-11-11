

# Slot: measurement unit (coso_measurementUnit)


_The unit of measurement the describes the result._






This slot occurs 285114 times.


URI: [coso:measurementUnit](http://w3id.org/coso/v1/contaminoso#measurementUnit)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) |  |  no  |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) |  |  no  |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[QudtConcept](../classes/QudtConcept.md)&nbsp;or&nbsp;<br />[QudtUnit](../classes/QudtUnit.md)







## LinkML Source

<details>

```yaml
name: coso_measurementUnit
description: The unit of measurement the describes the result.
title: measurement unit
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:measurementUnit
alias: coso_measurementUnit
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
- http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
union_of:
- sosa_Result
- coso_ContaminantMeasurement
- owl_Thing
- qudt_Quantifiable
- qudt_Quantity
- qudt_Concept
- stad_Datapoint
range: Any
any_of:
- range: qudt_Concept
- range: qudt_Unit

```
</details>