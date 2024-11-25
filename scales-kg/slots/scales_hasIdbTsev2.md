

# Slot: scales_hasIdbTsev2


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasIdbTsev2](http://schemas.scales-okn.org/rdf/scales#hasIdbTsev2)



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
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTsev2 -8 |
| scales:CaseCriminal/txsd;;2:17-cr-00501 scales:hasIdbTsev2 -8 |

## Comments

* 104516 occurrences with subject type scales_CaseCriminal and object type string.
* 7066 occurrences with subject type scales_CaseCriminal and object type integer.

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
| self | scales:hasIdbTsev2 |
| native | scales-kg/:scales_hasIdbTsev2 |




## LinkML Source

<details>
```yaml
name: scales_hasIdbTsev2
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 104516 occurrences with subject type scales_CaseCriminal and object type string.
- 7066 occurrences with subject type scales_CaseCriminal and object type integer.
examples:
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTsev2 -8
- value: scales:CaseCriminal/txsd;;2:17-cr-00501 scales:hasIdbTsev2 -8
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTsev2
alias: scales_hasIdbTsev2
domain_of:
- scales_CaseCriminal
range: Any
any_of:
- range: integer
- range: string

```
</details>