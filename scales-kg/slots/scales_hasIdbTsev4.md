

# Slot: scales_hasIdbTsev4


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasIdbTsev4](http://schemas.scales-okn.org/rdf/scales#hasIdbTsev4)



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
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTsev4 -8 |
| scales:CaseCriminal/ared;;4:16-cr-00001 scales:hasIdbTsev4 -8 |

## Comments

* 99020 occurrences with subject type scales_CaseCriminal and object type string.
* 12562 occurrences with subject type scales_CaseCriminal and object type integer.

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
| self | scales:hasIdbTsev4 |
| native | scales-kg/:scales_hasIdbTsev4 |




## LinkML Source

<details>
```yaml
name: scales_hasIdbTsev4
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 99020 occurrences with subject type scales_CaseCriminal and object type string.
- 12562 occurrences with subject type scales_CaseCriminal and object type integer.
examples:
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTsev4 -8
- value: scales:CaseCriminal/ared;;4:16-cr-00001 scales:hasIdbTsev4 -8
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTsev4
alias: scales_hasIdbTsev4
domain_of:
- scales_CaseCriminal
range: Any
any_of:
- range: integer
- range: string

```
</details>