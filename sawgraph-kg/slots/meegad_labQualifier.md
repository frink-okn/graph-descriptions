

# Slot: No slot description provided (meegad_labQualifier)


_No slot description provided_





URI: [meegad:labQualifier](http://sawgraph.spatialai.org/v1/me-egad#labQualifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoAggregateContaminantMeasurement](../classes/ContaminosoAggregateContaminantMeasurement.md) | No type description provided |  no  |
| [ContaminosoContaminantMeasurement](../classes/ContaminosoContaminantMeasurement.md) | No type description provided |  no  |







## Properties

* Range: [ContaminosoResultQualifier](../classes/ContaminosoResultQualifier.md)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231 meegad:labQualifier meegad:concentrationQualifier.J |
| http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018 meegad:labQualifier meegad:concentrationQualifier.J |

## Comments

* 40705 occurrences with subject type contaminoso_ContaminantMeasurement and object type contaminoso_ResultQualifier.
* 13237 occurrences with subject type contaminoso_AggregateContaminantMeasurement and object type contaminoso_ResultQualifier.

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
| self | meegad:labQualifier |
| native | sawgraph-kg/:meegad_labQualifier |




## LinkML Source

<details>
```yaml
name: meegad_labQualifier
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 40705 occurrences with subject type contaminoso_ContaminantMeasurement and object
  type contaminoso_ResultQualifier.
- 13237 occurrences with subject type contaminoso_AggregateContaminantMeasurement
  and object type contaminoso_ResultQualifier.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.1763231
    meegad:labQualifier meegad:concentrationQualifier.J
- value: http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018
    meegad:labQualifier meegad:concentrationQualifier.J
from_schema: sawgraph-kg
rank: 1000
slot_uri: meegad:labQualifier
alias: meegad_labQualifier
domain_of:
- contaminoso_AggregateContaminantMeasurement
- contaminoso_ContaminantMeasurement
subproperty_of: contaminoso_resultAnnotation
range: contaminoso_ResultQualifier

```
</details>