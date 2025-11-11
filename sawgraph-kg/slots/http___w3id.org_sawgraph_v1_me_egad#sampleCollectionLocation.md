

# Slot: egad - sample collection location (http___w3id.org_sawgraph_v1_me-egad#sampleCollectionLocation)




This slot occurs 15556 times.


URI: [http://w3id.org/sawgraph/v1/me-egad#sampleCollectionLocation](http://w3id.org/sawgraph/v1/me-egad#sampleCollectionLocation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) |  |  no  |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) |  |  no  |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[CosoSampleAnnotation](../classes/CosoSampleAnnotation.md)







## LinkML Source

<details>

```yaml
name: http___w3id.org_sawgraph_v1_me-egad#sampleCollectionLocation
title: egad - sample collection location
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: http://w3id.org/sawgraph/v1/me-egad#sampleCollectionLocation
alias: http___w3id.org_sawgraph_v1_me_egad#sampleCollectionLocation
domain_of:
- coso_AnimalOrganSample
- coso_AnimalTissueSample
- coso_PlantMaterialSample
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
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleDetailedLocation
- range: owl_Thing
- range: owl_NamedIndividual
- range: coso_SampleAnnotation

```
</details>