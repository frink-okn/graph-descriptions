

# Class: TODO -- what's a good name for this class (type)? (contaminoso_SampledFeaure)


_No type description provided_





URI: [contaminoso:SampledFeaure](http://sawgraph.spatialai.org/v1/contaminoso#SampledFeaure)






```mermaid
 classDiagram
    class ContaminosoSampledFeaure
    click ContaminosoSampledFeaure href "../ContaminosoSampledFeaure"
      GeoSpatialObject <|-- ContaminosoSampledFeaure
        click GeoSpatialObject href "../GeoSpatialObject"
      
      ContaminosoSampledFeaure : geo_hasSerialization
        
          
    
    
    ContaminosoSampledFeaure --> "0..1" GeoWktLiteral : geo_hasSerialization
    click GeoWktLiteral href "../GeoWktLiteral"

        
      
```





## Inheritance
* [GeoSpatialObject](../classes/GeoSpatialObject.md)
    * **ContaminosoSampledFeaure**



## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [geo_hasSerialization](../slots/geo_hasSerialization.md) | 0..1 <br/> [GeoWktLiteral](../classes/GeoWktLiteral.md) | No slot description provided | [GeoSpatialObject](../classes/GeoSpatialObject.md) |









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
| self | contaminoso:SampledFeaure |
| native | sawgraph-kg/:ContaminosoSampledFeaure |







## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: contaminoso_SampledFeaure
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
from_schema: sawgraph-kg
rank: 1000
is_a: geo_SpatialObject
class_uri: contaminoso:SampledFeaure

```
</details>

### Induced

<details>
```yaml
name: contaminoso_SampledFeaure
description: No type description provided
title: TODO -- what's a good name for this class (type)?
todos:
- TODO -- Todos for this class go here
- or you can delete the todos
- if you think the class is perfect.
notes:
- Class with 0 occurences.
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
    owner: contaminoso_SampledFeaure
    domain_of:
    - geo_Geometry
    - geo_SpatialObject
    range: geo_wktLiteral
class_uri: contaminoso:SampledFeaure

```
</details>