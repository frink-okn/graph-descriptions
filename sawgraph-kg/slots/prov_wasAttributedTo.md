

# Slot: wasAttributedTo (prov_wasAttributedTo)


_Attribution is the ascribing of an entity to an agent._






This slot occurs 1318919 times.


URI: [prov:wasAttributedTo](http://www.w3.org/ns/prov#wasAttributedTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [CosoAnimalTissueSample](../classes/CosoAnimalTissueSample.md) |  |  no  |
| [CosoAnimalMaterialSample](../classes/CosoAnimalMaterialSample.md) |  |  no  |
| [CosoPlantMaterialSample](../classes/CosoPlantMaterialSample.md) |  |  no  |
| [MeEgadEGAD-Sample](../classes/MeEgadEGAD-Sample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Observation.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADPorkBloodSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSoilSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADGroundWaterSample.md) |  |  no  |
| [CosoAnimalMilkSample](../classes/CosoAnimalMilkSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADSurfaceWaterSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-Sample.md) |  |  no  |
| [MeEgadEGAD-PFAS-Observation](../classes/MeEgadEGAD-PFAS-Observation.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Us-wqp#Site](../classes/HttpW3id.orgSawgraphV1Us-wqp#Site.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADBeefBloodSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample](../classes/HttpW3id.orgSawgraphV1Me-egad-data#DefEGADDrinkingWaterSample.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Us-wqp#Observation](../classes/HttpW3id.orgSawgraphV1Us-wqp#Observation.md) |  |  no  |
| [CosoAnimalOrganSample](../classes/CosoAnimalOrganSample.md) |  |  no  |







## Properties

* Range: [ProvAgent](../classes/ProvAgent.md)





## Comments

* description: Attribution is the ascribing of an entity to an agent.



## LinkML Source

<details>

```yaml
name: prov_wasAttributedTo
description: Attribution is the ascribing of an entity to an agent.
title: wasAttributedTo
notes:
- No occurrences of this slot in the graph.
comments:
- 'description: Attribution is the ascribing of an entity to an agent.'
from_schema: okns:prov
source: http://www.w3.org/ns/prov-o#
domain: prov_Entity
slot_uri: prov:wasAttributedTo
domain_of:
- coso_AnimalMaterialSample
- coso_AnimalMilkSample
- coso_AnimalOrganSample
- coso_AnimalTissueSample
- coso_PlantMaterialSample
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Observation
- http___w3id.org_sawgraph_v1_me-egad#EGAD-Sample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADBeefBloodSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADDrinkingWaterSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADGroundWaterSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADPorkBloodSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSoilSample
- http___w3id.org_sawgraph_v1_me-egad-data#DefEGADSurfaceWaterSample
- http___w3id.org_sawgraph_v1_us-wqp#Observation
- http___w3id.org_sawgraph_v1_us-wqp#Site
- me_egad_EGAD-PFAS-Observation
- me_egad_EGAD-Sample
subproperty_of: prov_wasInfluencedBy
range: prov_Agent

```
</details>