

# Slot: egad - lab qualifier (me_egad_labQualifier)




This slot occurs 489050 times.


URI: [me_egad:labQualifier](http://sawgraph.spatialai.org/v1/me-egad#labQualifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) |  |  no  |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ConcentrationQualifier](../classes/MeEgadEGAD-ConcentrationQualifier.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)







## LinkML Source

<details>

```yaml
name: me_egad_labQualifier
title: egad - lab qualifier
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: me_egad:labQualifier
alias: me_egad_labQualifier
domain_of:
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
subproperty_of: coso_resultAnnotation
range: Any
any_of:
- range: me_egad_EGAD-ConcentrationQualifier
- range: owl_NamedIndividual

```
</details>