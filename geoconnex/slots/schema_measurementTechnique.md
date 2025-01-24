

# Slot: schema_measurementTechnique


_No slot (predicate) description specified_





URI: [schema:measurementTechnique](https://schema.org/measurementTechnique)



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
| schema_PropertyValue → string | _:b1000007 | schema:measurementTechnique | observation |


## Comments

* 28216 occurrences with subject type schema_PropertyValue and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:measurementTechnique |
| native | geoconnex/:schema_measurementTechnique |




## LinkML Source

<details>
```yaml
name: schema_measurementTechnique
description: No slot (predicate) description specified
comments:
- 28216 occurrences with subject type schema_PropertyValue and object type string.
examples:
- description: schema_PropertyValue → string
  object:
    example_object: observation
    example_predicate: schema:measurementTechnique
    example_subject: _:b1000007
from_schema: geoconnex
rank: 1000
slot_uri: schema:measurementTechnique
alias: schema_measurementTechnique
domain_of:
- schema_PropertyValue
range: string

```
</details>