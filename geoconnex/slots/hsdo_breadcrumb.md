

# Slot: hsdo_breadcrumb


_No slot (predicate) description specified_





URI: [hsdo:breadcrumb](http://schema.org/breadcrumb)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoWebPage](../classes/HsdoWebPage.md) | A web page |  no  |







## Properties

* Range: [HsdoBreadcrumbList](../classes/HsdoBreadcrumbList.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_WebPage → hsdo_BreadcrumbList | https://internetofwater.org/who-we-are/#webpage | hsdo:breadcrumb | https://internetofwater.org/who-we-are/#breadcrumblist |


## Comments

* 3 occurrences with subject type hsdo_WebPage and object type hsdo_BreadcrumbList.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:breadcrumb |
| native | geoconnex/:hsdo_breadcrumb |




## LinkML Source

<details>
```yaml
name: hsdo_breadcrumb
description: No slot (predicate) description specified
comments:
- 3 occurrences with subject type hsdo_WebPage and object type hsdo_BreadcrumbList.
examples:
- description: hsdo_WebPage → hsdo_BreadcrumbList
  object:
    example_object: https://internetofwater.org/who-we-are/#breadcrumblist
    example_predicate: hsdo:breadcrumb
    example_subject: https://internetofwater.org/who-we-are/#webpage
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:breadcrumb
alias: hsdo_breadcrumb
domain_of:
- hsdo_WebPage
range: hsdo_BreadcrumbList

```
</details>