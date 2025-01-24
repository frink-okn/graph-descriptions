

# Slot: schema_sameAs


_No slot (predicate) description specified_





URI: [schema:sameAs](https://schema.org/sameAs)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [SchemaPlace](../classes/SchemaPlace.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_Place → schema_Place | https://geoconnex.us/ref/principal_aq/999 | schema:sameAs | https://geoconnex.us/ref/nat_aq/N9999OTHER |


## Comments

* 118 occurrences with subject type schema_Place and object type schema_Place.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:sameAs |
| native | geoconnex/:schema_sameAs |




## LinkML Source

<details>
```yaml
name: schema_sameAs
description: No slot (predicate) description specified
comments:
- 118 occurrences with subject type schema_Place and object type schema_Place.
examples:
- description: schema_Place → schema_Place
  object:
    example_object: https://geoconnex.us/ref/nat_aq/N9999OTHER
    example_predicate: schema:sameAs
    example_subject: https://geoconnex.us/ref/principal_aq/999
from_schema: geoconnex
rank: 1000
slot_uri: schema:sameAs
alias: schema_sameAs
domain_of:
- schema_Place
range: schema_Place

```
</details>