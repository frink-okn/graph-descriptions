

# Slot: TODO -- tell the world what this slot (predicate) describes. (geo_hasSerialization)


_TODO -- tell the world what this slot (predicate) describes._





URI: [geo:hasSerialization](http://www.opengis.net/ont/geosparql#hasSerialization)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UssdwisPublicWaterSystem](../classes/UssdwisPublicWaterSystem.md) | TODO -- tell the world what this class (type) describes |  no  |
| [GeoGeometry](../classes/GeoGeometry.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ContaminosoPoint](../classes/ContaminosoPoint.md) | TODO -- tell the world what this class (type) describes |  no  |
| [MeegadEGAD-SamplePoint](../classes/MeegadEGAD-SamplePoint.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ContaminosoSamplePoint](../classes/ContaminosoSamplePoint.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ContaminosoFeature](../classes/ContaminosoFeature.md) | TODO -- tell the world what this class (type) describes |  no  |
| [UssdwisCombinedDistributionSystem](../classes/UssdwisCombinedDistributionSystem.md) | TODO -- tell the world what this class (type) describes |  no  |
| [UssdwisPublicWaterSystem-CWS](../classes/UssdwisPublicWaterSystem-CWS.md) | TODO -- tell the world what this class (type) describes |  no  |
| [UssdwisPublicWaterSystem-GW](../classes/UssdwisPublicWaterSystem-GW.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ContaminosoSampledFeaure](../classes/ContaminosoSampledFeaure.md) | TODO -- tell the world what this class (type) describes |  no  |
| [UssdwisPublicWaterSystem-TNCWS](../classes/UssdwisPublicWaterSystem-TNCWS.md) | TODO -- tell the world what this class (type) describes |  no  |
| [UssdwisPWS-SamplePoint](../classes/UssdwisPWS-SamplePoint.md) | TODO -- tell the world what this class (type) describes |  no  |
| [UssdwisPublicWaterSystem-NTNCWS](../classes/UssdwisPublicWaterSystem-NTNCWS.md) | TODO -- tell the world what this class (type) describes |  no  |
| [UssdwisPublicWaterSystem-SW](../classes/UssdwisPublicWaterSystem-SW.md) | TODO -- tell the world what this class (type) describes |  no  |
| [GeoFeature](../classes/GeoFeature.md) | TODO -- tell the world what this class (type) describes |  no  |
| [IlisgsISGS-Well](../classes/IlisgsISGS-Well.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ContaminosoReleasePoint](../classes/ContaminosoReleasePoint.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ContaminosoReleaseFeature](../classes/ContaminosoReleaseFeature.md) | TODO -- tell the world what this class (type) describes |  no  |
| [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md) | TODO -- tell the world what this class (type) describes |  no  |
| [GeoSpatialObject](../classes/GeoSpatialObject.md) | TODO -- tell the world what this class (type) describes |  no  |
| [MemgsMGS-Well](../classes/MemgsMGS-Well.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [GeoWktLiteral](../classes/GeoWktLiteral.md)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/il-isgs-data#d.ISGS-Well.geometry.120010000300 geo:hasSerialization POINT(-90.91358699999999 40.079858) |
| http://sawgraph.spatialai.org/v1/me-egad-data#egad.site.geometry.100145 geo:hasSerialization POINT (-68.07989292 46.73707407) |
| http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.geometry.100410 geo:hasSerialization POINT (-69.2930289 44.5876092) |

## Comments

* 379496 occurrences with untyped subjects and object type http://www.opengis.net/ont/geosparql#wktLiteral.
* 105691 occurrences with subject type geo_SpatialObject and object type geo_wktLiteral.
* 8389 occurrences with subject type geo_Geometry and object type geo_wktLiteral.

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
| self | geo:hasSerialization |
| native | sawgraph-kg/:geo_hasSerialization |




## LinkML Source

<details>
```yaml
name: geo_hasSerialization
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
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
- value: http://sawgraph.spatialai.org/v1/me-egad-data#egad.site.geometry.100145 geo:hasSerialization
    POINT (-68.07989292 46.73707407)
- value: http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.geometry.100410
    geo:hasSerialization POINT (-69.2930289 44.5876092)
from_schema: sawgraph-kg
rank: 1000
slot_uri: geo:hasSerialization
alias: geo_hasSerialization
domain_of:
- geo_Geometry
- geo_SpatialObject
range: geo_wktLiteral

```
</details>