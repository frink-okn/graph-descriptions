

# Slot: scales_hasIdbTermdate


_No slot description provided_





URI: [scales:hasIdbTermdate](http://schemas.scales-okn.org/rdf/scales#hasIdbTermdate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | No type description provided |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | No type description provided |  no  |







## Properties

* Range: [xsd:dateTime](http://www.w3.org/2001/XMLSchema#dateTime)






## Examples

| Value |
| --- |
| scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbTermdate 2019-01-15T00:00:00 |
| scales:CaseCriminal/akd;;1:16-cr-00001 scales:hasIdbTermdate 2016-08-01T00:00:00 |

## Comments

* 517964 occurrences with subject type scales_CaseCivil and object type datetime.
* 48652 occurrences with subject type scales_CaseCriminal and object type datetime.

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
| self | scales:hasIdbTermdate |
| native | scales-kg/:scales_hasIdbTermdate |




## LinkML Source

<details>
```yaml
name: scales_hasIdbTermdate
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 517964 occurrences with subject type scales_CaseCivil and object type datetime.
- 48652 occurrences with subject type scales_CaseCriminal and object type datetime.
examples:
- value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbTermdate 2019-01-15T00:00:00
- value: scales:CaseCriminal/akd;;1:16-cr-00001 scales:hasIdbTermdate 2016-08-01T00:00:00
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbTermdate
alias: scales_hasIdbTermdate
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: datetime

```
</details>