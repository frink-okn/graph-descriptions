

# Slot: geo_hasGeometry


_No slot (predicate) description specified_






This slot occurs 47 times.


URI: [geo:hasGeometry](http://www.opengis.net/ont/geosparql#hasGeometry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SockgSite](../classes/SockgSite.md) | A Site represents a specific geographical location related to agricultural ac... |  yes  |







## Properties

* Range: [GeoGeometry](../classes/GeoGeometry.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| sockg_Site | geo_Geometry | sockg:individuals/231056 | sockg:individuals/geometry_ALAuburn | 47 |




## LinkML Source

<details>

```yaml
name: geo_hasGeometry
annotations:
  count:
    tag: count
    value: 47
description: No slot (predicate) description specified
examples:
- object:
    example_object: sockg:individuals/geometry_ALAuburn
    example_object_type: geo_Geometry
    example_predicate: geo:hasGeometry
    example_subject: sockg:individuals/231056
    example_subject_type: sockg_Site
from_schema: soc-kg
rank: 1000
slot_uri: geo:hasGeometry
alias: geo_hasGeometry
domain_of:
- sockg_Site
range: geo_Geometry

```
</details>