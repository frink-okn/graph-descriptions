

# Slot: No slot description provided (meegad_methodDetectionLimit)


_No slot description provided_





URI: [meegad:methodDetectionLimit](http://sawgraph.spatialai.org/v1/me-egad#methodDetectionLimit)



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

* Range: [ContaminosoResultQualifier](../classes/ContaminosoResultQualifier.md)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#mdl.WG17410824.AAWH.20230125.DEP18018 meegad:methodDetectionLimit http://sawgraph.spatialai.org/v1/me-egad-data#rl.WG17410824.AAWH.20230125.DEP18018 |

## Comments

* 141607 occurrences with subject type contaminoso_ResultQualifier and object type contaminoso_ResultQualifier.

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
| self | meegad:methodDetectionLimit |
| native | sawgraph-kg/:meegad_methodDetectionLimit |




## LinkML Source

<details>
```yaml
name: meegad_methodDetectionLimit
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 141607 occurrences with subject type contaminoso_ResultQualifier and object type
  contaminoso_ResultQualifier.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#mdl.WG17410824.AAWH.20230125.DEP18018
    meegad:methodDetectionLimit http://sawgraph.spatialai.org/v1/me-egad-data#rl.WG17410824.AAWH.20230125.DEP18018
from_schema: sawgraph-kg
rank: 1000
slot_uri: meegad:methodDetectionLimit
alias: meegad_methodDetectionLimit
domain_of:
- contaminoso_ResultQualifier
subproperty_of: contaminoso_resultAnnotation
range: contaminoso_ResultQualifier

```
</details>