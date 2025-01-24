

# Slot: geo_crs


_No slot (predicate) description specified_





URI: [geo:crs](http://www.opengis.net/ont/geosparql#crs)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [Sf#Point](../classes/Sf#Point.md) | No class (type) description specified |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| sf_#Point → uri | _:b1000018 | geo:crs | http://www.opengis.net/def/crs/OGC/1.3/CRS84 |


## Comments

* 13487 occurrences with subject type sf_#Point and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | geo:crs |
| native | geoconnex/:geo_crs |




## LinkML Source

<details>
```yaml
name: geo_crs
description: No slot (predicate) description specified
comments:
- 13487 occurrences with subject type sf_#Point and object type uri.
examples:
- description: sf_#Point → uri
  object:
    example_object: http://www.opengis.net/def/crs/OGC/1.3/CRS84
    example_predicate: geo:crs
    example_subject: _:b1000018
from_schema: geoconnex
rank: 1000
slot_uri: geo:crs
alias: geo_crs
domain_of:
- sf_#Point
range: uri

```
</details>