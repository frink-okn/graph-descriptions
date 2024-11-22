

# Slot: TODO -- tell the world what this slot (predicate) describes. (contaminoso_hasResult)


_TODO -- tell the world what this slot (predicate) describes._





URI: [contaminoso:hasResult](http://sawgraph.spatialai.org/v1/contaminoso#hasResult)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoContaminantObservation](../classes/ContaminosoContaminantObservation.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [ContaminosoAggregateContaminantMeasurement](../classes/ContaminosoAggregateContaminantMeasurement.md)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/us-epa-ghg#d.ReleaseObservation.GHGFacility-1010811.Year-2012.Chemical-Perfluorocyclopropane contaminoso:hasResult http://sawgraph.spatialai.org/v1/us-epa-ghg#d.ContaminantMeasurement.GHGFacility-1010811.Year-2012.Chemical-Perfluorocyclopropane.Chemical-Perfluorocyclopropane |

## Comments

* 733 occurrences with subject type contaminoso_ContaminantObservation and object type contaminoso_AggregateContaminantMeasurement.

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
| self | contaminoso:hasResult |
| native | sawgraph-kg/:contaminoso_hasResult |




## LinkML Source

<details>
```yaml
name: contaminoso_hasResult
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 733 occurrences with subject type contaminoso_ContaminantObservation and object
  type contaminoso_AggregateContaminantMeasurement.
examples:
- value: http://sawgraph.spatialai.org/v1/us-epa-ghg#d.ReleaseObservation.GHGFacility-1010811.Year-2012.Chemical-Perfluorocyclopropane
    contaminoso:hasResult http://sawgraph.spatialai.org/v1/us-epa-ghg#d.ContaminantMeasurement.GHGFacility-1010811.Year-2012.Chemical-Perfluorocyclopropane.Chemical-Perfluorocyclopropane
from_schema: sawgraph-kg
rank: 1000
slot_uri: contaminoso:hasResult
alias: contaminoso_hasResult
domain_of:
- contaminoso_ContaminantObservation
range: contaminoso_AggregateContaminantMeasurement

```
</details>