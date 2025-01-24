

# Slot: schema_encodingFormat


_No slot (predicate) description specified_





URI: [schema:encodingFormat](https://schema.org/encodingFormat)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaDataDownload](../classes/SchemaDataDownload.md) | All or part of a [[Dataset]] in downloadable form |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_DataDownload → string | _:b1000004 | schema:encodingFormat | application/json |


## Comments

* 56432 occurrences with subject type schema_DataDownload and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:encodingFormat |
| native | geoconnex/:schema_encodingFormat |




## LinkML Source

<details>
```yaml
name: schema_encodingFormat
description: No slot (predicate) description specified
comments:
- 56432 occurrences with subject type schema_DataDownload and object type string.
examples:
- description: schema_DataDownload → string
  object:
    example_object: application/json
    example_predicate: schema:encodingFormat
    example_subject: _:b1000004
from_schema: geoconnex
rank: 1000
slot_uri: schema:encodingFormat
alias: schema_encodingFormat
domain_of:
- schema_DataDownload
range: string

```
</details>