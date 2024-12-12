

# Slot: No slot description provided (geo_hasGeometry)


_No slot description provided_





URI: [geo:hasGeometry](http://www.opengis.net/ont/geosparql#hasGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoPoint](../classes/ContaminosoPoint.md) | No type description provided |  no  |
| [MeegadEGAD-Site](../classes/MeegadEGAD-Site.md) | No type description provided |  no  |
| [ContaminosoFeature](../classes/ContaminosoFeature.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[GeoSpatialObject](../classes/GeoSpatialObject.md)&nbsp;or&nbsp;<br />[GeoGeometry](../classes/GeoGeometry.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.99544 geo:hasGeometry http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.geometry.99544 |
| http://sawgraph.spatialai.org/v1/me-egad-data#site.99425 geo:hasGeometry http://sawgraph.spatialai.org/v1/me-egad-data#egad.site.geometry.99425 |
| http://sawgraph.spatialai.org/v1/me-egad-data#site.99425 geo:hasGeometry http://sawgraph.spatialai.org/v1/me-egad-data#site.geometry.99425 |
| http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well.105674 geo:hasGeometry http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well-Geometry.105674 |
| http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well.99999 geo:hasGeometry http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well-Geometry.99999 |
| http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.120010000300 geo:hasGeometry http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.geometry.120010000300 |
| http://sawgraph.spatialai.org/v1/me-egad-data#site.99901 geo:hasGeometry http://sawgraph.spatialai.org/v1/me-egad-data#egad.site.geometry.99901 |

## Comments

* 4511 occurrences with subject type contaminoso_Point and object type geo_Geometry.
* 841 occurrences with subject type meegad_EGAD-Site and object type geo_SpatialObject.
* 884 occurrences with subject type meegad_EGAD-Site and object type geo_Geometry.
* 2994 occurrences with subject type contaminoso_Feature and object type geo_Geometry.
* 80056 occurrences with subject type contaminoso_Feature and object type geo_SpatialObject.
* 379496 occurrences with subject type contaminoso_Feature and object type uri.
* 24794 occurrences with untyped subjects and object type http://www.opengis.net/ont/geosparql#SpatialObject.

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
| self | geo:hasGeometry |
| native | sawgraph-kg/:geo_hasGeometry |




## LinkML Source

<details>
```yaml
name: geo_hasGeometry
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 4511 occurrences with subject type contaminoso_Point and object type geo_Geometry.
- 841 occurrences with subject type meegad_EGAD-Site and object type geo_SpatialObject.
- 884 occurrences with subject type meegad_EGAD-Site and object type geo_Geometry.
- 2994 occurrences with subject type contaminoso_Feature and object type geo_Geometry.
- 80056 occurrences with subject type contaminoso_Feature and object type geo_SpatialObject.
- 379496 occurrences with subject type contaminoso_Feature and object type uri.
- 24794 occurrences with untyped subjects and object type http://www.opengis.net/ont/geosparql#SpatialObject.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.99544 geo:hasGeometry
    http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.geometry.99544
- value: http://sawgraph.spatialai.org/v1/me-egad-data#site.99425 geo:hasGeometry
    http://sawgraph.spatialai.org/v1/me-egad-data#egad.site.geometry.99425
- value: http://sawgraph.spatialai.org/v1/me-egad-data#site.99425 geo:hasGeometry
    http://sawgraph.spatialai.org/v1/me-egad-data#site.geometry.99425
- value: http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well.105674 geo:hasGeometry
    http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well-Geometry.105674
- value: http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well.99999 geo:hasGeometry
    http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well-Geometry.99999
- value: http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.120010000300 geo:hasGeometry
    http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.geometry.120010000300
- value: http://sawgraph.spatialai.org/v1/me-egad-data#site.99901 geo:hasGeometry
    http://sawgraph.spatialai.org/v1/me-egad-data#egad.site.geometry.99901
from_schema: sawgraph-kg
rank: 1000
slot_uri: geo:hasGeometry
alias: geo_hasGeometry
domain_of:
- contaminoso_Feature
- contaminoso_Point
- meegad_EGAD-Site
range: Any
any_of:
- range: geo_SpatialObject
- range: geo_Geometry
- range: uri

```
</details>