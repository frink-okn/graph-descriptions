

# Slot: TODO -- tell the world what this slot (predicate) describes. (contaminoso_hasAggregationPeriod)


_TODO -- tell the world what this slot (predicate) describes._





URI: [contaminoso:hasAggregationPeriod](http://sawgraph.spatialai.org/v1/contaminoso#hasAggregationPeriod)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoContaminantObservation](../classes/ContaminosoContaminantObservation.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/us-epa-ghg#d.ReleaseObservation.GHGFacility-1006665.Year-2011.Chemical-2_2_3_3_4-PENTAFLUORO-4-_TRIFLUOROMETHYL_-OXETANE contaminoso:hasAggregationPeriod usfrsdata:d.TimeInterval.Year-2011 |

## Comments

* 733 occurrences with subject type contaminoso_ContaminantObservation and object type uri.

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
| self | contaminoso:hasAggregationPeriod |
| native | sawgraph-kg/:contaminoso_hasAggregationPeriod |




## LinkML Source

<details>
```yaml
name: contaminoso_hasAggregationPeriod
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 733 occurrences with subject type contaminoso_ContaminantObservation and object
  type uri.
examples:
- value: http://sawgraph.spatialai.org/v1/us-epa-ghg#d.ReleaseObservation.GHGFacility-1006665.Year-2011.Chemical-2_2_3_3_4-PENTAFLUORO-4-_TRIFLUOROMETHYL_-OXETANE
    contaminoso:hasAggregationPeriod usfrsdata:d.TimeInterval.Year-2011
from_schema: sawgraph-kg
rank: 1000
domain: contaminoso_ReleaseContaminantObservation
slot_uri: contaminoso:hasAggregationPeriod
alias: contaminoso_hasAggregationPeriod
domain_of:
- contaminoso_ContaminantObservation
subproperty_of: contaminoso_hasTemporalCoverage
range: uri

```
</details>