

# Slot: egad - sample collection method (http___w3id.org_sawgraph_v1_me-egad#sampleCollectionMethod)




This slot occurs 22690 times.


URI: [http://w3id.org/sawgraph/v1/me-egad#sampleCollectionMethod](http://w3id.org/sawgraph/v1/me-egad#sampleCollectionMethod)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) |  |  no  |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) |  |  no  |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) |  |  no  |
| [CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) |  |  no  |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) |  |  no  |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod.md)&nbsp;or&nbsp;<br />[CosoSampleAnnotation](../classes/CosoSampleAnnotation.md)







## LinkML Source

<details>

```yaml
name: http___w3id.org_sawgraph_v1_me-egad#sampleCollectionMethod
title: egad - sample collection method
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: http://w3id.org/sawgraph/v1/me-egad#sampleCollectionMethod
alias: http___w3id.org_sawgraph_v1_me_egad#sampleCollectionMethod
domain_of:
- coso_AnimalBloodSample
- coso_AnimalMaterialSample
- coso_AnimalMilkSample
- coso_AnimalOrganSample
- coso_AnimalTissueSample
- coso_PlantMaterialSample
- http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
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
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleCollectionMethod
- range: coso_SampleAnnotation

```
</details>