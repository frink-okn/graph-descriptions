

# Slot: egad - sample treatment status (http___w3id.org_sawgraph_v1_me-egad#sampleTreatmentStatus)




This slot occurs 15610 times.


URI: [http://w3id.org/sawgraph/v1/me-egad#sampleTreatmentStatus](http://w3id.org/sawgraph/v1/me-egad#sampleTreatmentStatus)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) |  |  no  |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus.md)&nbsp;or&nbsp;<br />[CosoSampleAnnotation](../classes/CosoSampleAnnotation.md)







## LinkML Source

<details>

```yaml
name: http___w3id.org_sawgraph_v1_me-egad#sampleTreatmentStatus
title: egad - sample treatment status
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: http://w3id.org/sawgraph/v1/me-egad#sampleTreatmentStatus
alias: http___w3id.org_sawgraph_v1_me_egad#sampleTreatmentStatus
domain_of:
- coso_AnimalMilkSample
- http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
subproperty_of: coso_sampleAnnotation
union_of:
- owl_Thing
- coso_MaterialSample
- sosa_Sample
range: Any
any_of:
- range: owl_Thing
- range: owl_NamedIndividual
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleTreatmentStatus
- range: coso_SampleAnnotation

```
</details>