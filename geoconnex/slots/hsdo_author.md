

# Slot: hsdo_author


_No slot (predicate) description specified_





URI: [hsdo:author](http://schema.org/author)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoNewsArticle](../classes/HsdoNewsArticle.md) | A NewsArticle is an article whose content reports news, or provides backgroun... |  no  |







## Properties

* Range: [HsdoPerson](../classes/HsdoPerson.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_NewsArticle → hsdo_Person | https://gleaner.io/xid/genid/cktr9esip8ta6ev27pmg | hsdo:author | https://gleaner.io/xid/genid/cktr9esip8ta6ev27pn0 |


## Comments

* 2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Person.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:author |
| native | geoconnex/:hsdo_author |




## LinkML Source

<details>
```yaml
name: hsdo_author
description: No slot (predicate) description specified
comments:
- 2 occurrences with subject type hsdo_NewsArticle and object type hsdo_Person.
examples:
- description: hsdo_NewsArticle → hsdo_Person
  object:
    example_object: https://gleaner.io/xid/genid/cktr9esip8ta6ev27pn0
    example_predicate: hsdo:author
    example_subject: https://gleaner.io/xid/genid/cktr9esip8ta6ev27pmg
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:author
alias: hsdo_author
domain_of:
- hsdo_NewsArticle
range: hsdo_Person

```
</details>