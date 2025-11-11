

# Slot: sample annotation (coso_sampleAnnotation)


_A relation between a material sample and additional metadata about the sample._






This slot occurs 107712 times.


URI: [coso:sampleAnnotation](http://w3id.org/coso/v1/contaminoso#sampleAnnotation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) |  |  no  |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) |  |  no  |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) |  |  no  |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) |  |  no  |
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

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleCollectionMethod](../classes/MeEgadEGAD-SampleCollectionMethod.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleDetailedLocation](../classes/MeEgadEGAD-SampleDetailedLocation.md)&nbsp;or&nbsp;<br />[CosoSampleAnnotation](../classes/CosoSampleAnnotation.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleDetailedLocation.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampleTreatmentStatus](../classes/MeEgadEGAD-SampleTreatmentStatus.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleTreatmentStatus.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampleCollectionMethod.md)







## LinkML Source

<details>

```yaml
name: coso_sampleAnnotation
description: A relation between a material sample and additional metadata about the
  sample.
title: sample annotation
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:sampleAnnotation
alias: coso_sampleAnnotation
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
- me_egad_EGAD-Sample
union_of:
- owl_Thing
- coso_MaterialSample
- sosa_Sample
range: Any
any_of:
- range: me_egad_EGAD-SampleCollectionMethod
- range: owl_NamedIndividual
- range: me_egad_EGAD-SampleDetailedLocation
- range: coso_SampleAnnotation
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleDetailedLocation
- range: me_egad_EGAD-SampleTreatmentStatus
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleTreatmentStatus
- range: owl_Thing
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampleCollectionMethod

```
</details>