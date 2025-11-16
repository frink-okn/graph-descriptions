

# Slot: us_sdwis_hasPart





URI: [us_sdwis:hasPart](http://sawgraph.spatialai.org/v1/us-sdwis#hasPart)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[UsSdwisPWS-SubFeature](../classes/UsSdwisPWS-SubFeature.md)







## LinkML Source

<details>

```yaml
name: us_sdwis_hasPart
notes:
- No occurrences of this slot in the graph.
from_schema: okns:hydrology-kg
rank: 1000
slot_uri: us_sdwis:hasPart
alias: us_sdwis_hasPart
inverse: us_sdwis_partOf
union_of:
- geo_Feature
- us_sdwis_PublicWaterSystem
- geo_SpatialObject
- owl_Thing
range: Any
any_of:
- range: owl_Thing
- range: us_sdwis_PWS-SubFeature

```
</details>