

# Slot: hsdo_itemListElement


_No slot (predicate) description specified_





URI: [hsdo:itemListElement](http://schema.org/itemListElement)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoBreadcrumbList](../classes/HsdoBreadcrumbList.md) | A BreadcrumbList is an ItemList consisting of a chain of linked Web pages, ty... |  no  |







## Properties

* Range: [HsdoListItem](../classes/HsdoListItem.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_BreadcrumbList → hsdo_ListItem | https://internetofwater.org/who-we-are/#breadcrumblist | hsdo:itemListElement | https://internetofwater.org/who-we-are/#listItem |


## Comments

* 5 occurrences with subject type hsdo_BreadcrumbList and object type hsdo_ListItem.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:itemListElement |
| native | geoconnex/:hsdo_itemListElement |




## LinkML Source

<details>
```yaml
name: hsdo_itemListElement
description: No slot (predicate) description specified
comments:
- 5 occurrences with subject type hsdo_BreadcrumbList and object type hsdo_ListItem.
examples:
- description: hsdo_BreadcrumbList → hsdo_ListItem
  object:
    example_object: https://internetofwater.org/who-we-are/#listItem
    example_predicate: hsdo:itemListElement
    example_subject: https://internetofwater.org/who-we-are/#breadcrumblist
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:itemListElement
alias: hsdo_itemListElement
domain_of:
- hsdo_BreadcrumbList
range: hsdo_ListItem

```
</details>