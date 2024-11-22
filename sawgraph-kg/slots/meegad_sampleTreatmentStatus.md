

# Slot: TODO -- tell the world what this slot (predicate) describes. (meegad_sampleTreatmentStatus)


_TODO -- tell the world what this slot (predicate) describes._





URI: [meegad:sampleTreatmentStatus](http://sawgraph.spatialai.org/v1/me-egad#sampleTreatmentStatus)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [ContaminosoMaterialSample](../classes/ContaminosoMaterialSample.md) | TODO -- tell the world what this class (type) describes |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[ContaminosoSampleAnnotation](../classes/ContaminosoSampleAnnotation.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Value |
| --- |
| http://sawgraph.spatialai.org/v1/me-egad-data#sample.1028303.ELL.20190405 meegad:sampleTreatmentStatus meegad:treatmentStatus.NA |
| http://sawgraph.spatialai.org/v1/me-egad-data#sample.WG17641464.AAWH.20230328 meegad:sampleTreatmentStatus meegad:treatmentStatus.N |

## Comments

* 1693 occurrences with subject type contaminoso_MaterialSample and object type uri.
* 16736 occurrences with subject type contaminoso_MaterialSample and object type contaminoso_SampleAnnotation.

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
| self | meegad:sampleTreatmentStatus |
| native | sawgraph-kg/:meegad_sampleTreatmentStatus |




## LinkML Source

<details>
```yaml
name: meegad_sampleTreatmentStatus
description: TODO -- tell the world what this slot (predicate) describes.
title: TODO -- tell the world what this slot (predicate) describes.
todos:
- TODO -- Todos for this slot go here
- or you can delete the todos
- if you think the class is perfect.
comments:
- 1693 occurrences with subject type contaminoso_MaterialSample and object type uri.
- 16736 occurrences with subject type contaminoso_MaterialSample and object type contaminoso_SampleAnnotation.
examples:
- value: http://sawgraph.spatialai.org/v1/me-egad-data#sample.1028303.ELL.20190405
    meegad:sampleTreatmentStatus meegad:treatmentStatus.NA
- value: http://sawgraph.spatialai.org/v1/me-egad-data#sample.WG17641464.AAWH.20230328
    meegad:sampleTreatmentStatus meegad:treatmentStatus.N
from_schema: sawgraph-kg
rank: 1000
slot_uri: meegad:sampleTreatmentStatus
alias: meegad_sampleTreatmentStatus
domain_of:
- contaminoso_MaterialSample
subproperty_of: contaminoso_sampleAnnotation
range: Any
any_of:
- range: contaminoso_SampleAnnotation
- range: uri

```
</details>