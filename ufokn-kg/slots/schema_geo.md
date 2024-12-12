

# Slot: schema_geo


_No slot description provided_





URI: [schema:geo](https://schema.org/geo)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[SchemaGeoCoordinates](../classes/SchemaGeoCoordinates.md)&nbsp;or&nbsp;<br />[SchemaGeoShape](../classes/SchemaGeoShape.md)






## Examples

| Value |
| --- |
| https://ufokn.org/id/urmi/dpqwz0m0gs3b schema:geo _:69e22f093bd3d1f9a269c6454084bdb6 |
| https://ufokn.org/id/urmi/dpqwz0m0gs3b schema:geo _:92276e1da29d02ff87824f50b449812c |

## Comments

* 5858958 occurrences with subject type schema_Place and object type schema_GeoCoordinates.
* 5858958 occurrences with subject type schema_Place and object type schema_GeoShape.

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
| self | schema:geo |
| native | ufokn-kg/:schema_geo |




## LinkML Source

<details>
```yaml
name: schema_geo
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 5858958 occurrences with subject type schema_Place and object type schema_GeoCoordinates.
- 5858958 occurrences with subject type schema_Place and object type schema_GeoShape.
examples:
- value: https://ufokn.org/id/urmi/dpqwz0m0gs3b schema:geo _:69e22f093bd3d1f9a269c6454084bdb6
- value: https://ufokn.org/id/urmi/dpqwz0m0gs3b schema:geo _:92276e1da29d02ff87824f50b449812c
from_schema: ufokn-kg
rank: 1000
slot_uri: schema:geo
alias: schema_geo
domain_of:
- schema_Place
range: Any
any_of:
- range: schema_GeoCoordinates
- range: schema_GeoShape

```
</details>