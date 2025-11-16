

# Slot: me_mgs_ofWellType




This slot occurs 144120 times.


URI: [me_mgs:ofWellType](http://sawgraph.spatialai.org/v1/me-mgs#ofWellType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[MeMgsWellType](../classes/MeMgsWellType.md)







## LinkML Source

<details>

```yaml
name: me_mgs_ofWellType
from_schema: okns:hydrology-kg
rank: 1000
slot_uri: me_mgs:ofWellType
alias: me_mgs_ofWellType
domain_of:
- me_mgs_MGS-Well
union_of:
- me_mgs_MGS-Well
- owl_Thing
- geo_SpatialObject
- geo_Feature
range: Any
any_of:
- range: owl_Thing
- range: me_mgs_WellType

```
</details>