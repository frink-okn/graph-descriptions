

# Slot: scales_hasIdbTranoff


_No slot description provided_





URI: [scales:hasIdbTranoff](http://schemas.scales-okn.org/rdf/scales#hasIdbTranoff)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:integer](http://www.w3.org/2001/XMLSchema#integer)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTranoff -8.0 |
| scales:CaseCriminal/casd;;3:12-cr-03082 scales:hasIdbTranoff -8 |

## Comments

* 110543 occurrences with subject type scales_CaseCriminal and object type double.
* 1039 occurrences with subject type scales_CaseCriminal and object type integer.

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
| self | scales:hasIdbTranoff |
| native | scales-kg/:scales_hasIdbTranoff |




## LinkML Source

<details>
```yaml
name: scales_hasIdbTranoff
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 110543 occurrences with subject type scales_CaseCriminal and object type double.
- 1039 occurrences with subject type scales_CaseCriminal and object type integer.
examples:
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbTranoff -8.0
- value: scales:CaseCriminal/casd;;3:12-cr-03082 scales:hasIdbTranoff -8
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTranoff
alias: scales_hasIdbTranoff
domain_of:
- scales_CaseCriminal
range: Any
any_of:
- range: integer
- range: double

```
</details>