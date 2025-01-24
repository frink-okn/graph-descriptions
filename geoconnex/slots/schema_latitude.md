

# Slot: schema_latitude


_No slot (predicate) description specified_





URI: [schema:latitude](https://schema.org/latitude)



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
| schema_GeoCoordinates → double | _:b0 | schema:latitude | 45.47261797 |
| schema_GeoCoordinates → integer | _:b1029348 | schema:latitude | 49 |


## Comments

* 761101 occurrences with subject type schema_GeoCoordinates and object type double.
* 65 occurrences with subject type schema_GeoCoordinates and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:latitude |
| native | geoconnex/:schema_latitude |




## LinkML Source

<details>
```yaml
name: schema_latitude
description: No slot (predicate) description specified
comments:
- 761101 occurrences with subject type schema_GeoCoordinates and object type double.
- 65 occurrences with subject type schema_GeoCoordinates and object type integer.
examples:
- description: schema_GeoCoordinates → double
  object:
    example_object: '45.47261797'
    example_predicate: schema:latitude
    example_subject: _:b0
- description: schema_GeoCoordinates → integer
  object:
    example_object: '49'
    example_predicate: schema:latitude
    example_subject: _:b1029348
from_schema: geoconnex
rank: 1000
slot_uri: schema:latitude
alias: schema_latitude
domain_of:
- schema_GeoCoordinates
range: Any
any_of:
- range: integer
- range: double

```
</details>