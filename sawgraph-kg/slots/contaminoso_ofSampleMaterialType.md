

# Slot: No slot description provided (contaminoso_ofSampleMaterialType)


_No slot description provided_





URI: [contaminoso:ofSampleMaterialType](http://sawgraph.spatialai.org/v1/contaminoso#ofSampleMaterialType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoMaterialSample](../classes/ContaminosoMaterialSample.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ContaminosoMaterialType](../classes/ContaminosoMaterialType.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#sample.WG17641464.AAWH.20230328 contaminoso:ofSampleMaterialType meegad:sampleMaterialType.GW |

## Comments

* 23025 occurrences with subject type contaminoso_MaterialSample and object type contaminoso_MaterialType.

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
| self | contaminoso:ofSampleMaterialType |
| native | sawgraph-kg/:contaminoso_ofSampleMaterialType |




## LinkML Source

<details>
```yaml
name: contaminoso_ofSampleMaterialType
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 23025 occurrences with subject type contaminoso_MaterialSample and object type contaminoso_MaterialType.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#sample.WG17641464.AAWH.20230328
    contaminoso:ofSampleMaterialType meegad:sampleMaterialType.GW
from_schema: sawgraph-kg
rank: 1000
domain: contaminoso_MaterialSample
slot_uri: contaminoso:ofSampleMaterialType
alias: contaminoso_ofSampleMaterialType
domain_of:
- contaminoso_MaterialSample
range: Any
any_of:
- range: contaminoso_MaterialType
- range: uri

```
</details>