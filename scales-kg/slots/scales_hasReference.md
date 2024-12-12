

# Slot: scales_hasReference


_No slot description provided_





URI: [scales:hasReference](http://schemas.scales-okn.org/rdf/scales#hasReference)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesDocketEntry](../classes/ScalesDocketEntry.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[ScalesDocketEntry](../classes/ScalesDocketEntry.md)






## Examples

| Value |
| --- |
| scales:DocketEntry/wyd;;6:16-cr-00204_de8 scales:hasReference scales:DocketEntry/wyd;;6:16-cr-00204_de7 |
| scales:DocketEntry/akd;;1:16-cr-00001_de1 scales:hasReference scales:JudgeEntity/SJ003611 |

## Comments

* 8460489 occurrences with subject type scales_DocketEntry and object type scales_DocketEntry.
* 9512366 occurrences with subject type scales_DocketEntry and object type uri.

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
| self | scales:hasReference |
| native | scales-kg/:scales_hasReference |




## LinkML Source

<details>
```yaml
name: scales_hasReference
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 8460489 occurrences with subject type scales_DocketEntry and object type scales_DocketEntry.
- 9512366 occurrences with subject type scales_DocketEntry and object type uri.
examples:
- value: scales:DocketEntry/wyd;;6:16-cr-00204_de8 scales:hasReference scales:DocketEntry/wyd;;6:16-cr-00204_de7
- value: scales:DocketEntry/akd;;1:16-cr-00001_de1 scales:hasReference scales:JudgeEntity/SJ003611
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasReference
alias: scales_hasReference
domain_of:
- scales_DocketEntry
range: Any
any_of:
- range: uri
- range: scales_DocketEntry

```
</details>