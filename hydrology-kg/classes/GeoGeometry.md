

# Class: GeoGeometry


_A coherent set of direct positions in space. The positions are held within a Spatial Reference System (SRS)._






This class occurs 601214 times.


URI: [geo:Geometry](http://www.opengis.net/ont/geosparql#Geometry)






```mermaid
 classDiagram
    class GeoGeometry
    click GeoGeometry href "../GeoGeometry"
      GeoSpatialObject <|-- GeoGeometry
        click GeoSpatialObject href "../GeoSpatialObject"
      

      GeoGeometry <|-- Sf#LineString
        click Sf#LineString href "../Sf#LineString"
      GeoGeometry <|-- Sf#Point
        click Sf#Point href "../Sf#Point"
      
      
      
```





## Inheritance
* [GeoSpatialObject](../classes/GeoSpatialObject.md)
    * **GeoGeometry**
        * [Sf#LineString](../classes/Sf#LineString.md)
        * [Sf#Point](../classes/Sf#Point.md)



## Slots

| Name | Cardinality and Range | Description | Inheritance | Occurrences |
| ---  | --- | --- | --- | --- |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HttpGwml2.orgDefGwml2#GWAquifer](../classes/HttpGwml2.orgDefGwml2#GWAquifer.md) | [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HttpGwml2.orgDefGwml2#GWAquiferSystem](../classes/HttpGwml2.orgDefGwml2#GWAquiferSystem.md) | [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYCanal](../classes/HyfHYCanal.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYCanal](../classes/HyfHYCanal.md) | [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) | [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYElementaryFlowPath](../classes/HyfHYElementaryFlowPath.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYEstuary](../classes/HyfHYEstuary.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYEstuary](../classes/HyfHYEstuary.md) | [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYImpoundment](../classes/HyfHYImpoundment.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYImpoundment](../classes/HyfHYImpoundment.md) | [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYLagoon](../classes/HyfHYLagoon.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYLagoon](../classes/HyfHYLagoon.md) | [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYLake](../classes/HyfHYLake.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYLake](../classes/HyfHYLake.md) | [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYRiver](../classes/HyfHYRiver.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYRiver](../classes/HyfHYRiver.md) | [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYWaterBody](../classes/HyfHYWaterBody.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [HyfHYWaterBody](../classes/HyfHYWaterBody.md) | [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [IlIsgsISGS-Well](../classes/IlIsgsISGS-Well.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) | [geo_hasDefaultGeometry](../slots/geo_hasDefaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [MeMgsMGS-Well](../classes/MeMgsMGS-Well.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [Sf#MultiPolygon](../classes/Sf#MultiPolygon.md) | [geo_asWKT](../slots/geo_asWKT.md) | domain | [GeoGeometry](../classes/GeoGeometry.md) |
| [Sf#Polygon](../classes/Sf#Polygon.md) | [geo_asWKT](../slots/geo_asWKT.md) | domain | [GeoGeometry](../classes/GeoGeometry.md) |
| [UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md) | [geo_hasDefaultGeometry](../slots/geo_hasDefaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [UsSdwisPWS-ServiceArea](../classes/UsSdwisPWS-ServiceArea.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |






## Comments

* source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-class
* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-class
* source: http://www.opengis.net/ont/geosparql#
* source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-class
* source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-class
* description: A coherent set of direct positions in space. The positions are held within a Spatial Reference System (SRS).






## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>

```yaml
name: geo_Geometry
description: A coherent set of direct positions in space. The positions are held within
  a Spatial Reference System (SRS).
notes:
- Geometry can be used as a representation of the shape, extent or location of a Feature
  and may exist as a self-contained entity.
comments:
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-class'
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-class'
- 'source: http://www.opengis.net/ont/geosparql#'
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-class'
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-class'
- 'description: A coherent set of direct positions in space. The positions are held
  within a Spatial Reference System (SRS).'
from_schema: okns:geo
source: http://www.opengis.net/ont/geosparql#
is_a: geo_SpatialObject
class_uri: geo:Geometry

```
</details>

### Induced

<details>

```yaml
name: geo_Geometry
description: A coherent set of direct positions in space. The positions are held within
  a Spatial Reference System (SRS).
notes:
- Geometry can be used as a representation of the shape, extent or location of a Feature
  and may exist as a self-contained entity.
comments:
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-class'
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-class'
- 'source: http://www.opengis.net/ont/geosparql#'
- 'source: http://www.opengis.net/spec/geosparql/1.0/req/geometry-extension/geometry-class'
- 'source: http://www.opengis.net/spec/geosparql/1.1/req/geometry-extension/geometry-class'
- 'description: A coherent set of direct positions in space. The positions are held
  within a Spatial Reference System (SRS).'
from_schema: okns:geo
source: http://www.opengis.net/ont/geosparql#
is_a: geo_SpatialObject
class_uri: geo:Geometry

```
</details>