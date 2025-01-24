

# Slot: schema_geoIntersects


_No slot (predicate) description specified_





URI: [schema:geoIntersects](https://schema.org/geoIntersects)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → string | https://geoconnex.us/ref/pws/010106001 | schema:geoIntersects | https://geoconnex.us/ref/places/ |


## Comments

* 45668 occurrences with subject type schema_Place and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:geoIntersects |
| native | geoconnex/:schema_geoIntersects |




## LinkML Source

<details>
```yaml
name: schema_geoIntersects
description: No slot (predicate) description specified
comments:
- 45668 occurrences with subject type schema_Place and object type string.
examples:
- description: schema_Place → string
  object:
    example_object: https://geoconnex.us/ref/places/
    example_predicate: schema:geoIntersects
    example_subject: https://geoconnex.us/ref/pws/010106001
from_schema: geoconnex
rank: 1000
slot_uri: schema:geoIntersects
alias: schema_geoIntersects
domain_of:
- schema_Place
range: string

```
</details>