

# Slot: geo_asWKT


_No slot description provided_





URI: [geo:asWKT](http://www.opengis.net/ont/geosparql#asWKT)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaGeoShape](../classes/SchemaGeoShape.md) | The geographic shape of a place |  no  |







## Properties

* Range: [GeoWktLiteral](../classes/GeoWktLiteral.md)






## Examples

| Value |
| --- |
| _:100002217f7f477703e7dca48224c9fa geo:asWKT POINT( -81.54166702711412 39.486225178205494 69.13139343261719 ) |

## Comments

* 5858958 occurrences with subject type schema_GeoShape and object type geo_wktLiteral.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: ufokn-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | geo:asWKT |
| native | ufokn-kg/:geo_asWKT |




## LinkML Source

<details>
```yaml
name: geo_asWKT
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 5858958 occurrences with subject type schema_GeoShape and object type geo_wktLiteral.
examples:
- value: _:100002217f7f477703e7dca48224c9fa geo:asWKT POINT( -81.54166702711412 39.486225178205494
    69.13139343261719 )
from_schema: ufokn-kg
rank: 1000
slot_uri: geo:asWKT
alias: geo_asWKT
domain_of:
- schema_GeoShape
range: geo_wktLiteral

```
</details>