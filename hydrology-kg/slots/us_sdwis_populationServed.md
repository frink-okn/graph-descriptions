

# Slot: us_sdwis_populationServed




This slot occurs 6402 times.


URI: [us_sdwis:populationServed](http://sawgraph.spatialai.org/v1/us-sdwis#populationServed)



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

* Range: [Int32](../types/Int32.md)







## LinkML Source

<details>

```yaml
name: us_sdwis_populationServed
from_schema: okns:hydrology-kg
rank: 1000
slot_uri: us_sdwis:populationServed
alias: us_sdwis_populationServed
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
range: int32

```
</details>