

# Slot: hsdo_previousItem


_No slot (predicate) description specified_





URI: [hsdo:previousItem](http://schema.org/previousItem)



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
| hsdo_ListItem → string | https://internetofwater.org/internet-of-water-principles/#listItem | hsdo:previousItem | https://internetofwater.org/#listItem |


## Comments

* 2 occurrences with subject type hsdo_ListItem and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:previousItem |
| native | geoconnex/:hsdo_previousItem |




## LinkML Source

<details>
```yaml
name: hsdo_previousItem
description: No slot (predicate) description specified
comments:
- 2 occurrences with subject type hsdo_ListItem and object type string.
examples:
- description: hsdo_ListItem → string
  object:
    example_object: https://internetofwater.org/#listItem
    example_predicate: hsdo:previousItem
    example_subject: https://internetofwater.org/internet-of-water-principles/#listItem
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:previousItem
alias: hsdo_previousItem
domain_of:
- hsdo_ListItem
range: string

```
</details>