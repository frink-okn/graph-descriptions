

# Slot: No slot (predicate) name specified -- this slot is noted as a subproperty of another slot in this graph but has not itself been defined. (us_sdwis_hasSource)





URI: [us_sdwis:hasSource](http://sawgraph.spatialai.org/v1/us-sdwis#hasSource)



<!-- no inheritance hierarchy -->








## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[UsSdwisPWS-SubFeature](../classes/UsSdwisPWS-SubFeature.md)







## LinkML Source

<details>

```yaml
name: us_sdwis_hasSource
title: No slot (predicate) name specified -- this slot is noted as a subproperty of
  another slot in this graph but has not itself been defined.
notes:
- No occurrences of this slot in the graph.
from_schema: okns:hydrology-kg
rank: 1000
slot_uri: us_sdwis:hasSource
alias: us_sdwis_hasSource
asymmetric: true
inverse: us_sdwis_sourceFor
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