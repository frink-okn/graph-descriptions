

# Slot: scales_isInCourt


_No slot description provided_





URI: [scales:isInCourt](http://schemas.scales-okn.org/rdf/scales#isInCourt)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | No type description provided |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | No type description provided |  no  |







## Properties

* Range: [ScalesCourt](../classes/ScalesCourt.md)






## Examples

| Value |
| --- |
| scales:CaseOther/txsd;;3:16-mc-00016 scales:isInCourt scales:Court/txsd |
| scales:CaseCriminal/wyd;;6:17-cr-00033 scales:isInCourt scales:Court/wyd |

## Comments

* 561182 occurrences with subject type scales_CaseCivil and object type scales_Court.
* 127619 occurrences with subject type scales_CaseCriminal and object type scales_Court.

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
| self | scales:isInCourt |
| native | scales-kg/:scales_isInCourt |




## LinkML Source

<details>
```yaml
name: scales_isInCourt
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 561182 occurrences with subject type scales_CaseCivil and object type scales_Court.
- 127619 occurrences with subject type scales_CaseCriminal and object type scales_Court.
examples:
- value: scales:CaseOther/txsd;;3:16-mc-00016 scales:isInCourt scales:Court/txsd
- value: scales:CaseCriminal/wyd;;6:17-cr-00033 scales:isInCourt scales:Court/wyd
from_schema: scales-kg
rank: 1000
slot_uri: scales:isInCourt
alias: scales_isInCourt
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: scales_Court

```
</details>