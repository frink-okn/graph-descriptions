

# Slot: No slot description provided (meegad_parameterGroup)


_No slot description provided_





URI: [meegad:parameterGroup](http://sawgraph.spatialai.org/v1/me-egad#parameterGroup)



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

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/me-egad#concentrationQualifier.* meegad:parameterGroup ALL |

## Comments

* 56 occurrences with subject type contaminoso_ResultQualifier and object type string.

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
| self | meegad:parameterGroup |
| native | sawgraph-kg/:meegad_parameterGroup |




## LinkML Source

<details>
```yaml
name: meegad_parameterGroup
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 56 occurrences with subject type contaminoso_ResultQualifier and object type string.
examples:
- value: http://sawgraph.spatialai.org/me-egad#concentrationQualifier.* meegad:parameterGroup
    ALL
from_schema: sawgraph-kg
rank: 1000
slot_uri: meegad:parameterGroup
alias: meegad_parameterGroup
domain_of:
- contaminoso_ResultQualifier
range: string

```
</details>