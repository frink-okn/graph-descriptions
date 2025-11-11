

# Slot: egad - validation level (me_egad_validationLevel)




This slot occurs 567749 times.


URI: [me_egad:validationLevel](http://sawgraph.spatialai.org/v1/me-egad#validationLevel)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-SinglePFAS-Concentration](../classes/MeEgadEGAD-SinglePFAS-Concentration.md) |  |  no  |
| [MeEgadEGAD-AggregatePFAS-Concentration](../classes/MeEgadEGAD-AggregatePFAS-Concentration.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-ValidationLevel](../classes/MeEgadEGAD-ValidationLevel.md)







## LinkML Source

<details>

```yaml
name: me_egad_validationLevel
title: egad - validation level
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: me_egad:validationLevel
alias: me_egad_validationLevel
domain_of:
- me_egad_EGAD-AggregatePFAS-Concentration
- me_egad_EGAD-SinglePFAS-Concentration
subproperty_of: coso_resultAnnotation
range: Any
any_of:
- range: owl_Thing
- range: owl_NamedIndividual
- range: me_egad_EGAD-ValidationLevel

```
</details>