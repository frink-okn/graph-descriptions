

# Slot: geo_asWKT


_No slot (predicate) description specified_






This slot occurs 6236 times.


URI: [geo:asWKT](http://www.opengis.net/ont/geosparql#asWKT)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [GeoGeometry](../classes/GeoGeometry.md) | No class (type) description specified |  no  |
| [Sf#Point](../classes/Sf#Point.md) | No class (type) description specified |  yes  |







## Properties

* Range: [GeoWktLiteral](../types/GeoWktLiteral.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sf_#Point | geo_wktLiteral | me_egad_data:egad.site.geometry.100843 | POINT (-68.83827616 44.79828519) | 6236 |




## LinkML Source

<details>

```yaml
name: geo_asWKT
annotations:
  count:
    tag: count
    value: 6236
description: No slot (predicate) description specified
examples:
- object:
    example_object: POINT (-68.83827616 44.79828519)
    example_object_type: geo_wktLiteral
    example_predicate: geo:asWKT
    example_subject: me_egad_data:egad.site.geometry.100843
    example_subject_type: sf_#Point
from_schema: sawgraph-kg
rank: 1000
slot_uri: geo:asWKT
alias: geo_asWKT
domain_of:
- geo_Geometry
- sf_#Point
range: geo_wktLiteral

```
</details>