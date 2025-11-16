

# Slot: us_sdwis_pwsName




This slot occurs 6362 times.


URI: [us_sdwis:pwsName](http://sawgraph.spatialai.org/v1/us-sdwis#pwsName)



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

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)







## LinkML Source

<details>

```yaml
name: us_sdwis_pwsName
from_schema: okns:hydrology-kg
rank: 1000
slot_uri: us_sdwis:pwsName
alias: us_sdwis_pwsName
domain_of:
- us_sdwis_PublicWaterSystem-CWS
- us_sdwis_PublicWaterSystem-GW
- us_sdwis_PublicWaterSystem-NTNCWS
- us_sdwis_PublicWaterSystem-SW
- us_sdwis_PublicWaterSystem-TNCWS
subproperty_of: rdfs_label
union_of:
- geo_Feature
- us_sdwis_PublicWaterSystem
- geo_SpatialObject
- owl_Thing
range: Any
any_of:
- range: string
- range: rdfs_Literal

```
</details>