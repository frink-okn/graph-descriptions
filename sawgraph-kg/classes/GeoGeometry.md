

# Class: TODO -- what's a good name for this class (type)? (geo_Geometry)


_No type description provided_





URI: [geo:Geometry](http://www.opengis.net/ont/geosparql#Geometry)






```mermaid
 classDiagram
    class GeoGeometry
    click GeoGeometry href "../GeoGeometry"
      GeoSpatialObject <|-- GeoGeometry
        click GeoSpatialObject href "../GeoSpatialObject"
      
      GeoGeometry : geo_asWKT
        
          
    
    
    GeoGeometry --> "0..1" GeoWktLiteral : geo_asWKT
    click GeoWktLiteral href "../GeoWktLiteral"

        
      GeoGeometry : geo_hasSerialization
        
          
    
    
    GeoGeometry --> "0..1" GeoWktLiteral : geo_hasSerialization
    click GeoWktLiteral href "../GeoWktLiteral"

        
      
```





## Inheritance
* [GeoSpatialObject](../classes/GeoSpatialObject.md)
    * **GeoGeometry**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [geo_hasSerialization](../slots/geo_hasSerialization.md) | 0..1 <br/> [GeoWktLiteral](../classes/GeoWktLiteral.md) | No slot description provided | direct |
| [geo_asWKT](../slots/geo_asWKT.md) | 0..1 <br/> [GeoWktLiteral](../classes/GeoWktLiteral.md) | No slot description provided | direct |





## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [ContaminosoFeature](../classes/ContaminosoFeature.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | any_of[range] | [GeoGeometry](../classes/GeoGeometry.md) |
| [ContaminosoFeature](../classes/ContaminosoFeature.md) | [geo_hasDefaultGeometry](../slots/geo_hasDefaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [ContaminosoFeature](../classes/ContaminosoFeature.md) | [geo_defaultGeometry](../slots/geo_defaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [ContaminosoPoint](../classes/ContaminosoPoint.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | any_of[range] | [GeoGeometry](../classes/GeoGeometry.md) |
| [ContaminosoPoint](../classes/ContaminosoPoint.md) | [geo_hasDefaultGeometry](../slots/geo_hasDefaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |
| [MeegadEGAD-Site](../classes/MeegadEGAD-Site.md) | [geo_hasGeometry](../slots/geo_hasGeometry.md) | any_of[range] | [GeoGeometry](../classes/GeoGeometry.md) |
| [MeegadEGAD-Site](../classes/MeegadEGAD-Site.md) | [geo_hasDefaultGeometry](../slots/geo_hasDefaultGeometry.md) | range | [GeoGeometry](../classes/GeoGeometry.md) |






## TODOs

* TODO -- Todos for this class go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sawgraph-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | geo:Geometry |
| native | sawgraph-kg/:GeoGeometry |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: geo_Geometry
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 8389 occurences.
from_schema: sawgraph-kg
rank: 1000
is_a: geo_SpatialObject
slots:
- geo_hasSerialization
- geo_asWKT
class_uri: geo:Geometry

```
</details>

### Induced

<details>
```yaml
name: geo_Geometry
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 8389 occurences.
from_schema: sawgraph-kg
rank: 1000
is_a: geo_SpatialObject
attributes:
  geo_hasSerialization:
    name: geo_hasSerialization
    description: No slot description provided
    title: No slot description provided
    todos:
    - TODO -- Todos for this slot go here
    - or you can delete the todos
    - if you think the class is perfect.
    comments:
    - 379496 occurrences with untyped subjects and object type http://www.opengis.net/ont/geosparql#wktLiteral.
    - 105691 occurrences with subject type geo_SpatialObject and object type geo_wktLiteral.
    - 8389 occurrences with subject type geo_Geometry and object type geo_wktLiteral.
    examples:
    - value: http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.geometry.120010000300
        geo:hasSerialization POINT(-90.91358699999999 40.079858)
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#egad.site.geometry.100145
        geo:hasSerialization POINT (-68.07989292 46.73707407)
    - value: http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.geometry.100410
        geo:hasSerialization POINT (-69.2930289 44.5876092)
    from_schema: sawgraph-kg
    rank: 1000
    slot_uri: geo:hasSerialization
    alias: geo_hasSerialization
    owner: geo_Geometry
    domain_of:
    - geo_Geometry
    - geo_SpatialObject
    range: geo_wktLiteral
  geo_asWKT:
    name: geo_asWKT
    description: No slot description provided
    title: No slot description provided
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
    owner: geo_Geometry
    domain_of:
    - geo_Geometry
    subproperty_of: geo_hasSerialization
    range: geo_wktLiteral
class_uri: geo:Geometry

```
</details>