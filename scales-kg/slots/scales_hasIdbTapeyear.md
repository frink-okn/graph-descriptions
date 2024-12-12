

# Slot: scales_hasIdbTapeyear


_No slot description provided_





URI: [scales:hasIdbTapeyear](http://schemas.scales-okn.org/rdf/scales#hasIdbTapeyear)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | No type description provided |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | No type description provided |  no  |







## Properties

* Range: [xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbTapeyear 2019.0 |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTapeyear 2099.0 |

## Comments

* 551088 occurrences with subject type scales_CaseCivil and object type double.
* 111582 occurrences with subject type scales_CaseCriminal and object type double.

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
| self | scales:hasIdbTapeyear |
| native | scales-kg/:scales_hasIdbTapeyear |




## LinkML Source

<details>
```yaml
name: scales_hasIdbTapeyear
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 551088 occurrences with subject type scales_CaseCivil and object type double.
- 111582 occurrences with subject type scales_CaseCriminal and object type double.
examples:
- value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbTapeyear 2019.0
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTapeyear 2099.0
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTapeyear
alias: scales_hasIdbTapeyear
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: double

```
</details>