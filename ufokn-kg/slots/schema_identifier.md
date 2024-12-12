

# Slot: schema_identifier


_No slot description provided_





URI: [schema:identifier](https://schema.org/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |
| [SchemaGeoShape](../classes/SchemaGeoShape.md) | The geographic shape of a place |  no  |







## Properties

* Range: [SchemaPropertyValue](../classes/SchemaPropertyValue.md)






## Examples

| Value |
| --- |
| _:fffffdc6eb793b0e1c71e11bd8428e09 schema:identifier _:baef8cae5e57645d663395a719965de1 |
| https://ufokn.org/id/urmi/dpqwz0m0gs3b schema:identifier _:f8339464d8bf079d34587a15afa37865 |

## Comments

* 11717916 occurrences with subject type schema_GeoShape and object type schema_PropertyValue.
* 23435832 occurrences with subject type schema_Place and object type schema_PropertyValue.

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
| self | schema:identifier |
| native | ufokn-kg/:schema_identifier |




## LinkML Source

<details>
```yaml
name: schema_identifier
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 11717916 occurrences with subject type schema_GeoShape and object type schema_PropertyValue.
- 23435832 occurrences with subject type schema_Place and object type schema_PropertyValue.
examples:
- value: _:fffffdc6eb793b0e1c71e11bd8428e09 schema:identifier _:baef8cae5e57645d663395a719965de1
- value: https://ufokn.org/id/urmi/dpqwz0m0gs3b schema:identifier _:f8339464d8bf079d34587a15afa37865
from_schema: ufokn-kg
rank: 1000
slot_uri: schema:identifier
alias: schema_identifier
domain_of:
- schema_GeoShape
- schema_Place
range: schema_PropertyValue

```
</details>