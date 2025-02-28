

# Slot: No slot (predicate) name specified (geo_hasDefaultGeometry)


_No slot (predicate) description specified_






This slot occurs 249629 times.


URI: [geo:hasDefaultGeometry](http://www.opengis.net/ont/geosparql#hasDefaultGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [KwgoAdministrativeRegion1](../classes/KwgoAdministrativeRegion1.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md) | No class (type) description specified |  yes  |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[Sf#Polygon](../classes/Sf#Polygon.md)&nbsp;or&nbsp;<br />[GeoGeometry](../classes/GeoGeometry.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| kwgo_AdministrativeRegion_1 | sf_#Polygon | kwgr:administrativeRegion.USA.17 | kwgr:geometry.Polygon.administrativeRegion.USA.17 | 2 |
| kwgo_AdministrativeRegion_1 | geo_Geometry | kwgr:administrativeRegion.USA.17 | kwgr:geometry.Polygon.administrativeRegion.USA.17 | 2 |
| kwgo_AdministrativeRegion_1 | owl_Thing | kwgr:administrativeRegion.USA.17 | kwgr:geometry.Polygon.administrativeRegion.USA.17 | 2 |
| owl_Thing | sf_#Polygon | kwgr:administrativeRegion.USA.17 | kwgr:geometry.Polygon.administrativeRegion.USA.17 | 249511 |
| owl_Thing | geo_Geometry | kwgr:administrativeRegion.USA.17 | kwgr:geometry.Polygon.administrativeRegion.USA.17 | 249629 |
| owl_Thing | owl_Thing | kwgr:administrativeRegion.USA.17 | kwgr:geometry.Polygon.administrativeRegion.USA.17 | 249629 |
| kwgo_AdministrativeRegion_2 | geo_Geometry | kwgr:administrativeRegion.USA.17001 | kwgr:geometry.Polygon.administrativeRegion.USA.17001 | 118 |
| kwgo_AdministrativeRegion_2 | owl_Thing | kwgr:administrativeRegion.USA.17001 | kwgr:geometry.Polygon.administrativeRegion.USA.17001 | 118 |
| kwgo_S2Cell_Level13 | sf_#Polygon | kwgr:s2.level13.5522341869704445952 | kwgr:geometry.polygon.s2.level13.5522341869704445952 | 249509 |
| kwgo_S2Cell_Level13 | geo_Geometry | kwgr:s2.level13.5522341869704445952 | kwgr:geometry.polygon.s2.level13.5522341869704445952 | 249509 |
| kwgo_S2Cell_Level13 | owl_Thing | kwgr:s2.level13.5522341869704445952 | kwgr:geometry.polygon.s2.level13.5522341869704445952 | 249509 |




## LinkML Source

<details>

```yaml
name: geo_hasDefaultGeometry
annotations:
  count:
    tag: count
    value: 249629
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: kwgr:geometry.Polygon.administrativeRegion.USA.17
    example_object_type: sf_#Polygon
    example_predicate: geo:hasDefaultGeometry
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: kwgo_AdministrativeRegion_1
- object:
    example_object: kwgr:geometry.Polygon.administrativeRegion.USA.17
    example_object_type: geo_Geometry
    example_predicate: geo:hasDefaultGeometry
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: kwgo_AdministrativeRegion_1
- object:
    example_object: kwgr:geometry.Polygon.administrativeRegion.USA.17
    example_object_type: owl_Thing
    example_predicate: geo:hasDefaultGeometry
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: kwgo_AdministrativeRegion_1
- object:
    example_object: kwgr:geometry.Polygon.administrativeRegion.USA.17
    example_object_type: sf_#Polygon
    example_predicate: geo:hasDefaultGeometry
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:geometry.Polygon.administrativeRegion.USA.17
    example_object_type: geo_Geometry
    example_predicate: geo:hasDefaultGeometry
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:geometry.Polygon.administrativeRegion.USA.17
    example_object_type: owl_Thing
    example_predicate: geo:hasDefaultGeometry
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: owl_Thing
- object:
    example_object: kwgr:geometry.Polygon.administrativeRegion.USA.17001
    example_object_type: geo_Geometry
    example_predicate: geo:hasDefaultGeometry
    example_subject: kwgr:administrativeRegion.USA.17001
    example_subject_type: kwgo_AdministrativeRegion_2
- object:
    example_object: kwgr:geometry.Polygon.administrativeRegion.USA.17001
    example_object_type: owl_Thing
    example_predicate: geo:hasDefaultGeometry
    example_subject: kwgr:administrativeRegion.USA.17001
    example_subject_type: kwgo_AdministrativeRegion_2
- object:
    example_object: kwgr:geometry.polygon.s2.level13.5522341869704445952
    example_object_type: sf_#Polygon
    example_predicate: geo:hasDefaultGeometry
    example_subject: kwgr:s2.level13.5522341869704445952
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: kwgr:geometry.polygon.s2.level13.5522341869704445952
    example_object_type: geo_Geometry
    example_predicate: geo:hasDefaultGeometry
    example_subject: kwgr:s2.level13.5522341869704445952
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: kwgr:geometry.polygon.s2.level13.5522341869704445952
    example_object_type: owl_Thing
    example_predicate: geo:hasDefaultGeometry
    example_subject: kwgr:s2.level13.5522341869704445952
    example_subject_type: kwgo_S2Cell_Level13
from_schema: spatial-kg
rank: 1000
slot_uri: geo:hasDefaultGeometry
alias: geo_hasDefaultGeometry
domain_of:
- kwgo_AdministrativeRegion_1
- kwgo_AdministrativeRegion_2
- kwgo_S2Cell_Level13
- owl_Thing
range: Any
any_of:
- range: sf_#Polygon
- range: geo_Geometry
- range: owl_Thing

```
</details>