

# Slot: us_sdwis_sellsTo





URI: [us_sdwis:sellsTo](http://sawgraph.spatialai.org/v1/us-sdwis#sellsTo)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[GeoFeature](../classes/GeoFeature.md)&nbsp;or&nbsp;<br />[UsSdwisPublicWaterSystem](../classes/UsSdwisPublicWaterSystem.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)







## LinkML Source

<details>

```yaml
name: us_sdwis_sellsTo
notes:
- No occurrences of this slot in the graph.
from_schema: okns:hydrology-kg
rank: 1000
slot_uri: us_sdwis:sellsTo
alias: us_sdwis_sellsTo
inverse: us_sdwis_buysFrom
union_of:
- geo_Feature
- us_sdwis_PublicWaterSystem
- geo_SpatialObject
- owl_Thing
range: Any
any_of:
- range: geo_Feature
- range: us_sdwis_PublicWaterSystem
- range: geo_SpatialObject
- range: owl_Thing

```
</details>