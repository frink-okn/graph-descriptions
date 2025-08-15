

# Slot: me_mgs_wellDepth




This slot occurs 147508 times.


URI: [me_mgs:wellDepth](http://sawgraph.spatialai.org/v1/me-mgs#wellDepth)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[StadSingleData](../classes/StadSingleData.md)&nbsp;or&nbsp;<br />[MeMgsWellDepthInFt](../classes/MeMgsWellDepthInFt.md)







## LinkML Source

<details>

```yaml
name: me_mgs_wellDepth
from_schema: okns:hydrology-kg
exact_mappings:
- http://sawgraph.spatialai.org/v1/me-mgs#wellDepth
rank: 1000
slot_uri: me_mgs:wellDepth
alias: me_mgs_wellDepth
domain_of:
- me_mgs_MGS-Well
union_of:
- owl_Thing
- me_mgs_MGS-Well
- geo_Feature
- geo_SpatialObject
range: Any
any_of:
- range: owl_Thing
- range: stad_SingleData
- range: me_mgs_WellDepthInFt

```
</details>