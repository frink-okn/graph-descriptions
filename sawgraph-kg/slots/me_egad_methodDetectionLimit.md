

# Slot: egad - method detection limit (me_egad_methodDetectionLimit)




This slot occurs 577732 times.


URI: [me_egad:methodDetectionLimit](http://sawgraph.spatialai.org/v1/me-egad#methodDetectionLimit)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) |  |  no  |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[CosoResultQualifier](../classes/CosoResultQualifier.md)&nbsp;or&nbsp;<br />[CosoDetectionLimit](../classes/CosoDetectionLimit.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-MethodDetectionLimit](../classes/MeEgadEGAD-MethodDetectionLimit.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[QudtQuantifiable](../classes/QudtQuantifiable.md)&nbsp;or&nbsp;<br />[QudtQuantity](../classes/QudtQuantity.md)&nbsp;or&nbsp;<br />[QudtConcept](../classes/QudtConcept.md)&nbsp;or&nbsp;<br />[StadDatapoint](../classes/StadDatapoint.md)







## LinkML Source

<details>

```yaml
name: me_egad_methodDetectionLimit
title: egad - method detection limit
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: me_egad:methodDetectionLimit
alias: me_egad_methodDetectionLimit
domain_of:
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
subproperty_of: coso_resultAnnotation
range: Any
any_of:
- range: coso_ResultQualifier
- range: coso_DetectionLimit
- range: me_egad_EGAD-MethodDetectionLimit
- range: owl_Thing
- range: qudt_Quantifiable
- range: qudt_Quantity
- range: qudt_Concept
- range: stad_Datapoint

```
</details>