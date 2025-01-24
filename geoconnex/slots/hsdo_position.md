

# Slot: hsdo_position


_No slot (predicate) description specified_





URI: [hsdo:position](http://schema.org/position)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoListItem](../classes/HsdoListItem.md) | An list item, e |  no  |







## Properties

* Range: [xsd:integer](xsd:integer)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_ListItem → integer | https://internetofwater.org/#listItem | hsdo:position | 1 |


## Comments

* 3 occurrences with subject type hsdo_ListItem and object type integer.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:position |
| native | geoconnex/:hsdo_position |




## LinkML Source

<details>
```yaml
name: hsdo_position
description: No slot (predicate) description specified
comments:
- 3 occurrences with subject type hsdo_ListItem and object type integer.
examples:
- description: hsdo_ListItem → integer
  object:
    example_object: '1'
    example_predicate: hsdo:position
    example_subject: https://internetofwater.org/#listItem
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:position
alias: hsdo_position
domain_of:
- hsdo_ListItem
range: integer

```
</details>