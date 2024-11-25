

# Slot: scales_hasIdbTermoff


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasIdbTermoff](http://schemas.scales-okn.org/rdf/scales#hasIdbTermoff)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTermoff -8 |
| scales:CaseCriminal/cand;;1:16-cr-00325 scales:hasIdbTermoff 1 |

## Comments

* 103076 occurrences with subject type scales_CaseCriminal and object type integer.
* 8506 occurrences with subject type scales_CaseCriminal and object type string.

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
| self | scales:hasIdbTermoff |
| native | scales-kg/:scales_hasIdbTermoff |




## LinkML Source

<details>
```yaml
name: scales_hasIdbTermoff
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 103076 occurrences with subject type scales_CaseCriminal and object type integer.
- 8506 occurrences with subject type scales_CaseCriminal and object type string.
examples:
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTermoff -8
- value: scales:CaseCriminal/cand;;1:16-cr-00325 scales:hasIdbTermoff 1
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTermoff
alias: scales_hasIdbTermoff
domain_of:
- scales_CaseCriminal
range: Any
any_of:
- range: integer
- range: string

```
</details>