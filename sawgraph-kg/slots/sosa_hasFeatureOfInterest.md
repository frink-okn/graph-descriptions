

# Slot: No slot description provided (sosa_hasFeatureOfInterest)


_No slot description provided_





URI: [sosa:hasFeatureOfInterest](http://www.w3.org/ns/sosa/hasFeatureOfInterest)



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
| http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA sosa:hasFeatureOfInterest http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PublicWaterSystem.ME0400899 |

## Comments

* 156 occurrences with subject type contaminoso_ContaminantObservation and object type contaminoso_Feature.

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
| self | sosa:hasFeatureOfInterest |
| native | sawgraph-kg/:sosa_hasFeatureOfInterest |




## LinkML Source

<details>
```yaml
name: sosa_hasFeatureOfInterest
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 156 occurrences with subject type contaminoso_ContaminantObservation and object
  type contaminoso_Feature.
examples:
- value: http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
    sosa:hasFeatureOfInterest http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PublicWaterSystem.ME0400899
from_schema: sawgraph-kg
rank: 1000
slot_uri: sosa:hasFeatureOfInterest
alias: sosa_hasFeatureOfInterest
domain_of:
- contaminoso_ContaminantObservation
range: contaminoso_Feature

```
</details>