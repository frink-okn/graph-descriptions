

# Slot: has any feature of interest (coso_hasAnyFeatureOfInterest)


_A relation between an observation of a contaminant and a feature it is the subject of. There are no specific scale or cardinality constraints that limit the feature._






This slot occurs 3461978 times.


URI: [coso:hasAnyFeatureOfInterest](http://w3id.org/coso/v1/contaminoso#hasAnyFeatureOfInterest)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md)&nbsp;or&nbsp;<br />[CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md)&nbsp;or&nbsp;<br />[CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SampledFeature](../classes/MeEgadEGAD-SampledFeature.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md)&nbsp;or&nbsp;<br />[CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md)&nbsp;or&nbsp;<br />[CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SampledFeature.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md)&nbsp;or&nbsp;<br />[CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md)







## LinkML Source

<details>

```yaml
name: coso_hasAnyFeatureOfInterest
description: A relation between an observation of a contaminant and a feature it is
  the subject of. There are no specific scale or cardinality constraints that limit
  the feature.
title: has any feature of interest
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:hasAnyFeatureOfInterest
alias: coso_hasAnyFeatureOfInterest
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- me_egad_EGAD-PFAS-Observation
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
range: Any
any_of:
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
- range: sosa_FeatureOfInterest
- range: coso_PlantMaterialSample
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
- range: me_egad_EGAD-Sample
- range: coso_AnimalTissueSample
- range: coso_AnimalOrganSample
- range: me_egad_EGAD-SampledFeature
- range: me_egad_EGAD-SamplePoint
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
- range: coso_AnimalMilkSample
- range: coso_AnimalBloodSample
- range: owl_Thing
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SampledFeature
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
- range: coso_AnimalMaterialSample
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample

```
</details>