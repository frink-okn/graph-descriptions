

# Slot: Identifier (dct_identifier)


_Recommended practice is to identify the resource by means of a string conforming to an identification system. Examples include International Standard Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name (URN).  Persistent identifiers should be provided as HTTP URIs._






This slot occurs 64612 times.


URI: [dct:identifier](http://purl.org/dc/terms/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) |  |  no  |
| [Beb7217b5b32080b9606028314249e33b](../classes/Beb7217b5b32080b9606028314249e33b.md) |  |  no  |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) |  |  no  |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) |  |  no  |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) |  |  no  |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) |  |  no  |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) |  |  no  |
| [CosoSubstanceCollection](../classes/CosoSubstanceCollection.md) | A collection of more than one substances |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-ParameterName.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) |  |  no  |
| [Ba76635ffb4afc02e78b9ef49973d089f](../classes/Ba76635ffb4afc02e78b9ef49973d089f.md) |  |  no  |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) |  |  no  |
| [CosoAnimalBloodSample](../classes/CosoAnimalBloodSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) |  |  no  |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) |  |  no  |







## Properties

* Range: [RdfsLiteral](../classes/RdfsLiteral.md)





## Comments

* description: An unambiguous reference to the resource within a given context.



## LinkML Source

<details>

```yaml
name: dct_identifier
description: Recommended practice is to identify the resource by means of a string
  conforming to an identification system. Examples include International Standard
  Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name (URN).  Persistent
  identifiers should be provided as HTTP URIs.
title: Identifier
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: An unambiguous reference to the resource within a given context.'
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:identifier
domain_of:
- __Ba76635ffb4afc02e78b9ef49973d089f
- __Beb7217b5b32080b9606028314249e33b
- coso_AnimalBloodSample
- coso_AnimalMaterialSample
- coso_AnimalMilkSample
- coso_AnimalOrganSample
- coso_AnimalTissueSample
- coso_PlantMaterialSample
- coso_SubstanceCollection
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-ParameterName
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Site
- http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
- http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
- me_egad_EGAD-PFAS-Site
- me_egad_EGAD-Sample
- me_egad_EGAD-SamplePoint
subproperty_of: dc_identifier
range: rdfs_Literal

```
</details>