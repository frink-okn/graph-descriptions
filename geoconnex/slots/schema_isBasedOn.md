

# Slot: schema_isBasedOn


_No slot (predicate) description specified_





URI: [schema:isBasedOn](https://schema.org/isBasedOn)



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
| schema_Place → uri | https://geoconnex.us/ref/pws/010106001 | schema:isBasedOn | https://www.hydroshare.org/resource/9ebc0a0b43b843b9835830ffffdd971e/data/contents/temm.gpkg |


## Comments

* 85031 occurrences with subject type schema_Place and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:isBasedOn |
| native | geoconnex/:schema_isBasedOn |




## LinkML Source

<details>
```yaml
name: schema_isBasedOn
description: No slot (predicate) description specified
comments:
- 85031 occurrences with subject type schema_Place and object type uri.
examples:
- description: schema_Place → uri
  object:
    example_object: https://www.hydroshare.org/resource/9ebc0a0b43b843b9835830ffffdd971e/data/contents/temm.gpkg
    example_predicate: schema:isBasedOn
    example_subject: https://geoconnex.us/ref/pws/010106001
from_schema: geoconnex
rank: 1000
slot_uri: schema:isBasedOn
alias: schema_isBasedOn
domain_of:
- schema_Place
range: uri

```
</details>