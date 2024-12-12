

# Slot: No slot description provided (qudt_numericValue)


_No slot description provided_





URI: [qudt:numericValue](http://qudt.org/schema/qudt/numericValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [MeegadEGAD-ValidationQualifier](../classes/MeegadEGAD-ValidationQualifier.md) | No type description provided |  no  |
| [PfasReportingLimit](../classes/PfasReportingLimit.md) | No type description provided |  no  |
| [PfasMethodDetectionLimit](../classes/PfasMethodDetectionLimit.md) | No type description provided |  no  |
| [MeegadEGAD-LabQualifier](../classes/MeegadEGAD-LabQualifier.md) | No type description provided |  no  |
| [ContaminosoResultQualifier](../classes/ContaminosoResultQualifier.md) | No type description provided |  no  |
| [PfasQuantitationLimit](../classes/PfasQuantitationLimit.md) | No type description provided |  no  |
| [MeegadEGAD-ValidationLevel](../classes/MeegadEGAD-ValidationLevel.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:decimal](http://www.w3.org/2001/XMLSchema#decimal)&nbsp;or&nbsp;<br />[xsd:double](http://www.w3.org/2001/XMLSchema#double)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#quantityValue.1028303.ELL.20190405.45298906 qudt:numericValue 14.0 |
| http://sawgraph.spatialai.org/v1/me-egad-data#quantityValue.L195312201.AAWH.20191107.375735 qudt:numericValue 2.8e-05 |
| http://sawgraph.spatialai.org/v1/me-egad-data#rl.1028303.ELL.20190405.45298906 qudt:numericValue 1.6 |
| http://sawgraph.spatialai.org/v1/me-egad-data#rl.320495081.TAI.20190423.335671 qudt:numericValue 9.2e-05 |

## Comments

* 142927 occurrences with untyped subjects and object type decimal.
* 127 occurrences with untyped subjects and object type http://www.w3.org/2001/XMLSchema#double.
* 280289 occurrences with subject type contaminoso_ResultQualifier and object type decimal.
* 570 occurrences with subject type contaminoso_ResultQualifier and object type double.

## TODOs

* TODO -- Todos for this slot go here
* or you can delete the todos
* if you think the class is perfect.

## Identifier and Mapping Information







### Schema Source


* from schema: sawgraph-kg




## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | qudt:numericValue |
| native | sawgraph-kg/:qudt_numericValue |




## LinkML Source

<details>
```yaml
name: qudt_numericValue
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 142927 occurrences with untyped subjects and object type decimal.
- 127 occurrences with untyped subjects and object type http://www.w3.org/2001/XMLSchema#double.
- 280289 occurrences with subject type contaminoso_ResultQualifier and object type
  decimal.
- 570 occurrences with subject type contaminoso_ResultQualifier and object type double.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#quantityValue.1028303.ELL.20190405.45298906
    qudt:numericValue 14.0
- value: http://sawgraph.spatialai.org/v1/me-egad-data#quantityValue.L195312201.AAWH.20191107.375735
    qudt:numericValue 2.8e-05
- value: http://sawgraph.spatialai.org/v1/me-egad-data#rl.1028303.ELL.20190405.45298906
    qudt:numericValue 1.6
- value: http://sawgraph.spatialai.org/v1/me-egad-data#rl.320495081.TAI.20190423.335671
    qudt:numericValue 9.2e-05
from_schema: sawgraph-kg
rank: 1000
slot_uri: qudt:numericValue
alias: qudt_numericValue
domain_of:
- contaminoso_ResultQualifier
range: Any
any_of:
- range: decimal
- range: double

```
</details>