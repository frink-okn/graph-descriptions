

# Slot: schema_description


_TODO -- tell the world what this slot (predicate) describes._





URI: [schema:description](https://schema.org/description)



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
| _:1000004ffdfdf77e2c97998ea1e8da86 schema:description S2 cell at level 13 |
| https://ufokn.org/id/urmi/dngwmzszm7nt schema:description osm:leisure:nature_reserve |

## Comments

* 17576874 occurrences with subject type schema_PropertyValue and object type string.
* 5846397 occurrences with subject type schema_Place and object type string.

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
| self | schema:description |
| native | ufokn-kg/:schema_description |




## LinkML Source

<details>
```yaml
name: schema_description
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 17576874 occurrences with subject type schema_PropertyValue and object type string.
- 5846397 occurrences with subject type schema_Place and object type string.
examples:
- value: _:1000004ffdfdf77e2c97998ea1e8da86 schema:description S2 cell at level 13
- value: https://ufokn.org/id/urmi/dngwmzszm7nt schema:description osm:leisure:nature_reserve
from_schema: ufokn-kg
rank: 1000
slot_uri: schema:description
alias: schema_description
domain_of:
- schema_Place
- schema_PropertyValue
range: string

```
</details>