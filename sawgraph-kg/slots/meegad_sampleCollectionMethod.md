

# Slot: No slot description provided (meegad_sampleCollectionMethod)


_No slot description provided_





URI: [meegad:sampleCollectionMethod](http://sawgraph.spatialai.org/v1/me-egad#sampleCollectionMethod)



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
| http://sawgraph.spatialai.org/v1/me-egad-data#sample.WG17641464.AAWH.20230328 meegad:sampleCollectionMethod meegad:samplingMethod.GS |
| http://sawgraph.spatialai.org/v1/me-egad-data#sample.21K040706.CAL.20211104 meegad:sampleCollectionMethod meegad:samplingMethod.NA |

## Comments

* 22824 occurrences with subject type contaminoso_MaterialSample and object type contaminoso_SampleAnnotation.
* 216 occurrences with subject type contaminoso_MaterialSample and object type uri.

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
| self | meegad:sampleCollectionMethod |
| native | sawgraph-kg/:meegad_sampleCollectionMethod |




## LinkML Source

<details>
```yaml
name: meegad_sampleCollectionMethod
description: No slot description provided
title: No slot description provided
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 22824 occurrences with subject type contaminoso_MaterialSample and object type contaminoso_SampleAnnotation.
- 216 occurrences with subject type contaminoso_MaterialSample and object type uri.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#sample.WG17641464.AAWH.20230328
    meegad:sampleCollectionMethod meegad:samplingMethod.GS
- value: http://sawgraph.spatialai.org/v1/me-egad-data#sample.21K040706.CAL.20211104
    meegad:sampleCollectionMethod meegad:samplingMethod.NA
from_schema: sawgraph-kg
rank: 1000
slot_uri: meegad:sampleCollectionMethod
alias: meegad_sampleCollectionMethod
domain_of:
- contaminoso_MaterialSample
subproperty_of: contaminoso_sampleAnnotation
range: Any
any_of:
- range: contaminoso_SampleAnnotation
- range: uri

```
</details>