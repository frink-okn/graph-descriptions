

# Slot: topological connection (spatial contact) (sawgraph) (spatial_spatiallyRelatedTo)




This slot occurs 43360 times.


URI: [spatial:spatiallyRelatedTo](http://purl.org/spatialai/spatial/spatial-full#spatiallyRelatedTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md) |  |  no  |
| [HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site.md) |  |  no  |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) |  |  no  |
| [MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md) |  |  no  |
| [MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-SamplePoint](../classes/MeEgadEGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion3](../classes/KwgoAdministrativeRegion3.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-SamplePoint.md)&nbsp;or&nbsp;<br />[MeEgadEGAD-PFAS-Site](../classes/MeEgadEGAD-PFAS-Site.md)&nbsp;or&nbsp;<br />[HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site](../classes/HttpW3id.orgSawgraphV1Me-egad#EGAD-PFAS-Site.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[KwgoRegion](../classes/KwgoRegion.md)







## LinkML Source

<details>

```yaml
name: spatial_spatiallyRelatedTo
title: topological connection (spatial contact) (sawgraph)
from_schema: okns:sawgraph-kg
exact_mappings:
- http://stko-kwg.geog.ucsb.edu/lod/ontology/spatialRelation
rank: 1000
slot_uri: spatial:spatiallyRelatedTo
alias: spatial_spatiallyRelatedTo
domain_of:
- http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Site
- http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
- kwgo_S2Cell_Level13
- me_egad_EGAD-PFAS-Site
- me_egad_EGAD-SamplePoint
subproperty_of: kwgo_spatialRelation
union_of:
- owl_Thing
- geo_SpatialObject
range: Any
any_of:
- range: kwgo_S2Cell_Level13
- range: kwgo_AdministrativeRegion
- range: owl_Thing
- range: me_egad_EGAD-SamplePoint
- range: kwgo_AdministrativeRegion_3
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-SamplePoint
- range: me_egad_EGAD-PFAS-Site
- range: http___w3id.org_sawgraph_v1_me-egad#EGAD-PFAS-Site
- range: geo_SpatialObject
- range: kwgo_Region

```
</details>