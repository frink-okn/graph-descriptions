

# Slot: us_sdwis_serviceArea




This slot occurs 5061 times.


URI: [us_sdwis:serviceArea](http://sawgraph.spatialai.org/v1/us-sdwis#serviceArea)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UsSdwisPublicWaterSystem-SW](../classes/UsSdwisPublicWaterSystem-SW.md) |  |  no  |
| [UsSdwisPublicWaterSystem-GW](../classes/UsSdwisPublicWaterSystem-GW.md) |  |  no  |
| [UsSdwisPublicWaterSystem-NTNCWS](../classes/UsSdwisPublicWaterSystem-NTNCWS.md) |  |  no  |
| [UsSdwisPublicWaterSystem-CWS](../classes/UsSdwisPublicWaterSystem-CWS.md) |  |  no  |
| [UsSdwisPublicWaterSystem-TNCWS](../classes/UsSdwisPublicWaterSystem-TNCWS.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md)







## LinkML Source

<details>

```yaml
name: us_sdwis_serviceArea
from_schema: okns:hydrology-kg
exact_mappings:
- http://sawgraph.spatialai.org/v1/us-sdwis#serviceArea
rank: 1000
slot_uri: us_sdwis:serviceArea
alias: us_sdwis_serviceArea
domain_of:
- us_sdwis_PublicWaterSystem-CWS
- us_sdwis_PublicWaterSystem-GW
- us_sdwis_PublicWaterSystem-NTNCWS
- us_sdwis_PublicWaterSystem-SW
- us_sdwis_PublicWaterSystem-TNCWS
union_of:
- owl_Thing
- __B4321a9eb518ec74b0f636677676d03cc
- us_sdwis_PublicWaterSystem
- geo_Feature
- geo_SpatialObject
range: Any
any_of:
- range: owl_Thing
- range: geo_SpatialObject
- range: geo_Feature
- range: us_sdwis_PWS-ServiceArea

```
</details>