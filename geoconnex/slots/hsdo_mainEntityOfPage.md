

# Slot: hsdo_mainEntityOfPage


_No slot (predicate) description specified_





URI: [hsdo:mainEntityOfPage](http://schema.org/mainEntityOfPage)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoNewsArticle](../classes/HsdoNewsArticle.md) | A NewsArticle is an article whose content reports news, or provides backgroun... |  no  |







## Properties

* Range: [HsdoWebPage](../classes/HsdoWebPage.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_NewsArticle → hsdo_WebPage | https://gleaner.io/xid/genid/cktr9esip8ta6ev27pmg | hsdo:mainEntityOfPage | https://storymaps.arcgis.com/stories/0ecb1aaf143b4e1981dbe30f38fceec5 |


## Comments

* 2 occurrences with subject type hsdo_NewsArticle and object type hsdo_WebPage.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:mainEntityOfPage |
| native | geoconnex/:hsdo_mainEntityOfPage |




## LinkML Source

<details>
```yaml
name: hsdo_mainEntityOfPage
description: No slot (predicate) description specified
comments:
- 2 occurrences with subject type hsdo_NewsArticle and object type hsdo_WebPage.
examples:
- description: hsdo_NewsArticle → hsdo_WebPage
  object:
    example_object: https://storymaps.arcgis.com/stories/0ecb1aaf143b4e1981dbe30f38fceec5
    example_predicate: hsdo:mainEntityOfPage
    example_subject: https://gleaner.io/xid/genid/cktr9esip8ta6ev27pmg
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:mainEntityOfPage
alias: hsdo_mainEntityOfPage
domain_of:
- hsdo_NewsArticle
range: hsdo_WebPage

```
</details>