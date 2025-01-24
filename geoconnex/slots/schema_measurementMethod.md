

# Slot: schema_measurementMethod


_No slot (predicate) description specified_





URI: [schema:measurementMethod](https://schema.org/measurementMethod)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPropertyValue](../classes/SchemaPropertyValue.md) | A property-value pair, e |  no  |







## Properties

* Range: [xsd:anyURI](xsd:anyURI)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| schema_PropertyValue → uri | _:b1000007 | schema:measurementMethod | _:b1570585 |


## Comments

* 28216 occurrences with subject type schema_PropertyValue and object type uri.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:measurementMethod |
| native | geoconnex/:schema_measurementMethod |




## LinkML Source

<details>
```yaml
name: schema_measurementMethod
description: No slot (predicate) description specified
comments:
- 28216 occurrences with subject type schema_PropertyValue and object type uri.
examples:
- description: schema_PropertyValue → uri
  object:
    example_object: _:b1570585
    example_predicate: schema:measurementMethod
    example_subject: _:b1000007
from_schema: geoconnex
rank: 1000
slot_uri: schema:measurementMethod
alias: schema_measurementMethod
domain_of:
- schema_PropertyValue
range: uri

```
</details>