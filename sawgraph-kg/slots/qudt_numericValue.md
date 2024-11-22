

# Slot: TODO -- tell the world what this slot (predicate) describes. (qudt_numericValue)


_TODO -- tell the world what this slot (predicate) describes._





URI: [qudt:numericValue](http://qudt.org/schema/qudt/numericValue)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoResultQualifier](../classes/ContaminosoResultQualifier.md) | TODO -- tell the world what this class (type) describes |  no  |
| [MeegadEGAD-ValidationLevel](../classes/MeegadEGAD-ValidationLevel.md) | TODO -- tell the world what this class (type) describes |  no  |
| [PfasQuantitationLimit](../classes/PfasQuantitationLimit.md) | TODO -- tell the world what this class (type) describes |  no  |
| [MeegadEGAD-LabQualifier](../classes/MeegadEGAD-LabQualifier.md) | TODO -- tell the world what this class (type) describes |  no  |
| [PfasMethodDetectionLimit](../classes/PfasMethodDetectionLimit.md) | TODO -- tell the world what this class (type) describes |  no  |
| [PfasReportingLimit](../classes/PfasReportingLimit.md) | TODO -- tell the world what this class (type) describes |  no  |
| [MeegadEGAD-ValidationQualifier](../classes/MeegadEGAD-ValidationQualifier.md) | TODO -- tell the world what this class (type) describes |  no  |







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
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
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