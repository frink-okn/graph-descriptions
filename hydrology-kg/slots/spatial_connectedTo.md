

# Slot: topological connection (spatial contact) (sawgraph) (spatial_connectedTo)




This slot occurs 4665700 times.


URI: [spatial:connectedTo](http://purl.org/spatialai/spatial/spatial-full#connectedTo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HyfHYEstuary](../classes/HyfHYEstuary.md) |  |  no  |
| [UsSdwisPublicWaterSystem-SW](../classes/UsSdwisPublicWaterSystem-SW.md) |  |  no  |
| [HyfHYCanal](../classes/HyfHYCanal.md) |  |  no  |
| [HyfHYWaterBody](../classes/HyfHYWaterBody.md) |  |  no  |
| [UsSdwisPublicWaterSystem-GW](../classes/UsSdwisPublicWaterSystem-GW.md) |  |  no  |
| [HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md) |  |  no  |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) |  |  no  |
| [UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md) |  |  no  |
| [HyfHYLagoon](../classes/HyfHYLagoon.md) |  |  no  |
| [UsSdwisPublicWaterSystem-NTNCWS](../classes/UsSdwisPublicWaterSystem-NTNCWS.md) |  |  no  |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) |  |  no  |
| [UsSdwisPublicWaterSystem-CWS](../classes/UsSdwisPublicWaterSystem-CWS.md) |  |  no  |
| [HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md) |  |  no  |
| [HyfHYRiver](../classes/HyfHYRiver.md) |  |  no  |
| [HyfHYImpoundment](../classes/HyfHYImpoundment.md) |  |  no  |
| [HyfHYLake](../classes/HyfHYLake.md) |  |  no  |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |  |  no  |
| [UsSdwisPublicWaterSystem-TNCWS](../classes/UsSdwisPublicWaterSystem-TNCWS.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion3](../classes/KwgoAdministrativeRegion3.md)&nbsp;or&nbsp;<br />[HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-NTNCWS](../classes/UsSdwisPublicWaterSystem-NTNCWS.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-TNCWS](../classes/UsSdwisPublicWaterSystem-TNCWS.md)&nbsp;or&nbsp;<br />[MeMgsMGS-Well](../classes/MeMgsMGS-Well.md)&nbsp;or&nbsp;<br />[KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-SW](../classes/UsSdwisPublicWaterSystem-SW.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion](../classes/KwgoAdministrativeRegion.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md)&nbsp;or&nbsp;<br />[HyfHYWaterBody](../classes/HyfHYWaterBody.md)&nbsp;or&nbsp;<br />[KwgoRegion](../classes/KwgoRegion.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-CWS](../classes/UsSdwisPublicWaterSystem-CWS.md)&nbsp;or&nbsp;<br />[KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem-GW](../classes/UsSdwisPublicWaterSystem-GW.md)&nbsp;or&nbsp;<br />[HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md)&nbsp;or&nbsp;<br />[HyfHYLake](../classes/HyfHYLake.md)







## LinkML Source

<details>

```yaml
name: spatial_connectedTo
title: topological connection (spatial contact) (sawgraph)
from_schema: okns:hydrology-kg
exact_mappings:
- http://purl.org/spatialai/spatial/spatial-full#connectedTo
rank: 1000
slot_uri: spatial:connectedTo
alias: spatial_connectedTo
domain_of:
- http___gwml2.org_def_gwml2#GW_Aquifer
- http___gwml2.org_def_gwml2#GW_AquiferSystem
- hyf__HY_ElementaryFlowPath
- hyf__HY_Lake
- hyf__HY_WaterBody
- kwgo_S2Cell_Level13
- me_mgs_MGS-Well
- us_sdwis_PWS-ServiceArea
- us_sdwis_PublicWaterSystem-CWS
- us_sdwis_PublicWaterSystem-GW
- us_sdwis_PublicWaterSystem-NTNCWS
- us_sdwis_PublicWaterSystem-SW
- us_sdwis_PublicWaterSystem-TNCWS
subproperty_of: kwgo_spatialRelation
union_of:
- owl_Thing
- geo_SpatialObject
range: Any
any_of:
- range: http___gwml2.org_def_gwml2#GW_AquiferSystem
- range: kwgo_AdministrativeRegion_3
- range: hyf__HY_ElementaryFlowPath
- range: us_sdwis_PublicWaterSystem-NTNCWS
- range: us_sdwis_PublicWaterSystem-TNCWS
- range: me_mgs_MGS-Well
- range: kwgo_S2Cell_Level13
- range: us_sdwis_PublicWaterSystem-SW
- range: kwgo_AdministrativeRegion
- range: geo_SpatialObject
- range: us_sdwis_PWS-ServiceArea
- range: hyf__HY_WaterBody
- range: kwgo_Region
- range: us_sdwis_PublicWaterSystem-CWS
- range: kwgo_AdministrativeRegion_2
- range: owl_Thing
- range: us_sdwis_PublicWaterSystem-GW
- range: http___gwml2.org_def_gwml2#GW_Aquifer
- range: hyf__HY_Lake

```
</details>