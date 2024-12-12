

# Slot: scales_hasIdbProbcd4


_No slot description provided_





URI: [scales:hasIdbProbcd4](http://schemas.scales-okn.org/rdf/scales#hasIdbProbcd4)



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
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbcd4 -8 |
| scales:CaseCriminal/akd;;1:16-cr-00001 scales:hasIdbProbcd4 -8 |

## Comments

* 64463 occurrences with subject type scales_CaseCriminal and object type integer.
* 47119 occurrences with subject type scales_CaseCriminal and object type string.

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
| self | scales:hasIdbProbcd4 |
| native | scales-kg/:scales_hasIdbProbcd4 |




## LinkML Source

<details>
```yaml
name: scales_hasIdbProbcd4
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 64463 occurrences with subject type scales_CaseCriminal and object type integer.
- 47119 occurrences with subject type scales_CaseCriminal and object type string.
examples:
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbProbcd4 -8
- value: scales:CaseCriminal/akd;;1:16-cr-00001 scales:hasIdbProbcd4 -8
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbProbcd4
alias: scales_hasIdbProbcd4
domain_of:
- scales_CaseCriminal
range: Any
any_of:
- range: integer
- range: string

```
</details>