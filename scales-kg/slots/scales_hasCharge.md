

# Slot: scales_hasCharge


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasCharge](http://schemas.scales-okn.org/rdf/scales#hasCharge)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ScalesAgent](../classes/ScalesAgent.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [ScalesCharge](../classes/ScalesCharge.md)






## Examples

| Value |
| --- |
| scales:Agent/wyd;;6:17-cr-00033_a0 scales:hasCharge scales:Charge/wyd;;6:17-cr-00033_c1 |
| scales:CaseCriminal/wyd;;6:17-cr-00033 scales:hasCharge scales:Charge/wyd;;6:17-cr-00033_c1 |

## Comments

* 340575 occurrences with subject type scales_Agent and object type scales_Charge.
* 262292 occurrences with subject type scales_CaseCriminal and object type scales_Charge.

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
| self | scales:hasCharge |
| native | scales-kg/:scales_hasCharge |




## LinkML Source

<details>
```yaml
name: scales_hasCharge
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 340575 occurrences with subject type scales_Agent and object type scales_Charge.
- 262292 occurrences with subject type scales_CaseCriminal and object type scales_Charge.
examples:
- value: scales:Agent/wyd;;6:17-cr-00033_a0 scales:hasCharge scales:Charge/wyd;;6:17-cr-00033_c1
- value: scales:CaseCriminal/wyd;;6:17-cr-00033 scales:hasCharge scales:Charge/wyd;;6:17-cr-00033_c1
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasCharge
alias: scales_hasCharge
domain_of:
- scales_Agent
- scales_CaseCriminal
range: scales_Charge

```
</details>