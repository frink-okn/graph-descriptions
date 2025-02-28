

# Slot: No slot (predicate) name specified (geo_defaultGeometry)


_No slot (predicate) description specified_






This slot occurs 2225 times.


URI: [geo:defaultGeometry](http://www.opengis.net/ont/geosparql#defaultGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [KwgoAdministrativeRegion3](../classes/KwgoAdministrativeRegion3.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Sf#Polygon](../classes/Sf#Polygon.md)&nbsp;or&nbsp;<br />[GeoGeometry](../classes/GeoGeometry.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| owl_Thing | sf_#Polygon | https://datacommons.org/browser/geoId/1700105742 | http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742 | 2225 |
| owl_Thing | geo_Geometry | https://datacommons.org/browser/geoId/1700105742 | http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742 | 2225 |
| owl_Thing | owl_Thing | https://datacommons.org/browser/geoId/1700105742 | http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742 | 2225 |
| kwgo_AdministrativeRegion_3 | sf_#Polygon | https://datacommons.org/browser/geoId/1700105742 | http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742 | 2225 |
| kwgo_AdministrativeRegion_3 | geo_Geometry | https://datacommons.org/browser/geoId/1700105742 | http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742 | 2225 |
| kwgo_AdministrativeRegion_3 | owl_Thing | https://datacommons.org/browser/geoId/1700105742 | http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742 | 2225 |




## LinkML Source

<details>

```yaml
name: geo_defaultGeometry
annotations:
  count:
    tag: count
    value: 2225
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742
    example_object_type: sf_#Polygon
    example_predicate: geo:defaultGeometry
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: owl_Thing
- object:
    example_object: http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742
    example_object_type: geo_Geometry
    example_predicate: geo:defaultGeometry
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: owl_Thing
- object:
    example_object: http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742
    example_object_type: owl_Thing
    example_predicate: geo:defaultGeometry
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: owl_Thing
- object:
    example_object: http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742
    example_object_type: sf_#Polygon
    example_predicate: geo:defaultGeometry
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: kwgo_AdministrativeRegion_3
- object:
    example_object: http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742
    example_object_type: geo_Geometry
    example_predicate: geo:defaultGeometry
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: kwgo_AdministrativeRegion_3
- object:
    example_object: http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742
    example_object_type: owl_Thing
    example_predicate: geo:defaultGeometry
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: kwgo_AdministrativeRegion_3
from_schema: spatial-kg
rank: 1000
slot_uri: geo:defaultGeometry
alias: geo_defaultGeometry
domain_of:
- kwgo_AdministrativeRegion_3
- owl_Thing
range: Any
any_of:
- range: sf_#Polygon
- range: geo_Geometry
- range: owl_Thing

```
</details>