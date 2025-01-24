

# Slot: hsdo_datePublished


_No slot (predicate) description specified_





URI: [hsdo:datePublished](http://schema.org/datePublished)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoWebPage](../classes/HsdoWebPage.md) | A web page |  no  |
| [HsdoNewsArticle](../classes/HsdoNewsArticle.md) | A NewsArticle is an article whose content reports news, or provides backgroun... |  no  |







## Properties

* Range: [HsdoDate](../classes/HsdoDate.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_NewsArticle → hsdo_Date | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pkg | hsdo:datePublished | 2022-04-21T03:30:52.000Z |
| hsdo_WebPage → hsdo_Date | https://internetofwater.org/#webpage | hsdo:datePublished | 2022-03-30T20:11:43-04:00 |


## Comments

* 2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Date.
* 3 occurrences with subject type hsdo_WebPage and object type hsdo_Date.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:datePublished |
| native | geoconnex/:hsdo_datePublished |




## LinkML Source

<details>
```yaml
name: hsdo_datePublished
description: No slot (predicate) description specified
comments:
- 2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Date.
- 3 occurrences with subject type hsdo_WebPage and object type hsdo_Date.
examples:
- description: hsdo_NewsArticle → hsdo_Date
  object:
    example_object: '2022-04-21T03:30:52.000Z'
    example_predicate: hsdo:datePublished
    example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pkg
- description: hsdo_WebPage → hsdo_Date
  object:
    example_object: '2022-03-30T20:11:43-04:00'
    example_predicate: hsdo:datePublished
    example_subject: https://internetofwater.org/#webpage
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:datePublished
alias: hsdo_datePublished
domain_of:
- hsdo_NewsArticle
- hsdo_WebPage
range: hsdo_Date

```
</details>