

# Slot: TODO -- tell the world what this slot (predicate) describes. (geo_defaultGeometry)


_TODO -- tell the world what this slot (predicate) describes._





URI: [geo:defaultGeometry](http://www.opengis.net/ont/geosparql#defaultGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoFeature](../classes/ContaminosoFeature.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [GeoGeometry](../classes/GeoGeometry.md)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well.101783 geo:defaultGeometry http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well-Geometry.101783 |

## Comments

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
| self | geo:defaultGeometry |
| native | sawgraph-kg/:geo_defaultGeometry |




## LinkML Source

<details>
```yaml
name: geo_defaultGeometry
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 999 occurrences with subject type contaminoso_Feature and object type geo_Geometry.
examples:
- value: http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well.101783 geo:defaultGeometry
    http://sawgraph.spatialai.org/v1/me-mgs-data#d.MGS-Well-Geometry.101783
from_schema: sawgraph-kg
rank: 1000
slot_uri: geo:defaultGeometry
alias: geo_defaultGeometry
domain_of:
- contaminoso_Feature
subproperty_of: geo_hasGeometry
range: geo_Geometry

```
</details>