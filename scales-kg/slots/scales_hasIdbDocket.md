

# Slot: scales_hasIdbDocket


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasIdbDocket](http://schemas.scales-okn.org/rdf/scales#hasIdbDocket)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbDocket 1600009 |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDocket 1700012 |

## Comments

* 551088 occurrences with subject type scales_CaseCivil and object type string.
* 111582 occurrences with subject type scales_CaseCriminal and object type string.

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
| self | scales:hasIdbDocket |
| native | scales-kg/:scales_hasIdbDocket |




## LinkML Source

<details>
```yaml
name: scales_hasIdbDocket
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 551088 occurrences with subject type scales_CaseCivil and object type string.
- 111582 occurrences with subject type scales_CaseCriminal and object type string.
examples:
- value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbDocket 1600009
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDocket 1700012
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbDocket
alias: scales_hasIdbDocket
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: string

```
</details>