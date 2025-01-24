

# Slot: schema_PropertyID


_No slot (predicate) description specified_





URI: [schema:PropertyID](https://schema.org/PropertyID)



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
| schema_PropertyValue → string | _:b120265 | schema:PropertyID | hilarriid |


## Comments

* 40988 occurrences with subject type schema_PropertyValue and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:PropertyID |
| native | geoconnex/:schema_PropertyID |




## LinkML Source

<details>
```yaml
name: schema_PropertyID
description: No slot (predicate) description specified
comments:
- 40988 occurrences with subject type schema_PropertyValue and object type string.
examples:
- description: schema_PropertyValue → string
  object:
    example_object: hilarriid
    example_predicate: schema:PropertyID
    example_subject: _:b120265
from_schema: geoconnex
rank: 1000
slot_uri: schema:PropertyID
alias: schema_PropertyID
domain_of:
- schema_PropertyValue
range: string

```
</details>