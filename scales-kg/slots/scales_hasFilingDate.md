

# Slot: scales_hasFilingDate


_No slot description provided_





URI: [scales:hasFilingDate](http://schemas.scales-okn.org/rdf/scales#hasFilingDate)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ScalesCaseCriminal](../classes/ScalesCaseCriminal.md) | No type description provided |  no  |
| [ScalesCaseCivil](../classes/ScalesCaseCivil.md) | No type description provided |  no  |
| [ScalesDocketEntry](../classes/ScalesDocketEntry.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| scales:CaseCivil/akd;;1:16-cv-00009 scales:hasFilingDate 2016-04-15 |
| scales:CaseCivil/ctd;;3:15-cv-01889 scales:hasFilingDate 12/31/2015 |
| scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasFilingDate 2017-03-02 |
| scales:DocketEntry/akd;;1:16-cr-00001_de0 scales:hasFilingDate 2016-02-03 |
| scales:DocketEntry/akd;;3:15-cv-00265_de0 scales:hasFilingDate 12/31/2015 |
| scales:CaseCriminal/casd;;3:12-cr-03082 scales:hasFilingDate 07/26/2012 |

## Comments

* 550105 occurrences with subject type scales_CaseCivil and object type date.
* 11077 occurrences with subject type scales_CaseCivil and object type string.
* 126369 occurrences with subject type scales_CaseCriminal and object type date.
* 23203350 occurrences with subject type scales_DocketEntry and object type date.
* 457921 occurrences with subject type scales_DocketEntry and object type string.
* 1250 occurrences with subject type scales_CaseCriminal and object type string.

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
| self | scales:hasFilingDate |
| native | scales-kg/:scales_hasFilingDate |




## LinkML Source

<details>
```yaml
name: scales_hasFilingDate
description: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 550105 occurrences with subject type scales_CaseCivil and object type date.
- 11077 occurrences with subject type scales_CaseCivil and object type string.
- 126369 occurrences with subject type scales_CaseCriminal and object type date.
- 23203350 occurrences with subject type scales_DocketEntry and object type date.
- 457921 occurrences with subject type scales_DocketEntry and object type string.
- 1250 occurrences with subject type scales_CaseCriminal and object type string.
examples:
- value: scales:CaseCivil/akd;;1:16-cv-00009 scales:hasFilingDate 2016-04-15
- value: scales:CaseCivil/ctd;;3:15-cv-01889 scales:hasFilingDate 12/31/2015
- value: scales:CaseCriminal/iand;;1:17-cr-00012 scales:hasFilingDate 2017-03-02
- value: scales:DocketEntry/akd;;1:16-cr-00001_de0 scales:hasFilingDate 2016-02-03
- value: scales:DocketEntry/akd;;3:15-cv-00265_de0 scales:hasFilingDate 12/31/2015
- value: scales:CaseCriminal/casd;;3:12-cr-03082 scales:hasFilingDate 07/26/2012
from_schema: scales-kg
rank: 1000
slot_uri: scales:hasFilingDate
alias: scales_hasFilingDate
domain_of:
- scales_CaseCivil
- scales_CaseCriminal
- scales_DocketEntry
range: Any
any_of:
- range: date
- range: string

```
</details>