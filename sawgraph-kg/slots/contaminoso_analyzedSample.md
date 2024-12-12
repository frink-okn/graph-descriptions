

# Slot: No slot description provided (contaminoso_analyzedSample)


_No slot description provided_





URI: [contaminoso:analyzedSample](http://sawgraph.spatialai.org/v1/contaminoso#analyzedSample)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoContaminantObservation](../classes/ContaminosoContaminantObservation.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ContaminosoMaterialSample](../classes/ContaminosoMaterialSample.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA contaminoso:analyzedSample http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Sample.ME0400899.10282021 |

## Comments

* 142331 occurrences with subject type contaminoso_ContaminantObservation and object type contaminoso_MaterialSample.

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
| self | contaminoso:analyzedSample |
| native | sawgraph-kg/:contaminoso_analyzedSample |




## LinkML Source

<details>
```yaml
name: contaminoso_analyzedSample
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 142331 occurrences with subject type contaminoso_ContaminantObservation and object
  type contaminoso_MaterialSample.
examples:
- value: http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0400899.10282021.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
    contaminoso:analyzedSample http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Sample.ME0400899.10282021
from_schema: sawgraph-kg
rank: 1000
domain: contaminoso_SampleContaminantObservation
slot_uri: contaminoso:analyzedSample
alias: contaminoso_analyzedSample
domain_of:
- contaminoso_ContaminantObservation
range: Any
any_of:
- range: contaminoso_MaterialSample
- range: uri

```
</details>