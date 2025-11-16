

# Slot: me_mgs_wellOverburden




This slot occurs 129946 times.


URI: [me_mgs:wellOverburden](http://sawgraph.spatialai.org/v1/me-mgs#wellOverburden)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[StadSingleData](../classes/StadSingleData.md)&nbsp;or&nbsp;<br />[MeMgsWellOverburdenThicknessInFt](../classes/MeMgsWellOverburdenThicknessInFt.md)







## LinkML Source

<details>

```yaml
name: me_mgs_wellOverburden
from_schema: okns:hydrology-kg
rank: 1000
slot_uri: me_mgs:wellOverburden
alias: me_mgs_wellOverburden
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
- range: stad_SingleData
- range: me_mgs_WellOverburdenThicknessInFt

```
</details>