

# Slot: hyf_downstreamFlowPath




This slot occurs 865469 times.


URI: [hyf:downstreamFlowPath](https://www.opengis.net/def/schema/hy_features/hyf/downstreamFlowPath)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md) |  |  no  |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HyfHYCatchmentRealization](../classes/HyfHYCatchmentRealization.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[HttpHyfo.spatialai.orgV1Hyfo#WaterFeatureRepresentation](../classes/HttpHyfo.spatialai.orgV1Hyfo#WaterFeatureRepresentation.md)&nbsp;or&nbsp;<br />[B805a9e7d30eaabcb686b8ce670ed1e95](../classes/B805a9e7d30eaabcb686b8ce670ed1e95.md)&nbsp;or&nbsp;<br />[HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md)&nbsp;or&nbsp;<br />[HyfHYFlowPath](../classes/HyfHYFlowPath.md)







## LinkML Source

<details>

```yaml
name: hyf_downstreamFlowPath
from_schema: okns:hydrology-kg
rank: 1000
slot_uri: hyf:downstreamFlowPath
alias: hyf_downstreamFlowPath
domain_of:
- __B805a9e7d30eaabcb686b8ce670ed1e95
- hyf_HY_ElementaryFlowPath
subproperty_of: hyf_downstreamFlowPathTC
inverse: hyf_upstreamWaterBody
union_of:
- geo_Feature
- owl_Thing
- hyf_HY_CatchmentRealization
- geo_SpatialObject
- http___hyfo.spatialai.org_v1_hyfo#WaterFeatureRepresentation
- hyf_HY_FlowPath
range: Any
any_of:
- range: geo_Feature
- range: owl_Thing
- range: hyf_HY_CatchmentRealization
- range: geo_SpatialObject
- range: http___hyfo.spatialai.org_v1_hyfo#WaterFeatureRepresentation
- range: __B805a9e7d30eaabcb686b8ce670ed1e95
- range: hyf_HY_ElementaryFlowPath
- range: hyf_HY_FlowPath

```
</details>