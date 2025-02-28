

# Slot: No slot (predicate) name specified (usfrs_hasAIRId)


_No slot (predicate) description specified_






This slot occurs 22529 times.


URI: [usfrs:hasAIRId](http://sawgraph.spatialai.org/v1/us-frs#hasAIRId)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UsfrsPotentiallyContaminatedSite-Facility](../classes/UsfrsPotentiallyContaminatedSite-Facility.md) | No class (type) description specified |  yes  |
| [B1](../classes/B1.md) | No class (type) description specified |  yes  |
| [UsfrsEPA-PFAS-Facility](../classes/UsfrsEPA-PFAS-Facility.md) | No class (type) description specified |  yes  |
| [FioFacility](../classes/FioFacility.md) | No class (type) description specified |  yes  |
| [UsfrsWaterfrontFacility-Facility](../classes/UsfrsWaterfrontFacility-Facility.md) | No class (type) description specified |  no  |
| [UsfrsBrownfieldsSite-Facility](../classes/UsfrsBrownfieldsSite-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsContaminationAddressed-Facility](../classes/UsfrsContaminationAddressed-Facility.md) | No class (type) description specified |  no  |
| [UsfrsStationary-Facility](../classes/UsfrsStationary-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsMonitoringStation-Facility](../classes/UsfrsMonitoringStation-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsFederal-Facility](../classes/UsfrsFederal-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsPortable-Facility](../classes/UsfrsPortable-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsBarge-Facility](../classes/UsfrsBarge-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsContaminatedSite-Facility](../classes/UsfrsContaminatedSite-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsWaterSystem-Facility](../classes/UsfrsWaterSystem-Facility.md) | No class (type) description specified |  no  |
| [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| usfrs_Stationary-Facility | string | usfrsdata:d.FRS-Facility.110000314204 | ME0000002303100002 | 22436 |
| usfrs_FRS-Facility | string | usfrsdata:d.FRS-Facility.110000314204 | ME0000002303100002 | 22529 |
| fio_Facility | string | usfrsdata:d.FRS-Facility.110000314204 | ME0000002303100002 | 22529 |
| __b1 | string | usfrsdata:d.FRS-Facility.110000314204 | ME0000002303100002 | 22529 |
| usfrs_EPA-PFAS-Facility | string | usfrsdata:d.FRS-Facility.110000314222 | ME0000002300500672 | 3178 |
| usfrs_Federal-Facility | string | usfrsdata:d.FRS-Facility.110000387714 | OH0000001318001169 | 46 |
| usfrs_ContaminatedSite-Facility | string | usfrsdata:d.FRS-Facility.110000394635 | OH0000000857040734 | 1 |
| usfrs_PotentiallyContaminatedSite-Facility | string | usfrsdata:d.FRS-Facility.110000888585 | IL000031012AAO | 5 |
| usfrs_Barge-Facility | string | usfrsdata:d.FRS-Facility.110009668243 | OH0000000123000290 | 1 |
| usfrs_BrownfieldsSite-Facility | string | usfrsdata:d.FRS-Facility.110015329928 | ME0000002301300019 | 3 |
| usfrs_MonitoringStation-Facility | string | usfrsdata:d.FRS-Facility.110020787022 | IL000031183ACF | 5 |
| usfrs_Portable-Facility | string | usfrsdata:d.FRS-Facility.110064845734 | ME000ACIN000085 | 7 |




## LinkML Source

<details>

```yaml
name: usfrs_hasAIRId
annotations:
  count:
    tag: count
    value: 22529
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: ME0000002303100002
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: usfrs_Stationary-Facility
- object:
    example_object: ME0000002303100002
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: ME0000002303100002
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: fio_Facility
- object:
    example_object: ME0000002303100002
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: __b1
- object:
    example_object: ME0000002300500672
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110000314222
    example_subject_type: usfrs_EPA-PFAS-Facility
- object:
    example_object: OH0000001318001169
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110000387714
    example_subject_type: usfrs_Federal-Facility
- object:
    example_object: OH0000000857040734
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110000394635
    example_subject_type: usfrs_ContaminatedSite-Facility
- object:
    example_object: IL000031012AAO
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110000888585
    example_subject_type: usfrs_PotentiallyContaminatedSite-Facility
- object:
    example_object: OH0000000123000290
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110009668243
    example_subject_type: usfrs_Barge-Facility
- object:
    example_object: ME0000002301300019
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110015329928
    example_subject_type: usfrs_BrownfieldsSite-Facility
- object:
    example_object: IL000031183ACF
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110020787022
    example_subject_type: usfrs_MonitoringStation-Facility
- object:
    example_object: ME000ACIN000085
    example_object_type: string
    example_predicate: usfrs:hasAIRId
    example_subject: usfrsdata:d.FRS-Facility.110064845734
    example_subject_type: usfrs_Portable-Facility
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:hasAIRId
alias: usfrs_hasAIRId
domain_of:
- __b1
- fio_Facility
- usfrs_Barge-Facility
- usfrs_BrownfieldsSite-Facility
- usfrs_ContaminatedSite-Facility
- usfrs_EPA-PFAS-Facility
- usfrs_FRS-Facility
- usfrs_Federal-Facility
- usfrs_MonitoringStation-Facility
- usfrs_Portable-Facility
- usfrs_PotentiallyContaminatedSite-Facility
- usfrs_Stationary-Facility
range: string

```
</details>