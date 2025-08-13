

# Slot: geo_asWKT


_The WKT serialization of a Geometry_






This slot occurs 980729 times.


URI: [geo:asWKT](http://www.opengis.net/ont/geosparql#asWKT)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Sf#MultiPolygon](../classes/Sf#MultiPolygon.md) |  |  no  |
| [Sf#Polygon](../classes/Sf#Polygon.md) |  |  no  |







## Properties

* Range: [GeoWktLiteral](../types/GeoWktLiteral.md)





## Comments

* source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-as-wkt-literal
* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-as-wkt-literal
* source: http://www.opengis.net/ont/geosparql#
* source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-as-wkt-literal
* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-as-wkt-literal
* description: The WKT serialization of a Geometry
* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: geo_asWKT
description: The WKT serialization of a Geometry
comments:
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-as-wkt-literal'
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-as-wkt-literal'
- 'source: http://www.opengis.net/ont/geosparql#'
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-as-wkt-literal'
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-as-wkt-literal'
- 'description: The WKT serialization of a Geometry'
- No occurrences of this slot in the graph.
from_schema: okns:geo
source: http://www.opengis.net/ont/geosparql#
domain: geo_Geometry
slot_uri: geo:asWKT
domain_of:
- sf_#MultiPolygon
- sf_#Polygon
subproperty_of: geo_hasSerialization
range: geo_wktLiteral

```
</details>