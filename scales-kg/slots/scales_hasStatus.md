

# Slot: scales_hasStatus


_No slot description provided_





URI: [scales:hasStatus](http://schemas.scales-okn.org/rdf/scales#hasStatus)



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
| scales:CaseCivil/akd;;1:16-cv-00009 scales:hasStatus closed |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasStatus closed |

## Comments

* 561182 occurrences with subject type scales_CaseCivil and object type string.
* 127619 occurrences with subject type scales_CaseCriminal and object type string.

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
| self | scales:hasStatus |
| native | scales-kg/:scales_hasStatus |




## LinkML Source

<details>
```yaml
name: scales_hasStatus
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 561182 occurrences with subject type scales_CaseCivil and object type string.
- 127619 occurrences with subject type scales_CaseCriminal and object type string.
examples:
- value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasStatus closed
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasStatus closed
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasStatus
alias: scales_hasStatus
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: string

```
</details>