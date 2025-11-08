

# Slot: egad - sample collection method (me_egad_sampleCollectionMethod)




This slot occurs 22690 times.


URI: [me_egad:sampleCollectionMethod](http://sawgraph.spatialai.org/v1/me-egad#sampleCollectionMethod)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleCollectionMethod](../classes/MeEgadEGAD-SampleCollectionMethod.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[CosoSampleAnnotation](../classes/CosoSampleAnnotation.md)







## LinkML Source

<details>

```yaml
name: me_egad_sampleCollectionMethod
title: egad - sample collection method
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: me_egad:sampleCollectionMethod
alias: me_egad_sampleCollectionMethod
domain_of:
- me_egad_EGAD-Sample
subproperty_of: coso_sampleAnnotation
union_of:
- owl_Thing
- coso_MaterialSample
- sosa_Sample
range: Any
any_of:
- range: me_egad_EGAD-SampleCollectionMethod
- range: owl_Thing
- range: owl_NamedIndividual
- range: coso_SampleAnnotation

```
</details>