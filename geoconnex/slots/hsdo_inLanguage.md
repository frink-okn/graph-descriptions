

# Slot: hsdo_inLanguage


_No slot (predicate) description specified_





URI: [hsdo:inLanguage](http://schema.org/inLanguage)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoWebPage](../classes/HsdoWebPage.md) | A web page |  no  |
| [HsdoWebSite](../classes/HsdoWebSite.md) | A WebSite is a set of related web pages and other items typically served from... |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_WebSite → string | https://internetofwater.org/#website | hsdo:inLanguage | en-US |
| hsdo_WebPage → string | https://internetofwater.org/#webpage | hsdo:inLanguage | en-US |


## Comments

* 1 occurrences with subject type hsdo_WebSite and object type string.
* 3 occurrences with subject type hsdo_WebPage and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:inLanguage |
| native | geoconnex/:hsdo_inLanguage |




## LinkML Source

<details>
```yaml
name: hsdo_inLanguage
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type hsdo_WebSite and object type string.
- 3 occurrences with subject type hsdo_WebPage and object type string.
examples:
- description: hsdo_WebSite → string
  object:
    example_object: en-US
    example_predicate: hsdo:inLanguage
    example_subject: https://internetofwater.org/#website
- description: hsdo_WebPage → string
  object:
    example_object: en-US
    example_predicate: hsdo:inLanguage
    example_subject: https://internetofwater.org/#webpage
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:inLanguage
alias: hsdo_inLanguage
domain_of:
- hsdo_WebPage
- hsdo_WebSite
range: string

```
</details>