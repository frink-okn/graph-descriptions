

# Slot: scales_hasIdbDistrict


_No slot description provided_





URI: [scales:hasIdbDistrict](http://schemas.scales-okn.org/rdf/scales#hasIdbDistrict)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | No type description provided |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | No type description provided |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbDistrict akd |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDistrict iand |

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
| self | scales:hasIdbDistrict |
| native | scales-kg/:scales_hasIdbDistrict |




## LinkML Source

<details>
```yaml
name: scales_hasIdbDistrict
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 551088 occurrences with subject type scales_CaseCivil and object type string.
- 111582 occurrences with subject type scales_CaseCriminal and object type string.
examples:
- value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbDistrict akd
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbDistrict iand
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbDistrict
alias: scales_hasIdbDistrict
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: string

```
</details>