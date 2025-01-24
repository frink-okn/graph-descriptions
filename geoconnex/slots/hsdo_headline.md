

# Slot: hsdo_headline


_No slot (predicate) description specified_





URI: [hsdo:headline](http://schema.org/headline)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoNewsArticle](../classes/HsdoNewsArticle.md) | A NewsArticle is an article whose content reports news, or provides backgroun... |  no  |







## Properties

* Range: [xsd:string](xsd:string)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_NewsArticle → string | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pkg | hsdo:headline | Using the NLDI |


## Comments

* 2 occurrences with subject type hsdo_NewsArticle and object type string.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:headline |
| native | geoconnex/:hsdo_headline |




## LinkML Source

<details>
```yaml
name: hsdo_headline
description: No slot (predicate) description specified
comments:
- 2 occurrences with subject type hsdo_NewsArticle and object type string.
examples:
- description: hsdo_NewsArticle → string
  object:
    example_object: Using the NLDI
    example_predicate: hsdo:headline
    example_subject: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pkg
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:headline
alias: hsdo_headline
domain_of:
- hsdo_NewsArticle
range: string

```
</details>