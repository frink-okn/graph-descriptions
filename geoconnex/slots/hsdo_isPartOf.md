

# Slot: hsdo_isPartOf


_No slot (predicate) description specified_





URI: [hsdo:isPartOf](http://schema.org/isPartOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoWebPage](../classes/HsdoWebPage.md) | A web page |  no  |







## Properties

* Range: [HsdoWebSite](../classes/HsdoWebSite.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_WebPage → hsdo_WebSite | https://internetofwater.org/who-we-are/#webpage | hsdo:isPartOf | https://internetofwater.org/#website |


## Comments

* 3 occurrences with subject type hsdo_WebPage and object type hsdo_WebSite.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:isPartOf |
| native | geoconnex/:hsdo_isPartOf |




## LinkML Source

<details>
```yaml
name: hsdo_isPartOf
description: No slot (predicate) description specified
comments:
- 3 occurrences with subject type hsdo_WebPage and object type hsdo_WebSite.
examples:
- description: hsdo_WebPage → hsdo_WebSite
  object:
    example_object: https://internetofwater.org/#website
    example_predicate: hsdo:isPartOf
    example_subject: https://internetofwater.org/who-we-are/#webpage
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:isPartOf
alias: hsdo_isPartOf
domain_of:
- hsdo_WebPage
range: hsdo_WebSite

```
</details>