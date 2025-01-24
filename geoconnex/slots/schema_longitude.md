

# Slot: schema_longitude


_No slot (predicate) description specified_





URI: [schema:longitude](https://schema.org/longitude)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaGeoCoordinates](../classes/SchemaGeoCoordinates.md) | The geographic coordinates of a place or event |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](xsd:integer)&nbsp;or&nbsp;<br />[xsd:double](xsd:double)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_GeoCoordinates → double | _:b0 | schema:longitude | -122.7634309999998 |
| schema_GeoCoordinates → integer | _:b122821 | schema:longitude | -79 |


## Comments

* 761097 occurrences with subject type schema_GeoCoordinates and object type double.
* 69 occurrences with subject type schema_GeoCoordinates and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:longitude |
| native | geoconnex/:schema_longitude |




## LinkML Source

<details>
```yaml
name: schema_longitude
description: No slot (predicate) description specified
comments:
- 761097 occurrences with subject type schema_GeoCoordinates and object type double.
- 69 occurrences with subject type schema_GeoCoordinates and object type integer.
examples:
- description: schema_GeoCoordinates → double
  object:
    example_object: '-122.7634309999998'
    example_predicate: schema:longitude
    example_subject: _:b0
- description: schema_GeoCoordinates → integer
  object:
    example_object: '-79'
    example_predicate: schema:longitude
    example_subject: _:b122821
from_schema: geoconnex
rank: 1000
slot_uri: schema:longitude
alias: schema_longitude
domain_of:
- schema_GeoCoordinates
range: Any
any_of:
- range: integer
- range: double

```
</details>