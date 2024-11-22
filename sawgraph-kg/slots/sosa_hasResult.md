

# Slot: TODO -- tell the world what this slot (predicate) describes. (sosa_hasResult)


_TODO -- tell the world what this slot (predicate) describes._





URI: [sosa:hasResult](http://www.w3.org/ns/sosa/hasResult)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoContaminantObservation](../classes/ContaminosoContaminantObservation.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ContaminosoContaminantMeasurement](../classes/ContaminosoContaminantMeasurement.md)&nbsp;or&nbsp;<br />[ContaminosoAggregateContaminantMeasurement](../classes/ContaminosoAggregateContaminantMeasurement.md)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA sosa:hasResult http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-PFASConcentration.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA |
| http://sawgraph.spatialai.org/v1/me-egad-data#observation.WG17410824.AAWH.20230125.DEP18018 sosa:hasResult http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018 |

## Comments

* 116038 occurrences with subject type contaminoso_ContaminantObservation and object type contaminoso_ContaminantMeasurement.
* 26293 occurrences with subject type contaminoso_ContaminantObservation and object type contaminoso_AggregateContaminantMeasurement.

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
| self | sosa:hasResult |
| native | sawgraph-kg/:sosa_hasResult |




## LinkML Source

<details>
```yaml
name: sosa_hasResult
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 116038 occurrences with subject type contaminoso_ContaminantObservation and object
  type contaminoso_ContaminantMeasurement.
- 26293 occurrences with subject type contaminoso_ContaminantObservation and object
  type contaminoso_AggregateContaminantMeasurement.
examples:
- value: http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
    sosa:hasResult http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-PFASConcentration.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
- value: http://sawgraph.spatialai.org/v1/me-egad-data#observation.WG17410824.AAWH.20230125.DEP18018
    sosa:hasResult http://sawgraph.spatialai.org/v1/me-egad-data#result.WG17410824.AAWH.20230125.DEP18018
from_schema: sawgraph-kg
rank: 1000
slot_uri: sosa:hasResult
alias: sosa_hasResult
domain_of:
- contaminoso_ContaminantObservation
range: Any
any_of:
- range: contaminoso_ContaminantMeasurement
- range: contaminoso_AggregateContaminantMeasurement

```
</details>