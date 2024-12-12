

# Slot: No slot description provided (contaminoso_hasFeatureOfInterest)


_No slot description provided_





URI: [contaminoso:hasFeatureOfInterest](http://sawgraph.spatialai.org/v1/contaminoso#hasFeatureOfInterest)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoContaminantObservation](../classes/ContaminosoContaminantObservation.md) | No type description provided |  no  |







## Properties

* Range: [ContaminosoFeature](../classes/ContaminosoFeature.md)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/us-epa-ghg#d.ReleaseObservation.GHGFacility-1010811.Year-2012.Chemical-Perfluorocyclopropane contaminoso:hasFeatureOfInterest usfrsdata:d.FRS-Facility.110010724216 |

## Comments

* 733 occurrences with subject type contaminoso_ContaminantObservation and object type contaminoso_Feature.

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
| self | contaminoso:hasFeatureOfInterest |
| native | sawgraph-kg/:contaminoso_hasFeatureOfInterest |




## LinkML Source

<details>
```yaml
name: contaminoso_hasFeatureOfInterest
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 733 occurrences with subject type contaminoso_ContaminantObservation and object
  type contaminoso_Feature.
examples:
- value: http://sawgraph.spatialai.org/v1/us-epa-ghg#d.ReleaseObservation.GHGFacility-1010811.Year-2012.Chemical-Perfluorocyclopropane
    contaminoso:hasFeatureOfInterest usfrsdata:d.FRS-Facility.110010724216
from_schema: sawgraph-kg
rank: 1000
slot_uri: contaminoso:hasFeatureOfInterest
alias: contaminoso_hasFeatureOfInterest
domain_of:
- contaminoso_ContaminantObservation
range: contaminoso_Feature

```
</details>