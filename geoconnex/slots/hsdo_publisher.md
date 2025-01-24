

# Slot: hsdo_publisher


_No slot (predicate) description specified_





URI: [hsdo:publisher](http://schema.org/publisher)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoWebSite](../classes/HsdoWebSite.md) | A WebSite is a set of related web pages and other items typically served from... |  no  |
| [HsdoNewsArticle](../classes/HsdoNewsArticle.md) | A NewsArticle is an article whose content reports news, or provides backgroun... |  no  |







## Properties

* Range: [HsdoOrganization](../classes/HsdoOrganization.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_WebSite → hsdo_Organization | https://internetofwater.org/#website | hsdo:publisher | https://internetofwater.org/#organization |
| hsdo_NewsArticle → hsdo_Organization | https://gleaner.io/xid/genid/cktr9esip8ta6ev27pmg | hsdo:publisher | https://gleaner.io/xid/genid/cktr9esip8ta6ev27png |


## Comments

* 1 occurrences with subject type hsdo_WebSite and object type hsdo_Organization.
* 2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Organization.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:publisher |
| native | geoconnex/:hsdo_publisher |




## LinkML Source

<details>
```yaml
name: hsdo_publisher
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type hsdo_WebSite and object type hsdo_Organization.
- 2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Organization.
examples:
- description: hsdo_WebSite → hsdo_Organization
  object:
    example_object: https://internetofwater.org/#organization
    example_predicate: hsdo:publisher
    example_subject: https://internetofwater.org/#website
- description: hsdo_NewsArticle → hsdo_Organization
  object:
    example_object: https://gleaner.io/xid/genid/cktr9esip8ta6ev27png
    example_predicate: hsdo:publisher
    example_subject: https://gleaner.io/xid/genid/cktr9esip8ta6ev27pmg
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:publisher
alias: hsdo_publisher
domain_of:
- hsdo_NewsArticle
- hsdo_WebSite
range: hsdo_Organization

```
</details>