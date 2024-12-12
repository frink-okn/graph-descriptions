

# Slot: No slot description provided (geo_hasDefaultGeometry)


_No slot description provided_





URI: [geo:hasDefaultGeometry](http://www.opengis.net/ont/geosparql#hasDefaultGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoPoint](../classes/ContaminosoPoint.md) | No type description provided |  no  |
| [MeegadEGAD-Site](../classes/MeegadEGAD-Site.md) | No type description provided |  no  |
| [ContaminosoFeature](../classes/ContaminosoFeature.md) | No type description provided |  no  |







## Properties

* Range: [GeoGeometry](../classes/GeoGeometry.md)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.99544 geo:hasDefaultGeometry http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.geometry.99544 |
| http://sawgraph.spatialai.org/v1/me-egad-data#site.99425 geo:hasDefaultGeometry http://sawgraph.spatialai.org/v1/me-egad-data#site.geometry.99425 |
| http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well.101783 geo:hasDefaultGeometry http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well-Geometry.101783 |

## Comments

* 4511 occurrences with subject type contaminoso_Point and object type geo_Geometry.
* 884 occurrences with subject type meegad_EGAD-Site and object type geo_Geometry.
* 999 occurrences with subject type contaminoso_Feature and object type geo_Geometry.

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
| self | geo:hasDefaultGeometry |
| native | sawgraph-kg/:geo_hasDefaultGeometry |




## LinkML Source

<details>
```yaml
name: geo_hasDefaultGeometry
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 4511 occurrences with subject type contaminoso_Point and object type geo_Geometry.
- 884 occurrences with subject type meegad_EGAD-Site and object type geo_Geometry.
- 999 occurrences with subject type contaminoso_Feature and object type geo_Geometry.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.99544 geo:hasDefaultGeometry
    http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.geometry.99544
- value: http://sawgraph.spatialai.org/v1/me-egad-data#site.99425 geo:hasDefaultGeometry
    http://sawgraph.spatialai.org/v1/me-egad-data#site.geometry.99425
- value: http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well.101783 geo:hasDefaultGeometry
    http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well-Geometry.101783
from_schema: sawgraph-kg
rank: 1000
slot_uri: geo:hasDefaultGeometry
alias: geo_hasDefaultGeometry
domain_of:
- contaminoso_Feature
- contaminoso_Point
- meegad_EGAD-Site
subproperty_of: geo_hasGeometry
range: geo_Geometry

```
</details>