

# Slot: No slot description provided (contaminoso_sampleAnnotation)


_No slot description provided_





URI: [contaminoso:sampleAnnotation](http://sawgraph.spatialai.org/v1/contaminoso#sampleAnnotation)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoMaterialSample](../classes/ContaminosoMaterialSample.md) | No type description provided |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ContaminosoSampleAnnotation](../classes/ContaminosoSampleAnnotation.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#sample.WG17641464.AAWH.20230328 contaminoso:sampleAnnotation meegad:treatmentStatus.N |
| http://sawgraph.spatialai.org/v1/me-egad-data#sample.1028303.ELL.20190405 contaminoso:sampleAnnotation meegad:sampleLocation.NA |

## Comments

* 55252 occurrences with subject type contaminoso_MaterialSample and object type contaminoso_SampleAnnotation.
* 9263 occurrences with subject type contaminoso_MaterialSample and object type uri.

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
| self | contaminoso:sampleAnnotation |
| native | sawgraph-kg/:contaminoso_sampleAnnotation |




## LinkML Source

<details>
```yaml
name: contaminoso_sampleAnnotation
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 55252 occurrences with subject type contaminoso_MaterialSample and object type contaminoso_SampleAnnotation.
- 9263 occurrences with subject type contaminoso_MaterialSample and object type uri.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#sample.WG17641464.AAWH.20230328
    contaminoso:sampleAnnotation meegad:treatmentStatus.N
- value: http://sawgraph.spatialai.org/v1/me-egad-data#sample.1028303.ELL.20190405
    contaminoso:sampleAnnotation meegad:sampleLocation.NA
from_schema: sawgraph-kg
rank: 1000
slot_uri: contaminoso:sampleAnnotation
alias: contaminoso_sampleAnnotation
domain_of:
- contaminoso_MaterialSample
range: Any
any_of:
- range: contaminoso_SampleAnnotation
- range: uri

```
</details>