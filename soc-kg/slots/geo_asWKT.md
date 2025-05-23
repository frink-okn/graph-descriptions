

# Slot: geo_asWKT


_No slot (predicate) description specified_






This slot occurs 47 times.


URI: [geo:asWKT](http://www.opengis.net/ont/geosparql#asWKT)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [GeoGeometry](../classes/GeoGeometry.md) | No class (type) description specified |  yes  |







## Properties

* Range: [GeoWktLiteral](../types/GeoWktLiteral.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| geo_Geometry | geo_wktLiteral | sockg:individuals/geometry_ABP | POLYGON((-95.801811 45.684633, -95.799659 45.684633, -95.799659 45.687024, -95.801811 45.687024, -95.801811 45.684633)) | 47 |




## LinkML Source

<details>

```yaml
name: geo_asWKT
annotations:
  count:
    tag: count
    value: 47
description: No slot (predicate) description specified
examples:
- object:
    example_object: POLYGON((-95.801811 45.684633, -95.799659 45.684633, -95.799659
      45.687024, -95.801811 45.687024, -95.801811 45.684633))
    example_object_type: geo_wktLiteral
    example_predicate: geo:asWKT
    example_subject: sockg:individuals/geometry_ABP
    example_subject_type: geo_Geometry
from_schema: soc-kg
rank: 1000
slot_uri: geo:asWKT
alias: geo_asWKT
domain_of:
- geo_Geometry
range: geo_wktLiteral

```
</details>