

# Slot: schema_value


_No slot (predicate) description specified_





URI: [schema:value](https://schema.org/value)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPropertyValue](../classes/SchemaPropertyValue.md) | A property-value pair, e |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_PropertyValue → string | _:b1000020 | schema:value | 02291001 |


## Comments

* 44093 occurrences with subject type schema_PropertyValue and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:value |
| native | geoconnex/:schema_value |




## LinkML Source

<details>
```yaml
name: schema_value
description: No slot (predicate) description specified
comments:
- 44093 occurrences with subject type schema_PropertyValue and object type string.
examples:
- description: schema_PropertyValue → string
  object:
    example_object: 02291001
    example_predicate: schema:value
    example_subject: _:b1000020
from_schema: geoconnex
rank: 1000
slot_uri: schema:value
alias: schema_value
domain_of:
- schema_PropertyValue
range: string

```
</details>