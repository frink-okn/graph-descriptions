

# Slot: hsdo_item


_No slot (predicate) description specified_





URI: [hsdo:item](http://schema.org/item)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoListItem](../classes/HsdoListItem.md) | An list item, e |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:string](xsd:string)&nbsp;or&nbsp;<br />[HsdoWebPage](../classes/HsdoWebPage.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_ListItem → hsdo_WebPage | https://internetofwater.org/internet-of-water-principles/#listItem | hsdo:item | https://internetofwater.org/internet-of-water-principles/ |
| hsdo_ListItem → string | https://internetofwater.org/#listItem | hsdo:item | https://internetofwater.org/ |


## Comments

* 2 occurrences with subject type hsdo_ListItem and object type hsdo_WebPage.
* 1 occurrences with subject type hsdo_ListItem and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:item |
| native | geoconnex/:hsdo_item |




## LinkML Source

<details>
```yaml
name: hsdo_item
description: No slot (predicate) description specified
comments:
- 2 occurrences with subject type hsdo_ListItem and object type hsdo_WebPage.
- 1 occurrences with subject type hsdo_ListItem and object type string.
examples:
- description: hsdo_ListItem → hsdo_WebPage
  object:
    example_object: https://internetofwater.org/internet-of-water-principles/
    example_predicate: hsdo:item
    example_subject: https://internetofwater.org/internet-of-water-principles/#listItem
- description: hsdo_ListItem → string
  object:
    example_object: https://internetofwater.org/
    example_predicate: hsdo:item
    example_subject: https://internetofwater.org/#listItem
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:item
alias: hsdo_item
domain_of:
- hsdo_ListItem
range: Any
any_of:
- range: string
- range: hsdo_WebPage

```
</details>