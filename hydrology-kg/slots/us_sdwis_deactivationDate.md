

# Slot: us_sdwis_deactivationDate




This slot occurs 4524 times.


URI: [us_sdwis:deactivationDate](http://sawgraph.spatialai.org/v1/us-sdwis#deactivationDate)



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

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)







## LinkML Source

<details>

```yaml
name: us_sdwis_deactivationDate
from_schema: okns:hydrology-kg
exact_mappings:
- http://sawgraph.spatialai.org/v1/us-sdwis#deactivationDate
rank: 1000
slot_uri: us_sdwis:deactivationDate
alias: us_sdwis_deactivationDate
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
range: date

```
</details>