

# Slot: scales_hasTerminatingDate


_TODO -- tell the world what this slot (predicate) describes._





URI: [scales:hasTerminatingDate](http://schemas.scales-okn.org/rdf/scales#hasTerminatingDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | TODO -- tell the world what this class (type) describes |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| scales:CaseCivil/akd;;1:16-cv-00009 scales:hasTerminatingDate 2019-01-15 |
| scales:CaseCivil/ctd;;3:15-cv-01889 scales:hasTerminatingDate 02/17/2016 |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasTerminatingDate 2019-03-01 |
| scales:CaseCriminal/casd;;3:12-cr-03082 scales:hasTerminatingDate 09/18/2012 |

## Comments

* 512691 occurrences with subject type scales_CaseCivil and object type date.
* 10827 occurrences with subject type scales_CaseCivil and object type string.
* 121860 occurrences with subject type scales_CaseCriminal and object type date.
* 1198 occurrences with subject type scales_CaseCriminal and object type string.

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
| self | scales:hasTerminatingDate |
| native | scales-kg/:scales_hasTerminatingDate |




## LinkML Source

<details>
```yaml
name: scales_hasTerminatingDate
description: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 512691 occurrences with subject type scales_CaseCivil and object type date.
- 10827 occurrences with subject type scales_CaseCivil and object type string.
- 121860 occurrences with subject type scales_CaseCriminal and object type date.
- 1198 occurrences with subject type scales_CaseCriminal and object type string.
examples:
- value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasTerminatingDate 2019-01-15
- value: scales:CaseCivil/ctd;;3:15-cv-01889 scales:hasTerminatingDate 02/17/2016
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasTerminatingDate 2019-03-01
- value: scales:CaseCriminal/casd;;3:12-cr-03082 scales:hasTerminatingDate 09/18/2012
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasTerminatingDate
alias: scales_hasTerminatingDate
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: Any
any_of:
- range: date
- range: string

```
</details>