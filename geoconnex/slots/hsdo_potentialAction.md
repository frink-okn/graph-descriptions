

# Slot: hsdo_potentialAction


_No slot (predicate) description specified_





URI: [hsdo:potentialAction](http://schema.org/potentialAction)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [HsdoWebSite](../classes/HsdoWebSite.md) | A WebSite is a set of related web pages and other items typically served from... |  no  |







## Properties

* Range: [HsdoSearchAction](../classes/HsdoSearchAction.md)






## Examples

| Types involved | Subject | Predicate | Object |
| --- | --- | --- | --- |
| hsdo_WebSite → hsdo_SearchAction | https://internetofwater.org/#website | hsdo:potentialAction | https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pjg |


## Comments

* 1 occurrences with subject type hsdo_WebSite and object type hsdo_SearchAction.

## Identifier and Mapping Information







### Schema Source


* from schema: geoconnex




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | hsdo:potentialAction |
| native | geoconnex/:hsdo_potentialAction |




## LinkML Source

<details>
```yaml
name: hsdo_potentialAction
description: No slot (predicate) description specified
comments:
- 1 occurrences with subject type hsdo_WebSite and object type hsdo_SearchAction.
examples:
- description: hsdo_WebSite → hsdo_SearchAction
  object:
    example_object: https://gleaner.io/xid/genid/cktr9ekip8ta6ev27pjg
    example_predicate: hsdo:potentialAction
    example_subject: https://internetofwater.org/#website
from_schema: geoconnex
rank: 1000
slot_uri: hsdo:potentialAction
alias: hsdo_potentialAction
domain_of:
- hsdo_WebSite
range: hsdo_SearchAction

```
</details>