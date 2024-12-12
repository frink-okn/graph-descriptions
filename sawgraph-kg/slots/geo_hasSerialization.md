

# Slot: No slot description provided (geo_hasSerialization)


_No slot description provided_





URI: [geo:hasSerialization](http://www.opengis.net/ont/geosparql#hasSerialization)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UssdwisPublicWaterSystem-GW](../classes/UssdwisPublicWaterSystem-GW.md) | No type description provided |  no  |
| [GeoGeometry](../classes/GeoGeometry.md) | No type description provided |  no  |
| [UssdwisPWS-SamplePoint](../classes/UssdwisPWS-SamplePoint.md) | No type description provided |  no  |
| [ContaminosoPoint](../classes/ContaminosoPoint.md) | No type description provided |  no  |
| [UssdwisPublicWaterSystem-CWS](../classes/UssdwisPublicWaterSystem-CWS.md) | No type description provided |  no  |
| [ContaminosoSamplePoint](../classes/ContaminosoSamplePoint.md) | No type description provided |  no  |
| [UssdwisCombinedDistributionSystem](../classes/UssdwisCombinedDistributionSystem.md) | No type description provided |  no  |
| [MeegadEGAD-SamplePoint](../classes/MeegadEGAD-SamplePoint.md) | No type description provided |  no  |
| [MemgsMGS-Well](../classes/MemgsMGS-Well.md) | No type description provided |  no  |
| [ContaminosoFeature](../classes/ContaminosoFeature.md) | No type description provided |  no  |
| [ContaminosoSampledFeaure](../classes/ContaminosoSampledFeaure.md) | No type description provided |  no  |
| [GeoFeature](../classes/GeoFeature.md) | No type description provided |  no  |
| [UssdwisPublicWaterSystem-TNCWS](../classes/UssdwisPublicWaterSystem-TNCWS.md) | No type description provided |  no  |
| [UssdwisPublicWaterSystem](../classes/UssdwisPublicWaterSystem.md) | No type description provided |  no  |
| [UssdwisPublicWaterSystem-NTNCWS](../classes/UssdwisPublicWaterSystem-NTNCWS.md) | No type description provided |  no  |
| [GeoSpatialObject](../classes/GeoSpatialObject.md) | No type description provided |  no  |
| [ContaminosoReleaseFeature](../classes/ContaminosoReleaseFeature.md) | No type description provided |  no  |
| [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md) | No type description provided |  no  |
| [IlisgsISGS-Well](../classes/IlisgsISGS-Well.md) | No type description provided |  no  |
| [ContaminosoReleasePoint](../classes/ContaminosoReleasePoint.md) | No type description provided |  no  |
| [UssdwisPublicWaterSystem-SW](../classes/UssdwisPublicWaterSystem-SW.md) | No type description provided |  no  |







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