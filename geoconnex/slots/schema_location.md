

# Slot: schema_location


_No slot (predicate) description specified_





URI: [schema:location](https://schema.org/location)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → uri | https://geoconnex.us/nmwdi/st/locations/1 | schema:location | https://gleaner.io/xid/genid/ckta2rsip8t5kr9uj7b0 |


## Comments

* 17510 occurrences with subject type schema_Place and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:location |
| native | geoconnex/:schema_location |




## LinkML Source

<details>
```yaml
name: schema_location
description: No slot (predicate) description specified
comments:
- 17510 occurrences with subject type schema_Place and object type uri.
examples:
- description: schema_Place → uri
  object:
    example_object: https://gleaner.io/xid/genid/ckta2rsip8t5kr9uj7b0
    example_predicate: schema:location
    example_subject: https://geoconnex.us/nmwdi/st/locations/1
from_schema: geoconnex
rank: 1000
slot_uri: schema:location
alias: schema_location
domain_of:
- schema_Place
range: uri

```
</details>