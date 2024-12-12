

# Slot: scales_hasIdbFsev5


_No slot description provided_





URI: [scales:hasIdbFsev5](http://schemas.scales-okn.org/rdf/scales#hasIdbFsev5)



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
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFsev5 -8 |
| scales:CaseCriminal/txsd;;4:16-cr-00241 scales:hasIdbFsev5 -8 |

## Comments

* 108070 occurrences with subject type scales_CaseCriminal and object type string.
* 3512 occurrences with subject type scales_CaseCriminal and object type integer.

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
| self | scales:hasIdbFsev5 |
| native | scales-kg/:scales_hasIdbFsev5 |




## LinkML Source

<details>
```yaml
name: scales_hasIdbFsev5
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 108070 occurrences with subject type scales_CaseCriminal and object type string.
- 3512 occurrences with subject type scales_CaseCriminal and object type integer.
examples:
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFsev5 -8
- value: scales:CaseCriminal/txsd;;4:16-cr-00241 scales:hasIdbFsev5 -8
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbFsev5
alias: scales_hasIdbFsev5
domain_of:
- scales_CaseCriminal
range: Any
any_of:
- range: integer
- range: string

```
</details>