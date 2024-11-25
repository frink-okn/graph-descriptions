

# Slot: schema_name


_TODO -- tell the world what this slot (predicate) describes._





URI: [schema:name](https://schema.org/name)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |
| [SchemaPropertyValue](../classes/SchemaPropertyValue.md) | A property-value pair, e |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| _:1000004ffdfdf77e2c97998ea1e8da86 schema:name s2Level13 |
| https://ufokn.org/id/urmi/dngwmzszm7nt schema:name dngwmzszm7nt |

## Comments

* 41012706 occurrences with subject type schema_PropertyValue and object type string.
* 5839329 occurrences with subject type schema_Place and object type string.

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
| self | schema:name |
| native | ufokn-kg/:schema_name |




## LinkML Source

<details>
```yaml
name: schema_name
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 41012706 occurrences with subject type schema_PropertyValue and object type string.
- 5839329 occurrences with subject type schema_Place and object type string.
examples:
- value: _:1000004ffdfdf77e2c97998ea1e8da86 schema:name s2Level13
- value: https://ufokn.org/id/urmi/dngwmzszm7nt schema:name dngwmzszm7nt
from_schema: ufokn-kg
rank: 1000
slot_uri: schema:name
alias: schema_name
domain_of:
- schema_Place
- schema_PropertyValue
range: string

```
</details>