

# Slot: me_mgs_hasUse




This slot occurs 143400 times.


URI: [me_mgs:hasUse](http://sawgraph.spatialai.org/v1/me-mgs#hasUse)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[MeMgsWellUse](../classes/MeMgsWellUse.md)







## LinkML Source

<details>

```yaml
name: me_mgs_hasUse
from_schema: okns:hydrology-kg
exact_mappings:
- http://sawgraph.spatialai.org/v1/me-mgs#hasUse
rank: 1000
slot_uri: me_mgs:hasUse
alias: me_mgs_hasUse
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
- range: me_mgs_WellUse

```
</details>