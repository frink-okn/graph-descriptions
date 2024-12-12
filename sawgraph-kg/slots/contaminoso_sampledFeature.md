

# Slot: No slot description provided (contaminoso_sampledFeature)


_No slot description provided_





URI: [contaminoso:sampledFeature](http://sawgraph.spatialai.org/v1/contaminoso#sampledFeature)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoContaminantObservation](../classes/ContaminosoContaminantObservation.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ContaminosoFeature](../classes/ContaminosoFeature.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA contaminoso:sampledFeature http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PublicWaterSystem.ME0400899 |

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
| self | contaminoso:sampledFeature |
| native | sawgraph-kg/:contaminoso_sampledFeature |




## LinkML Source

<details>
```yaml
name: contaminoso_sampledFeature
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
    contaminoso:sampledFeature http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PublicWaterSystem.ME0400899
from_schema: sawgraph-kg
rank: 1000
domain: contaminoso_ContaminantObservation
slot_uri: contaminoso:sampledFeature
alias: contaminoso_sampledFeature
domain_of:
- contaminoso_ContaminantObservation
subproperty_of: sosa_hasFeatureOfInterest
range: Any
any_of:
- range: contaminoso_Feature
- range: uri

```
</details>