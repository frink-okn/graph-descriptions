

# Slot: No slot description provided (contaminoso_analysisDate)


_No slot description provided_





URI: [contaminoso:analysisDate](http://sawgraph.spatialai.org/v1/contaminoso#analysisDate)



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
| http://sawgraph.spatialai.org/v1/me-egad-data#observation.1028303.ELL.20190405.45298906 contaminoso:analysisDate 2019-04-12 |

## Comments

* 142853 occurrences with subject type contaminoso_ContaminantObservation and object type date.

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
| self | contaminoso:analysisDate |
| native | sawgraph-kg/:contaminoso_analysisDate |




## LinkML Source

<details>
```yaml
name: contaminoso_analysisDate
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 142853 occurrences with subject type contaminoso_ContaminantObservation and object
  type date.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#observation.1028303.ELL.20190405.45298906
    contaminoso:analysisDate 2019-04-12
from_schema: sawgraph-kg
rank: 1000
slot_uri: contaminoso:analysisDate
alias: contaminoso_analysisDate
domain_of:
- contaminoso_ContaminantObservation
subproperty_of: sosa_resultTime
range: date

```
</details>