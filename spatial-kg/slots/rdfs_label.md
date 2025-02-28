

# Slot: No slot (predicate) name specified (rdfs_label)


_No slot (predicate) description specified_






This slot occurs 503708 times.


URI: [rdfs:label](http://www.w3.org/2000/01/rdf-schema#label)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [KwgoAdministrativeRegion1](../classes/KwgoAdministrativeRegion1.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [KwgoAdministrativeRegion3](../classes/KwgoAdministrativeRegion3.md) | No class (type) description specified |  yes  |
| [KwgoAdministrativeRegion2](../classes/KwgoAdministrativeRegion2.md) | No class (type) description specified |  yes  |
| [Sf#Polygon](../classes/Sf#Polygon.md) | No class (type) description specified |  yes  |
| [KwgoS2CellLevel13](../classes/KwgoS2CellLevel13.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  no  |
| [GeoGeometry](../classes/GeoGeometry.md) | No class (type) description specified |  yes  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| geo_Geometry | string | http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742 | Geometry of Beverly township, Illinois | 251854 |
| sf_#Polygon | string | http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742 | Geometry of Beverly township, Illinois | 251736 |
| owl_Thing | string | http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742 | Geometry of Beverly township, Illinois | 503708 |
| kwgo_AdministrativeRegion_1 | string | kwgr:administrativeRegion.USA.17 | Illinois | 2 |
| kwgo_AdministrativeRegion_2 | string | kwgr:administrativeRegion.USA.17001 | Adams County, Illinois | 118 |
| kwgo_S2Cell_Level13 | string | kwgr:s2.level13.5522341869704445952 | S2 Cell at level 13 with ID 5522341869704445952 | 249509 |
| kwgo_AdministrativeRegion_3 | string | https://datacommons.org/browser/geoId/1700105742 | Beverly township, Illinois | 2225 |




## LinkML Source

<details>

```yaml
name: rdfs_label
annotations:
  count:
    tag: count
    value: 503708
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: Geometry of Beverly township, Illinois
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742
    example_subject_type: geo_Geometry
- object:
    example_object: Geometry of Beverly township, Illinois
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742
    example_subject_type: sf_#Polygon
- object:
    example_object: Geometry of Beverly township, Illinois
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: http://sawgraph.spatialai.org/v1/saw_geo#d.Polygon.administrativeRegion.USA.1700105742
    example_subject_type: owl_Thing
- object:
    example_object: Illinois
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: kwgr:administrativeRegion.USA.17
    example_subject_type: kwgo_AdministrativeRegion_1
- object:
    example_object: Adams County, Illinois
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: kwgr:administrativeRegion.USA.17001
    example_subject_type: kwgo_AdministrativeRegion_2
- object:
    example_object: S2 Cell at level 13 with ID 5522341869704445952
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: kwgr:s2.level13.5522341869704445952
    example_subject_type: kwgo_S2Cell_Level13
- object:
    example_object: Beverly township, Illinois
    example_object_type: string
    example_predicate: rdfs:label
    example_subject: https://datacommons.org/browser/geoId/1700105742
    example_subject_type: kwgo_AdministrativeRegion_3
from_schema: spatial-kg
rank: 1000
slot_uri: rdfs:label
alias: rdfs_label
domain_of:
- geo_Geometry
- kwgo_AdministrativeRegion_1
- kwgo_AdministrativeRegion_2
- kwgo_AdministrativeRegion_3
- kwgo_S2Cell_Level13
- owl_Thing
- sf_#Polygon
range: Any
any_of:
- range: string
- range: uri

```
</details>