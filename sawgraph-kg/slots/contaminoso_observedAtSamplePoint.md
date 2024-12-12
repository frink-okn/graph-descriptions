

# Slot: No slot description provided (contaminoso_observedAtSamplePoint)


_No slot description provided_





URI: [contaminoso:observedAtSamplePoint](http://sawgraph.spatialai.org/v1/contaminoso#observedAtSamplePoint)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoContaminantObservation](../classes/ContaminosoContaminantObservation.md) | No type description provided |  no  |







## Properties

* Range: [ContaminosoPoint](../classes/ContaminosoPoint.md)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#observation.WG17410824.AAWH.20230125.DEP18018 contaminoso:observedAtSamplePoint http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.142996 |

## Comments

* 142261 occurrences with subject type contaminoso_ContaminantObservation and object type contaminoso_Point.

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
| self | contaminoso:observedAtSamplePoint |
| native | sawgraph-kg/:contaminoso_observedAtSamplePoint |




## LinkML Source

<details>
```yaml
name: contaminoso_observedAtSamplePoint
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 142261 occurrences with subject type contaminoso_ContaminantObservation and object
  type contaminoso_Point.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#observation.WG17410824.AAWH.20230125.DEP18018
    contaminoso:observedAtSamplePoint http://sawgraph.spatialai.org/v1/me-egad-data#samplePoint.142996
from_schema: sawgraph-kg
rank: 1000
slot_uri: contaminoso:observedAtSamplePoint
alias: contaminoso_observedAtSamplePoint
domain_of:
- contaminoso_ContaminantObservation
range: contaminoso_Point

```
</details>