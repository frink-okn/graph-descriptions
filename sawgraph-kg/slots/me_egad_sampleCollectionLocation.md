

# Slot: egad - sample collection location (me_egad_sampleCollectionLocation)




This slot occurs 15556 times.


URI: [me_egad:sampleCollectionLocation](http://sawgraph.spatialai.org/v1/me-egad#sampleCollectionLocation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[CosoSampleAnnotation](../classes/CosoSampleAnnotation.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleDetailedLocation](../classes/MeEgadEGAD-SampleDetailedLocation.md)







## LinkML Source

<details>

```yaml
name: me_egad_sampleCollectionLocation
title: egad - sample collection location
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: me_egad:sampleCollectionLocation
alias: me_egad_sampleCollectionLocation
domain_of:
- me_egad_EGAD-Sample
subproperty_of: coso_sampleAnnotation
union_of:
- owl_Thing
- coso_MaterialSample
- sosa_Sample
range: Any
any_of:
- range: owl_Thing
- range: owl_NamedIndividual
- range: coso_SampleAnnotation
- range: me_egad_EGAD-SampleDetailedLocation

```
</details>