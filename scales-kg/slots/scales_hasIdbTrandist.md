

# Slot: scales_hasIdbTrandist


_No slot description provided_





URI: [scales:hasIdbTrandist](http://schemas.scales-okn.org/rdf/scales#hasIdbTrandist)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTrandist -8 |
| scales:CaseCriminal/akd;;1:16-cr-00001 scales:hasIdbTrandist -8 |

## Comments

* 92764 occurrences with subject type scales_CaseCriminal and object type integer.
* 18818 occurrences with subject type scales_CaseCriminal and object type string.

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
| self | scales:hasIdbTrandist |
| native | scales-kg/:scales_hasIdbTrandist |




## LinkML Source

<details>
```yaml
name: scales_hasIdbTrandist
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 92764 occurrences with subject type scales_CaseCriminal and object type integer.
- 18818 occurrences with subject type scales_CaseCriminal and object type string.
examples:
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTrandist -8
- value: scales:CaseCriminal/akd;;1:16-cr-00001 scales:hasIdbTrandist -8
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTrandist
alias: scales_hasIdbTrandist
domain_of:
- scales_CaseCriminal
range: Any
any_of:
- range: integer
- range: string

```
</details>