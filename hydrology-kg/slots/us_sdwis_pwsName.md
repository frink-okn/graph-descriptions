

# Slot: us_sdwis_pwsName




This slot occurs 6362 times.


URI: [us_sdwis:pwsName](http://sawgraph.spatialai.org/v1/us-sdwis#pwsName)



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

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[RdfsLiteral](../classes/RdfsLiteral.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)







## LinkML Source

<details>

```yaml
name: us_sdwis_pwsName
from_schema: okns:hydrology-kg
exact_mappings:
- http://sawgraph.spatialai.org/v1/us-sdwis#pwsName
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
- owl_Thing
- __B4321a9eb518ec74b0f636677676d03cc
- us_sdwis_PublicWaterSystem
- geo_Feature
- geo_SpatialObject
range: Any
any_of:
- range: rdfs_Literal
- range: string

```
</details>