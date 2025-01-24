

# Slot: schema_geo


_No slot (predicate) description specified_





URI: [schema:geo](https://schema.org/geo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |
| [HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation](../classes/HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation.md) | No class (type) description specified |  no  |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SchemaGeoShape](../classes/SchemaGeoShape.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[SchemaGeoCoordinates](../classes/SchemaGeoCoordinates.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → schema_GeoShape | https://geoconnex.us/ref/ua10/98263 | schema:geo | https://gleaner.io/xid/genid/crht3s93cv0c73e1d160 |
| schema_Place → uri | https://geoconnex.us/ref/hu02/01 | schema:geo | _:b1546204 |
| None → schema_GeoCoordinates | https://gleaner.io/xid/genid/cl2fdb4ip8tadg8qd0ug | schema:geo | https://gleaner.io/xid/genid/cl2fdb4ip8tadg8qd0u0 |
| schema_Place → schema_GeoCoordinates | https://sta.geoconnex.dev/collections/WQIE-WQP/Datastreams/items/'007ab627-00bf-f48c-a27c-d1af60f4e3c6' | schema:geo | _:b842332 |
| http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation → schema_GeoCoordinates | https://geoconnex.us/ornl/hydrosource/dams/999 | schema:geo | https://gleaner.io/xid/genid/ckh8pd4ip8t5ksin205g |
| hyf__HY_HydroLocation → schema_GeoCoordinates | https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900' | schema:geo | _:b850486 |


## Comments

* 427661 occurrences with subject type schema_Place and object type schema_GeoShape.
* 1944 occurrences with subject type schema_Place and object type uri.
* 6 occurrences with untyped subjects and object type schema:GeoCoordinates.
* 200804 occurrences with subject type schema_Place and object type schema_GeoCoordinates.
* 10247 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type schema_GeoCoordinates.
* 385003 occurrences with subject type hyf__HY_HydroLocation and object type schema_GeoCoordinates.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:geo |
| native | geoconnex/:schema_geo |




## LinkML Source

<details>
```yaml
name: schema_geo
description: No slot (predicate) description specified
comments:
- 427661 occurrences with subject type schema_Place and object type schema_GeoShape.
- 1944 occurrences with subject type schema_Place and object type uri.
- 6 occurrences with untyped subjects and object type schema:GeoCoordinates.
- 200804 occurrences with subject type schema_Place and object type schema_GeoCoordinates.
- 10247 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
  and object type schema_GeoCoordinates.
- 385003 occurrences with subject type hyf__HY_HydroLocation and object type schema_GeoCoordinates.
examples:
- description: schema_Place → schema_GeoShape
  object:
    example_object: https://gleaner.io/xid/genid/crht3s93cv0c73e1d160
    example_predicate: schema:geo
    example_subject: https://geoconnex.us/ref/ua10/98263
- description: schema_Place → uri
  object:
    example_object: _:b1546204
    example_predicate: schema:geo
    example_subject: https://geoconnex.us/ref/hu02/01
- description: None → schema_GeoCoordinates
  object:
    example_object: https://gleaner.io/xid/genid/cl2fdb4ip8tadg8qd0u0
    example_predicate: schema:geo
    example_subject: https://gleaner.io/xid/genid/cl2fdb4ip8tadg8qd0ug
- description: schema_Place → schema_GeoCoordinates
  object:
    example_object: _:b842332
    example_predicate: schema:geo
    example_subject: https://sta.geoconnex.dev/collections/WQIE-WQP/Datastreams/items/'007ab627-00bf-f48c-a27c-d1af60f4e3c6'
- description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    → schema_GeoCoordinates
  object:
    example_object: https://gleaner.io/xid/genid/ckh8pd4ip8t5ksin205g
    example_predicate: schema:geo
    example_subject: https://geoconnex.us/ornl/hydrosource/dams/999
- description: hyf__HY_HydroLocation → schema_GeoCoordinates
  object:
    example_object: _:b850486
    example_predicate: schema:geo
    example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900'
from_schema: geoconnex
rank: 1000
slot_uri: schema:geo
alias: schema_geo
domain_of:
- http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
- hyf__HY_HydroLocation
- schema_Place
range: Any
any_of:
- range: schema_GeoShape
- range: uri
- range: schema_GeoCoordinates

```
</details>