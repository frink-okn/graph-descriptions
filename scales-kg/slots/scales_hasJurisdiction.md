

# Slot: scales_hasJurisdiction


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasJurisdiction](http://schemas.scales-okn.org/rdf/scales#hasJurisdiction)



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
| scales:CaseCivil/akd;;1:16-cv-00009 scales:hasJurisdiction U.S. Government Defendant |
| scales:CaseCriminal/txed;;4:17-cr-00092 scales:hasJurisdiction Ct. 1s |

## Comments

* 561174 occurrences with subject type scales_CaseCivil and object type string.
* 31 occurrences with subject type scales_CaseCriminal and object type string.

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
| self | scales:hasJurisdiction |
| native | scales-kg/:scales_hasJurisdiction |




## LinkML Source

<details>
```yaml
name: scales_hasJurisdiction
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 561174 occurrences with subject type scales_CaseCivil and object type string.
- 31 occurrences with subject type scales_CaseCriminal and object type string.
examples:
- value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasJurisdiction U.S. Government
    Defendant
- value: scales:CaseCriminal/txed;;4:17-cr-00092 scales:hasJurisdiction Ct. 1s
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasJurisdiction
alias: scales_hasJurisdiction
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: string

```
</details>