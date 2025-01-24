

# Slot: schema_propertyID


_No slot (predicate) description specified_





URI: [schema:propertyID](https://schema.org/propertyID)



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
| schema_PropertyValue → string | _:b1000007 | schema:propertyID | https://www.wikidata.org/w/index.php?search=Gage height |


## Comments

* 41704 occurrences with subject type schema_PropertyValue and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:propertyID |
| native | geoconnex/:schema_propertyID |




## LinkML Source

<details>
```yaml
name: schema_propertyID
description: No slot (predicate) description specified
comments:
- 41704 occurrences with subject type schema_PropertyValue and object type string.
examples:
- description: schema_PropertyValue → string
  object:
    example_object: https://www.wikidata.org/w/index.php?search=Gage height
    example_predicate: schema:propertyID
    example_subject: _:b1000007
from_schema: geoconnex
rank: 1000
slot_uri: schema:propertyID
alias: schema_propertyID
domain_of:
- schema_PropertyValue
range: string

```
</details>