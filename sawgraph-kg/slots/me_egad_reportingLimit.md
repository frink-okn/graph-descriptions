

# Slot: egad - reporting limit (me_egad_reportingLimit)




This slot occurs 579249 times.


URI: [me_egad:reportingLimit](http://sawgraph.spatialai.org/v1/me-egad#reportingLimit)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) |  |  no  |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[CosoQuantitationLimit](../classes/CosoQuantitationLimit.md)&nbsp;or&nbsp;<br />[CosoResultQualifier](../classes/CosoResultQualifier.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[QudtQuantifiable](../classes/QudtQuantifiable.md)&nbsp;or&nbsp;<br />[QudtQuantity](../classes/QudtQuantity.md)&nbsp;or&nbsp;<br />[QudtConcept](../classes/QudtConcept.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ReportingLimit](../classes/MeEgadEGAD-ReportingLimit.md)&nbsp;or&nbsp;<br />[StadDatapoint](../classes/StadDatapoint.md)







## LinkML Source

<details>

```yaml
name: me_egad_reportingLimit
title: egad - reporting limit
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: me_egad:reportingLimit
alias: me_egad_reportingLimit
domain_of:
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
subproperty_of: coso_resultAnnotation
range: Any
any_of:
- range: coso_QuantitationLimit
- range: coso_ResultQualifier
- range: owl_Thing
- range: qudt_Quantifiable
- range: qudt_Quantity
- range: qudt_Concept
- range: me_egad_EGAD-ReportingLimit
- range: stad_Datapoint

```
</details>