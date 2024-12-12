

# Slot: schema_additionalType


_No slot description provided_





URI: [schema:additionalType](https://schema.org/additionalType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [SchemaPlace](../classes/SchemaPlace.md) | Entities that have a somewhat fixed, physical extension |  no  |
| [SchemaPropertyValue](../classes/SchemaPropertyValue.md) | A property-value pair, e |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](xsd:anyURI)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)






## Examples

| Value |
| --- |
| _:1000004ffdfdf77e2c97998ea1e8da86 schema:additionalType https://stko-kwg.geog.ucsb.edu/lod/ontology#S2Cell |
| https://ufokn.org/id/urmi/dngwmzszm7nt schema:additionalType building |

## Comments

* 11717916 occurrences with subject type schema_PropertyValue and object type uri.
* 5839332 occurrences with subject type schema_Place and object type string.

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
| self | schema:additionalType |
| native | ufokn-kg/:schema_additionalType |




## LinkML Source

<details>
```yaml
name: schema_additionalType
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 11717916 occurrences with subject type schema_PropertyValue and object type uri.
- 5839332 occurrences with subject type schema_Place and object type string.
examples:
- value: _:1000004ffdfdf77e2c97998ea1e8da86 schema:additionalType https://stko-kwg.geog.ucsb.edu/lod/ontology#S2Cell
- value: https://ufokn.org/id/urmi/dngwmzszm7nt schema:additionalType building
from_schema: ufokn-kg
rank: 1000
slot_uri: schema:additionalType
alias: schema_additionalType
domain_of:
- schema_Place
- schema_PropertyValue
range: Any
any_of:
- range: uri
- range: string

```
</details>