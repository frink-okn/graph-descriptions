

# Slot: TODO -- tell the world what this slot (predicate) describes. (geo_asWKT)


_TODO -- tell the world what this slot (predicate) describes._





URI: [geo:asWKT](http://www.opengis.net/ont/geosparql#asWKT)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [GeoGeometry](../classes/GeoGeometry.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [GeoWktLiteral](../classes/GeoWktLiteral.md)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.geometry.120010000300 geo:asWKT POINT(-90.91358699999999 40.079858) |
| http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.geometry.100410 geo:asWKT POINT (-69.2930289 44.5876092) |

## Comments

* 379496 occurrences with untyped subjects and object type http://www.opengis.net/ont/geosparql#wktLiteral.
* 5395 occurrences with subject type geo_Geometry and object type geo_wktLiteral.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sawgraph-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | geo:asWKT |
| native | sawgraph-kg/:geo_asWKT |




## LinkML Source

<details>
```yaml
name: geo_asWKT
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 379496 occurrences with untyped subjects and object type http://www.opengis.net/ont/geosparql#wktLiteral.
- 5395 occurrences with subject type geo_Geometry and object type geo_wktLiteral.
examples:
- value: http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.geometry.120010000300
    geo:asWKT POINT(-90.91358699999999 40.079858)
- value: http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.geometry.100410
    geo:asWKT POINT (-69.2930289 44.5876092)
from_schema: sawgraph-kg
rank: 1000
slot_uri: geo:asWKT
alias: geo_asWKT
domain_of:
- geo_Geometry
subproperty_of: geo_hasSerialization
range: geo_wktLiteral

```
</details>