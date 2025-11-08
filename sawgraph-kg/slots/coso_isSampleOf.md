

# Slot: is sample of (coso_isSampleOf)


_A relation between a physcial material sample and the geographic feature the sample was taken from._






This slot occurs 23037 times.


URI: [coso:isSampleOf](http://w3id.org/coso/v1/contaminoso#isSampleOf)



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

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[CosoSampledFeature](../classes/CosoSampledFeature.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[CosoFeature](../classes/CosoFeature.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)







## LinkML Source

<details>

```yaml
name: coso_isSampleOf
description: A relation between a physcial material sample and the geographic feature
  the sample was taken from.
title: is sample of
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:isSampleOf
alias: coso_isSampleOf
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
subproperty_of: sosa_isSampleOf
union_of:
- owl_Thing
- coso_MaterialSample
- sosa_Sample
range: Any
any_of:
- range: coso_SampledFeature
- range: geo_Feature
- range: owl_Thing
- range: coso_Feature
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampledFeature
- range: sosa_FeatureOfInterest
- range: geo_SpatialObject

```
</details>