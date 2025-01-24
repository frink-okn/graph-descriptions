

# Slot: hsdo_dateModified


_No slot (predicate) description specified_





URI: [hsdo:dateModified](http://schema.org/dateModified)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoNewsArticle](../classes/HsdoNewsArticle.md) | A NewsArticle is an article whose content reports news, or provides backgroun... |  no  |
| [HsdoWebPage](../classes/HsdoWebPage.md) | A web page |  no  |







## Properties

* Range: [HsdoDate](../classes/HsdoDate.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_NewsArticle → hsdo_Date | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pkg | hsdo:dateModified | 2022-04-21T16:08:00.395Z |
| hsdo_WebPage → hsdo_Date | https://internetofwater.org/#webpage | hsdo:dateModified | 2023-07-18T14:52:28-04:00 |


## Comments

* 2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Date.
* 3 occurrences with subject type hsdo_WebPage and object type hsdo_Date.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:dateModified |
| native | geoconnex/:hsdo_dateModified |




## LinkML Source

<details>
```yaml
name: hsdo_dateModified
description: No slot (predicate) description specified
comments:
- 2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Date.
- 3 occurrences with subject type hsdo_WebPage and object type hsdo_Date.
examples:
- description: hsdo_NewsArticle → hsdo_Date
  object:
    example_object: '2022-04-21T16:08:00.395Z'
    example_predicate: hsdo:dateModified
    example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pkg
- description: hsdo_WebPage → hsdo_Date
  object:
    example_object: '2023-07-18T14:52:28-04:00'
    example_predicate: hsdo:dateModified
    example_subject: https://internetofwater.org/#webpage
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:dateModified
alias: hsdo_dateModified
domain_of:
- hsdo_NewsArticle
- hsdo_WebPage
range: hsdo_Date

```
</details>