

# Slot: hsdo_nextItem


_No slot (predicate) description specified_





URI: [hsdo:nextItem](http://schema.org/nextItem)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoListItem](../classes/HsdoListItem.md) | An list item, e |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_ListItem → string | https://internetofwater.org/#listItem | hsdo:nextItem | https://internetofwater.org/internet-of-water-principles/#listItem |


## Comments

* 2 occurrences with subject type hsdo_ListItem and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:nextItem |
| native | geoconnex/:hsdo_nextItem |




## LinkML Source

<details>
```yaml
name: hsdo_nextItem
description: No slot (predicate) description specified
comments:
- 2 occurrences with subject type hsdo_ListItem and object type string.
examples:
- description: hsdo_ListItem → string
  object:
    example_object: https://internetofwater.org/internet-of-water-principles/#listItem
    example_predicate: hsdo:nextItem
    example_subject: https://internetofwater.org/#listItem
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:nextItem
alias: hsdo_nextItem
domain_of:
- hsdo_ListItem
range: string

```
</details>