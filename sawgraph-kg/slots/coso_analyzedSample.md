

# Slot: analyzed sample (coso_analyzedSample)


_A relation between an observation of a contaminant and the sample that was analyzed._






This slot occurs 1282200 times.


URI: [coso:analyzedSample](http://w3id.org/coso/v1/contaminoso#analyzedSample)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md)&nbsp;or&nbsp;<br />[SosaFeatureOfInterest](../classes/SosaFeatureOfInterest.md)&nbsp;or&nbsp;<br />[CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md)&nbsp;or&nbsp;<br />[CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md)&nbsp;or&nbsp;<br />[CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Us-wqp#Sample](../classes/HttpW3id.orgSawgraphV1Us-wqp#Sample.md)&nbsp;or&nbsp;<br />[SosaSample](../classes/SosaSample.md)&nbsp;or&nbsp;<br />[CosoMaterialSample](../classes/CosoMaterialSample.md)&nbsp;or&nbsp;<br />[CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md)&nbsp;or&nbsp;<br />[CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md)&nbsp;or&nbsp;<br />[CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md)







## LinkML Source

<details>

```yaml
name: coso_analyzedSample
description: A relation between an observation of a contaminant and the sample that
  was analyzed.
title: analyzed sample
from_schema: okns:sawgraph-kg
rank: 1000
slot_uri: coso:analyzedSample
alias: coso_analyzedSample
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- http___w3id.org_sawgraph_v1_us-wqp#Observation
- me_egad_EGAD-PFAS-Observation
subproperty_of: coso_hasAnyFeatureOfInterest
union_of:
- coso_ContaminantObservation
- owl_Thing
- sosa_Observation
- coso_ContaminantSampleObservation
range: Any
any_of:
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
- range: sosa_FeatureOfInterest
- range: coso_PlantMaterialSample
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
- range: me_egad_EGAD-Sample
- range: coso_AnimalTissueSample
- range: coso_AnimalOrganSample
- range: http___w3id.org_sawgraph_v1_us-wqp#Sample
- range: sosa_Sample
- range: coso_MaterialSample
- range: coso_AnimalMilkSample
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
- range: coso_AnimalBloodSample
- range: owl_Thing
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
- range: coso_AnimalMaterialSample
- range: http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample

```
</details>