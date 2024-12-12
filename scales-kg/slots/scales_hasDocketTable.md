

# Slot: scales_hasDocketTable


_No slot description provided_





URI: [scales:hasDocketTable](http://schemas.scales-okn.org/rdf/scales#hasDocketTable)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | No type description provided |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | No type description provided |  no  |







## Properties

* Range: [ScalesDocketTable](../classes/ScalesDocketTable.md)






## Examples

| Value |
| --- |
| scales:CaseOther/txsd;;3:16-mc-00016 scales:hasDocketTable scales:DocketTable/txsd;;3:16-mc-00016 |
| scales:CaseCriminal/wyd;;6:17-cr-00033 scales:hasDocketTable scales:DocketTable/wyd;;6:17-cr-00033 |

## Comments

* 561182 occurrences with subject type scales_CaseCivil and object type scales_DocketTable.
* 127619 occurrences with subject type scales_CaseCriminal and object type scales_DocketTable.

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
| self | scales:hasDocketTable |
| native | scales-kg/:scales_hasDocketTable |




## LinkML Source

<details>
```yaml
name: scales_hasDocketTable
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 561182 occurrences with subject type scales_CaseCivil and object type scales_DocketTable.
- 127619 occurrences with subject type scales_CaseCriminal and object type scales_DocketTable.
examples:
- value: scales:CaseOther/txsd;;3:16-mc-00016 scales:hasDocketTable scales:DocketTable/txsd;;3:16-mc-00016
- value: scales:CaseCriminal/wyd;;6:17-cr-00033 scales:hasDocketTable scales:DocketTable/wyd;;6:17-cr-00033
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasDocketTable
alias: scales_hasDocketTable
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: scales_DocketTable

```
</details>