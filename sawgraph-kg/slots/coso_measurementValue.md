

# Slot: measurement value (coso_measurementValue)


_The numeric value or enumerated value that quantifies or qualifies the result._






This slot occurs 1156116 times.


URI: [coso:measurementValue](http://w3id.org/coso/v1/contaminoso#measurementValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) |  |  no  |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) |  |  no  |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal)&nbsp;or&nbsp;<br />[QudtEnumeratedValue](../classes/QudtEnumeratedValue.md)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)&nbsp;or&nbsp;<br />[QudtConcept](../classes/QudtConcept.md)&nbsp;or&nbsp;<br />[QudtVerifiable](../classes/QudtVerifiable.md)







## LinkML Source

<details>

```yaml
name: coso_measurementValue
description: The numeric value or enumerated value that quantifies or qualifies the
  result.
title: measurement value
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:measurementValue
alias: coso_measurementValue
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
- range: decimal
- range: qudt_EnumeratedValue
- range: double
- range: qudt_Concept
- range: qudt_Verifiable

```
</details>