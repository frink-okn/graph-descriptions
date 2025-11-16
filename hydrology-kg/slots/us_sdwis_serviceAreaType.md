

# Slot: us_sdwis_serviceAreaType




This slot occurs 6041 times.


URI: [us_sdwis:serviceAreaType](http://sawgraph.spatialai.org/v1/us-sdwis#serviceAreaType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[UsSdwisPWS-ServiceAreaType](../classes/UsSdwisPWS-ServiceAreaType.md)







## LinkML Source

<details>

```yaml
name: us_sdwis_serviceAreaType
from_schema: okns:hydrology-kg
rank: 1000
slot_uri: us_sdwis:serviceAreaType
alias: us_sdwis_serviceAreaType
domain_of:
- us_sdwis_PWS-ServiceArea
union_of:
- geo_Feature
- owl_Thing
- geo_SpatialObject
- us_sdwis_PWS-ServiceArea
range: Any
any_of:
- range: owl_Thing
- range: us_sdwis_PWS-ServiceAreaType

```
</details>