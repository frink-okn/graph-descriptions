

# Slot: topological connection (spatial contact) (sawgraph) (spatial_spatiallyRelatedTo)




This slot occurs 4315928 times.


URI: [spatial:spatiallyRelatedTo](http://purl.org/spatialai/spatial/spatial-full#spatiallyRelatedTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) |  |  no  |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion3](../classes/KwgoAdministrativeRegion3.md)&nbsp;or&nbsp;<br />[KwgoRegion](../classes/KwgoRegion.md)&nbsp;or&nbsp;<br />[RdfsResource](../classes/RdfsResource.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md)&nbsp;or&nbsp;<br />[Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md)







## LinkML Source

<details>

```yaml
name: spatial_spatiallyRelatedTo
title: topological connection (spatial contact) (sawgraph)
from_schema: okns:fio-kg
exact_mappings:
- http://stko-kwg.geog.ucsb.edu/lod/ontology/spatialRelation
rank: 1000
slot_uri: spatial:spatiallyRelatedTo
alias: spatial_spatiallyRelatedTo
domain_of:
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
- kwgo_S2Cell_Level13
subproperty_of: kwgo_spatialRelation
union_of:
- geo_SpatialObject
- owl_Thing
range: Any
any_of:
- range: fio-epa-frs_EPA-PFAS-Facility
- range: kwgo_AdministrativeRegion_3
- range: kwgo_Region
- range: rdfs_Resource
- range: kwgo_AdministrativeRegion
- range: kwgo_S2Cell_Level13
- range: geo_SpatialObject
- range: owl_Thing
- range: kwgo_AdministrativeRegion_2
- range: fio-epa-frs_FRS-Facility

```
</details>