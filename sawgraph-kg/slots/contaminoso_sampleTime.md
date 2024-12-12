

# Slot: No slot description provided (contaminoso_sampleTime)


_No slot description provided_





URI: [contaminoso:sampleTime](http://sawgraph.spatialai.org/v1/contaminoso#sampleTime)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoContaminantObservation](../classes/ContaminosoContaminantObservation.md) | No type description provided |  no  |







## Properties

* Range: [xsd:date](http://www.w3.org/2001/XMLSchema#date)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0000002.06132022.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA contaminoso:sampleTime 2022-06-13 |

## Comments

* 156 occurrences with subject type contaminoso_ContaminantObservation and object type date.

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
| self | contaminoso:sampleTime |
| native | sawgraph-kg/:contaminoso_sampleTime |




## LinkML Source

<details>
```yaml
name: contaminoso_sampleTime
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 156 occurrences with subject type contaminoso_ContaminantObservation and object
  type date.
examples:
- value: http://sawgraph.spatialai.org/v1/us-sdwis-data#d.PWS-Observation.ME0000002.06132022.PFOA-PFOS-PFHxS-PFNA-PFHpA-PFDA
    contaminoso:sampleTime 2022-06-13
from_schema: sawgraph-kg
rank: 1000
slot_uri: contaminoso:sampleTime
alias: contaminoso_sampleTime
domain_of:
- contaminoso_ContaminantObservation
range: date

```
</details>