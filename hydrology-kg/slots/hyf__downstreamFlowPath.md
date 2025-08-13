

# Slot: hyf__downstreamFlowPath




This slot occurs 865469 times.


URI: [hyf:/downstreamFlowPath](https://www.opengis.net/def/schema/hy_features/hyf/downstreamFlowPath)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[HttpHyfo.spatialai.orgV1Hyfo#WaterFeatureRepresentation](../classes/HttpHyfo.spatialai.orgV1Hyfo#WaterFeatureRepresentation.md)&nbsp;or&nbsp;<br />[HyfHYFlowPath](../classes/HyfHYFlowPath.md)&nbsp;or&nbsp;<br />[Bf03ad86fab1719a427cbb412f91529fa](../classes/Bf03ad86fab1719a427cbb412f91529fa.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md)&nbsp;or&nbsp;<br />[HyfHYCatchmentRealization](../classes/HyfHYCatchmentRealization.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)







## LinkML Source

<details>

```yaml
name: hyf__downstreamFlowPath
from_schema: okns:hydrology-kg
exact_mappings:
- https://www.opengis.net/def/schema/hy_features/hyf/downstreamFlowPath
rank: 1000
slot_uri: hyf:/downstreamFlowPath
alias: hyf__downstreamFlowPath
domain_of:
- hyf__HY_ElementaryFlowPath
subproperty_of: hyf__downstreamFlowPathTC
inverse: hyf__upstreamWaterBody
union_of:
- owl_Thing
- http___hyfo.spatialai.org_v1_hyfo#WaterFeatureRepresentation
- hyf__HY_FlowPath
- __Bf03ad86fab1719a427cbb412f91529fa
- geo_Feature
- hyf__HY_CatchmentRealization
- geo_SpatialObject
range: Any
any_of:
- range: owl_Thing
- range: http___hyfo.spatialai.org_v1_hyfo#WaterFeatureRepresentation
- range: hyf__HY_FlowPath
- range: __Bf03ad86fab1719a427cbb412f91529fa
- range: geo_Feature
- range: hyf__HY_ElementaryFlowPath
- range: hyf__HY_CatchmentRealization
- range: geo_SpatialObject

```
</details>