

# Slot: egad - reporting limit (http___w3id.org_sawgraph_v1_me-egad#reportingLimit)




This slot occurs 579249 times.


URI: [http://w3id.org/sawgraph/v1/me-egad#reportingLimit](http://w3id.org/sawgraph/v1/me-egad#reportingLimit)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[CosoQuantitationLimit](../classes/CosoQuantitationLimit.md)&nbsp;or&nbsp;<br />[CosoResultQualifier](../classes/CosoResultQualifier.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[QudtQuantifiable](../classes/QudtQuantifiable.md)&nbsp;or&nbsp;<br />[QudtQuantity](../classes/QudtQuantity.md)&nbsp;or&nbsp;<br />[QudtConcept](../classes/QudtConcept.md)&nbsp;or&nbsp;<br />[StadDatapoint](../classes/StadDatapoint.md)







## LinkML Source

<details>

```yaml
name: http___w3id.org_sawgraph_v1_me-egad#reportingLimit
title: egad - reporting limit
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: http://w3id.org/sawgraph/v1/me-egad#reportingLimit
alias: http___w3id.org_sawgraph_v1_me_egad#reportingLimit
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
- http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
subproperty_of: coso_resultAnnotation
range: Any
any_of:
- range: coso_QuantitationLimit
- range: coso_ResultQualifier
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
- range: owl_Thing
- range: qudt_Quantifiable
- range: qudt_Quantity
- range: qudt_Concept
- range: stad_Datapoint

```
</details>