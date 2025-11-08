

# Slot: result annotation (coso_resultAnnotation)


_A relation between a result and additional metadata about the result._






This slot occurs 4651480 times.


URI: [coso:resultAnnotation](http://w3id.org/coso/v1/contaminoso#resultAnnotation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-AggregatePFAS-Concentration.md) |  |  no  |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) |  |  no  |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SinglePFAS-Concentration.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ConcentrationQualifier](../classes/MeEgadEGAD-ConcentrationQualifier.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ValidationLevel.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-MethodDetectionLimit](../classes/MeEgadEGAD-MethodDetectionLimit.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ValidationLevel](../classes/MeEgadEGAD-ValidationLevel.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ReportingLimit.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-ConcentrationQualifier.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-MethodDetectionLimit.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ReportingLimit](../classes/MeEgadEGAD-ReportingLimit.md)







## LinkML Source

<details>

```yaml
name: coso_resultAnnotation
description: A relation between a result and additional metadata about the result.
title: result annotation
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:resultAnnotation
alias: coso_resultAnnotation
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-AggregatePFAS-Concentration
- http___w3id.org_sawgraph_v1_me-egad#EGAD-SinglePFAS-Concentration
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
range: Any
any_of:
- range: me_egad_EGAD-ConcentrationQualifier
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ValidationLevel
- range: owl_NamedIndividual
- range: me_egad_EGAD-MethodDetectionLimit
- range: me_egad_EGAD-ValidationLevel
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ReportingLimit
- range: owl_Thing
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-ConcentrationQualifier
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-MethodDetectionLimit
- range: me_egad_EGAD-ReportingLimit

```
</details>