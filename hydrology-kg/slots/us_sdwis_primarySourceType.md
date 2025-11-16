

# Slot: us_sdwis_primarySourceType




This slot occurs 6190 times.


URI: [us_sdwis:primarySourceType](http://sawgraph.spatialai.org/v1/us-sdwis#primarySourceType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UsSdwisPublicWaterSystem-NTNCWS](../classes/UsSdwisPublicWaterSystem-NTNCWS.md) |  |  no  |
| [UsSdwisPublicWaterSystem-SW](../classes/UsSdwisPublicWaterSystem-SW.md) |  |  no  |
| [UsSdwisPublicWaterSystem-TNCWS](../classes/UsSdwisPublicWaterSystem-TNCWS.md) |  |  no  |
| [UsSdwisPublicWaterSystem-CWS](../classes/UsSdwisPublicWaterSystem-CWS.md) |  |  no  |
| [UsSdwisPublicWaterSystem-GW](../classes/UsSdwisPublicWaterSystem-GW.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[UsSdwisPWS-SourceWaterType](../classes/UsSdwisPWS-SourceWaterType.md)







## LinkML Source

<details>

```yaml
name: us_sdwis_primarySourceType
from_schema: okns:hydrology-kg
rank: 1000
slot_uri: us_sdwis:primarySourceType
alias: us_sdwis_primarySourceType
domain_of:
- us_sdwis_PublicWaterSystem-CWS
- us_sdwis_PublicWaterSystem-GW
- us_sdwis_PublicWaterSystem-NTNCWS
- us_sdwis_PublicWaterSystem-SW
- us_sdwis_PublicWaterSystem-TNCWS
union_of:
- geo_Feature
- us_sdwis_PublicWaterSystem
- geo_SpatialObject
- owl_Thing
range: Any
any_of:
- range: owl_Thing
- range: us_sdwis_PWS-SourceWaterType

```
</details>