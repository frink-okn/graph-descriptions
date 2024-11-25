

# Slot: schema_value


_TODO -- tell the world what this slot (predicate) describes._





URI: [schema:value](https://schema.org/value)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPropertyValue](../classes/SchemaPropertyValue.md) | A property-value pair, e |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| _:1000004ffdfdf77e2c97998ea1e8da86 schema:value 9813806808853118976 |
| _:100000653c7fb81a8400bfae61447215 schema:value 272.4525347332547 |

## Comments

* 35153748 occurrences with subject type schema_PropertyValue and object type string.
* 5858958 occurrences with subject type schema_PropertyValue and object type double.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: ufokn-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | schema:value |
| native | ufokn-kg/:schema_value |




## LinkML Source

<details>
```yaml
name: schema_value
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 35153748 occurrences with subject type schema_PropertyValue and object type string.
- 5858958 occurrences with subject type schema_PropertyValue and object type double.
examples:
- value: _:1000004ffdfdf77e2c97998ea1e8da86 schema:value 9813806808853118976
- value: _:100000653c7fb81a8400bfae61447215 schema:value 272.4525347332547
from_schema: ufokn-kg
rank: 1000
slot_uri: schema:value
alias: schema_value
domain_of:
- schema_PropertyValue
range: Any
any_of:
- range: string
- range: double

```
</details>