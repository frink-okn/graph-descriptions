

# Slot: scales_hasIdbTypetrn


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasIdbTypetrn](http://schemas.scales-okn.org/rdf/scales#hasIdbTypetrn)



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
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTypetrn -8 |
| scales:CaseCriminal/almd;;1:16-cr-00441 scales:hasIdbTypetrn -8 |

## Comments

* 81005 occurrences with subject type scales_CaseCriminal and object type string.
* 30577 occurrences with subject type scales_CaseCriminal and object type integer.

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
| self | scales:hasIdbTypetrn |
| native | scales-kg/:scales_hasIdbTypetrn |




## LinkML Source

<details>
```yaml
name: scales_hasIdbTypetrn
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 81005 occurrences with subject type scales_CaseCriminal and object type string.
- 30577 occurrences with subject type scales_CaseCriminal and object type integer.
examples:
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTypetrn -8
- value: scales:CaseCriminal/almd;;1:16-cr-00441 scales:hasIdbTypetrn -8
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTypetrn
alias: scales_hasIdbTypetrn
domain_of:
- scales_CaseCriminal
range: Any
any_of:
- range: integer
- range: string

```
</details>