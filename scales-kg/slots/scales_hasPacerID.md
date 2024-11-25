

# Slot: scales_hasPacerID


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasPacerID](http://schemas.scales-okn.org/rdf/scales#hasPacerID)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ScalesDocketEntry](../classes/ScalesDocketEntry.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ScalesCharge](../classes/ScalesCharge.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| scales:CaseCivil/akd;;1:16-cv-00009 scales:hasPacerID 1:16-cv-00009 |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasPacerID 1:17-cr-00012 |
| scales:Charge/akd;;1:16-cr-00001_c1-3 scales:hasPacerID 1-3 |
| scales:DocketEntry/akd;;1:16-cr-00001_de0 scales:hasPacerID 1 |

## Comments

* 561182 occurrences with subject type scales_CaseCivil and object type string.
* 127619 occurrences with subject type scales_CaseCriminal and object type string.
* 262292 occurrences with subject type scales_Charge and object type string.
* 23661271 occurrences with subject type scales_DocketEntry and object type string.

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
| self | scales:hasPacerID |
| native | scales-kg/:scales_hasPacerID |




## LinkML Source

<details>
```yaml
name: scales_hasPacerID
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 561182 occurrences with subject type scales_CaseCivil and object type string.
- 127619 occurrences with subject type scales_CaseCriminal and object type string.
- 262292 occurrences with subject type scales_Charge and object type string.
- 23661271 occurrences with subject type scales_DocketEntry and object type string.
examples:
- value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasPacerID 1:16-cv-00009
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasPacerID 1:17-cr-00012
- value: scales:Charge/akd;;1:16-cr-00001_c1-3 scales:hasPacerID 1-3
- value: scales:DocketEntry/akd;;1:16-cr-00001_de0 scales:hasPacerID 1
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasPacerID
alias: scales_hasPacerID
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
- scales_Charge
- scales_DocketEntry
range: string

```
</details>