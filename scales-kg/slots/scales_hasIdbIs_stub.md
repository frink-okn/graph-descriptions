

# Slot: scales_hasIdbIs_stub


_No slot description provided_





URI: [scales:hasIdbIs_stub](http://schemas.scales-okn.org/rdf/scales#hasIdbIs_stub)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | No type description provided |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | No type description provided |  no  |







## Properties

* Range: [xsd:boolean](http://www.w3.org/2001/XMLSchema#boolean)






## Examples

| Value |
| --- |
| scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbIs_stub false |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbIs_stub false |

## Comments

* 551088 occurrences with subject type scales_CaseCivil and object type boolean.
* 111582 occurrences with subject type scales_CaseCriminal and object type boolean.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: scales-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | scales:hasIdbIs_stub |
| native | scales-kg/:scales_hasIdbIs_stub |




## LinkML Source

<details>
```yaml
name: scales_hasIdbIs_stub
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 551088 occurrences with subject type scales_CaseCivil and object type boolean.
- 111582 occurrences with subject type scales_CaseCriminal and object type boolean.
examples:
- value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbIs_stub false
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbIs_stub false
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbIs_stub
alias: scales_hasIdbIs_stub
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: boolean

```
</details>