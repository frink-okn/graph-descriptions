

# Slot: geo_hasGeometry


_No slot (predicate) description specified_





URI: [geo:hasGeometry](http://www.opengis.net/ont/geosparql#hasGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |
| [HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation](../classes/HttpWww.opengeospatial.orgStandardsWaterml2HyFeaturesHYHydroLocation.md) | No class (type) description specified |  no  |
| [HyfHYHydroLocation](../classes/HyfHYHydroLocation.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Sf#LineString](../classes/Sf#LineString.md)&nbsp;or&nbsp;<br />[Sf#Point](../classes/Sf#Point.md)&nbsp;or&nbsp;<br />[Sf#GeometryCollection](../classes/Sf#GeometryCollection.md)&nbsp;or&nbsp;<br />[Sf#MultiPolygon](../classes/Sf#MultiPolygon.md)&nbsp;or&nbsp;<br />[Sf#Polygon](../classes/Sf#Polygon.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → sf_#MultiPolygon | https://geoconnex.us/ref/ua10/98263 | geo:hasGeometry | https://gleaner.io/xid/genid/crht3s93cv0c73e1d15g |
| schema_Place → sf_#LineString | https://geoconnex.us/ref/mainstems/99895 | geo:hasGeometry | https://gleaner.io/xid/genid/cks4khsip8tc7lvlbq90 |
| schema_Place → sf_#Polygon | https://geoconnex.us/ref/pws/WY5680103 | geo:hasGeometry | _:b783557 |
| schema_Place → sf_#Point | https://sta.geoconnex.dev/collections/WQIE-WQP/Datastreams/items/'007ab627-00bf-f48c-a27c-d1af60f4e3c6' | geo:hasGeometry | _:b842331 |
| hyf__HY_HydroLocation → sf_#Point | https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900' | geo:hasGeometry | _:b850485 |
| http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation → sf_#Point | https://geoconnex.us/ornl/hydrosource/dams/999 | geo:hasGeometry | https://gleaner.io/xid/genid/ckh8pd4ip8t5ksin2050 |
| schema_Place → sf_#GeometryCollection | https://geoconnex.us/ref/pws/SC0720003 | geo:hasGeometry | _:b163095 |


## Comments

* 319697 occurrences with subject type schema_Place and object type sf_#MultiPolygon.
* 101786 occurrences with subject type schema_Place and object type sf_#LineString.
* 32790 occurrences with subject type schema_Place and object type sf_#Polygon.
* 200617 occurrences with subject type schema_Place and object type sf_#Point.
* 387017 occurrences with subject type hyf__HY_HydroLocation and object type sf_#Point.
* 10247 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation and object type sf_#Point.
* 5 occurrences with subject type schema_Place and object type sf_#GeometryCollection.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | geo:hasGeometry |
| native | geoconnex/:geo_hasGeometry |




## LinkML Source

<details>
```yaml
name: geo_hasGeometry
description: No slot (predicate) description specified
comments:
- 319697 occurrences with subject type schema_Place and object type sf_#MultiPolygon.
- 101786 occurrences with subject type schema_Place and object type sf_#LineString.
- 32790 occurrences with subject type schema_Place and object type sf_#Polygon.
- 200617 occurrences with subject type schema_Place and object type sf_#Point.
- 387017 occurrences with subject type hyf__HY_HydroLocation and object type sf_#Point.
- 10247 occurrences with subject type http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
  and object type sf_#Point.
- 5 occurrences with subject type schema_Place and object type sf_#GeometryCollection.
examples:
- description: schema_Place → sf_#MultiPolygon
  object:
    example_object: https://gleaner.io/xid/genid/crht3s93cv0c73e1d15g
    example_predicate: geo:hasGeometry
    example_subject: https://geoconnex.us/ref/ua10/98263
- description: schema_Place → sf_#LineString
  object:
    example_object: https://gleaner.io/xid/genid/cks4khsip8tc7lvlbq90
    example_predicate: geo:hasGeometry
    example_subject: https://geoconnex.us/ref/mainstems/99895
- description: schema_Place → sf_#Polygon
  object:
    example_object: _:b783557
    example_predicate: geo:hasGeometry
    example_subject: https://geoconnex.us/ref/pws/WY5680103
- description: schema_Place → sf_#Point
  object:
    example_object: _:b842331
    example_predicate: geo:hasGeometry
    example_subject: https://sta.geoconnex.dev/collections/WQIE-WQP/Datastreams/items/'007ab627-00bf-f48c-a27c-d1af60f4e3c6'
- description: hyf__HY_HydroLocation → sf_#Point
  object:
    example_object: _:b850485
    example_predicate: geo:hasGeometry
    example_subject: https://sta.geoconnex.dev/collections/USGS/Things/items/'USNWS-390855089210900'
- description: http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
    → sf_#Point
  object:
    example_object: https://gleaner.io/xid/genid/ckh8pd4ip8t5ksin2050
    example_predicate: geo:hasGeometry
    example_subject: https://geoconnex.us/ornl/hydrosource/dams/999
- description: schema_Place → sf_#GeometryCollection
  object:
    example_object: _:b163095
    example_predicate: geo:hasGeometry
    example_subject: https://geoconnex.us/ref/pws/SC0720003
from_schema: geoconnex
rank: 1000
slot_uri: geo:hasGeometry
alias: geo_hasGeometry
domain_of:
- http___www.opengeospatial.org_standards_waterml2_hy_features_HY_HydroLocation
- hyf__HY_HydroLocation
- schema_Place
range: Any
any_of:
- range: sf_#LineString
- range: sf_#Point
- range: sf_#GeometryCollection
- range: sf_#MultiPolygon
- range: sf_#Polygon

```
</details>