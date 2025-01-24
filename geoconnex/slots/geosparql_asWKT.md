

# Slot: geosparql_asWKT


_No slot (predicate) description specified_





URI: [geosparql:asWKT](geosparql:asWKT)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Sf#Point](../classes/Sf#Point.md) | No class (type) description specified |  no  |







## Properties

* Range: [GeoWktLiteral](../classes/GeoWktLiteral.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| sf_#Point → geo_wktLiteral | _:b661965 | geosparql:asWKT | POINT (-122.7665757245598 38.37518704031606) |


## Comments

* 6 occurrences with subject type sf_#Point and object type geo_wktLiteral.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | geosparql:asWKT |
| native | geoconnex/:geosparql_asWKT |




## LinkML Source

<details>
```yaml
name: geosparql_asWKT
description: No slot (predicate) description specified
comments:
- 6 occurrences with subject type sf_#Point and object type geo_wktLiteral.
examples:
- description: sf_#Point → geo_wktLiteral
  object:
    example_object: POINT (-122.7665757245598 38.37518704031606)
    example_predicate: geosparql:asWKT
    example_subject: _:b661965
from_schema: geoconnex
rank: 1000
slot_uri: geosparql:asWKT
alias: geosparql_asWKT
domain_of:
- sf_#Point
range: geo_wktLiteral

```
</details>