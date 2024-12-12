

# Slot: scales_hasIdbFiledate


_No slot description provided_





URI: [scales:hasIdbFiledate](http://schemas.scales-okn.org/rdf/scales#hasIdbFiledate)



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
| scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbFiledate 2016-04-15T00:00:00 |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFiledate 2017-03-02T00:00:00 |

## Comments

* 551088 occurrences with subject type scales_CaseCivil and object type datetime.
* 111582 occurrences with subject type scales_CaseCriminal and object type datetime.

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
| self | scales:hasIdbFiledate |
| native | scales-kg/:scales_hasIdbFiledate |




## LinkML Source

<details>
```yaml
name: scales_hasIdbFiledate
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 551088 occurrences with subject type scales_CaseCivil and object type datetime.
- 111582 occurrences with subject type scales_CaseCriminal and object type datetime.
examples:
- value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasIdbFiledate 2016-04-15T00:00:00
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasIdbFiledate 2017-03-02T00:00:00
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasIdbFiledate
alias: scales_hasIdbFiledate
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
range: datetime

```
</details>