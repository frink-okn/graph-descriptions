

# Slot: No slot (predicate) name specified (usfrs_hasRCRAINFOId)


_No slot (predicate) description specified_






This slot occurs 30246 times.


URI: [usfrs:hasRCRAINFOId](http://sawgraph.spatialai.org/v1/us-frs#hasRCRAINFOId)



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
| [UsfrsPortable-Facility](../classes/UsfrsPortable-Facility.md) | No class (type) description specified |  no  |
| [UsfrsBarge-Facility](../classes/UsfrsBarge-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsContaminatedSite-Facility](../classes/UsfrsContaminatedSite-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsWaterSystem-Facility](../classes/UsfrsWaterSystem-Facility.md) | No class (type) description specified |  no  |
| [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| usfrs_Stationary-Facility | string | usfrsdata:d.FRS-Facility.110000314204 | MED000791681 | 30115 |
| usfrs_FRS-Facility | string | usfrsdata:d.FRS-Facility.110000314204 | MED000791681 | 30246 |
| fio_Facility | string | usfrsdata:d.FRS-Facility.110000314204 | MED000791681 | 30246 |
| __b1 | string | usfrsdata:d.FRS-Facility.110000314204 | MED000791681 | 30246 |
| usfrs_EPA-PFAS-Facility | string | usfrsdata:d.FRS-Facility.110000314295 | MED054608179 | 3597 |
| usfrs_Federal-Facility | string | usfrsdata:d.FRS-Facility.110000387714 | OH0800005035 | 354 |
| usfrs_ContaminatedSite-Facility | string | usfrsdata:d.FRS-Facility.110000394635 | OHD074703547 | 1 |
| usfrs_PotentiallyContaminatedSite-Facility | string | usfrsdata:d.FRS-Facility.110000888585 | ILD005092572 | 29 |
| usfrs_BrownfieldsSite-Facility | string | usfrsdata:d.FRS-Facility.110004576646 | OH0000865501 | 14 |
| usfrs_Barge-Facility | string | usfrsdata:d.FRS-Facility.110009668243 | OHD071654958 | 1 |
| usfrs_MonitoringStation-Facility | string | usfrsdata:d.FRS-Facility.110020868881 | ILR000144659 | 10 |




## LinkML Source

<details>

```yaml
name: usfrs_hasRCRAINFOId
annotations:
  count:
    tag: count
    value: 30246
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: MED000791681
    example_object_type: string
    example_predicate: usfrs:hasRCRAINFOId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: usfrs_Stationary-Facility
- object:
    example_object: MED000791681
    example_object_type: string
    example_predicate: usfrs:hasRCRAINFOId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: MED000791681
    example_object_type: string
    example_predicate: usfrs:hasRCRAINFOId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: fio_Facility
- object:
    example_object: MED000791681
    example_object_type: string
    example_predicate: usfrs:hasRCRAINFOId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: __b1
- object:
    example_object: MED054608179
    example_object_type: string
    example_predicate: usfrs:hasRCRAINFOId
    example_subject: usfrsdata:d.FRS-Facility.110000314295
    example_subject_type: usfrs_EPA-PFAS-Facility
- object:
    example_object: OH0800005035
    example_object_type: string
    example_predicate: usfrs:hasRCRAINFOId
    example_subject: usfrsdata:d.FRS-Facility.110000387714
    example_subject_type: usfrs_Federal-Facility
- object:
    example_object: OHD074703547
    example_object_type: string
    example_predicate: usfrs:hasRCRAINFOId
    example_subject: usfrsdata:d.FRS-Facility.110000394635
    example_subject_type: usfrs_ContaminatedSite-Facility
- object:
    example_object: ILD005092572
    example_object_type: string
    example_predicate: usfrs:hasRCRAINFOId
    example_subject: usfrsdata:d.FRS-Facility.110000888585
    example_subject_type: usfrs_PotentiallyContaminatedSite-Facility
- object:
    example_object: OH0000865501
    example_object_type: string
    example_predicate: usfrs:hasRCRAINFOId
    example_subject: usfrsdata:d.FRS-Facility.110004576646
    example_subject_type: usfrs_BrownfieldsSite-Facility
- object:
    example_object: OHD071654958
    example_object_type: string
    example_predicate: usfrs:hasRCRAINFOId
    example_subject: usfrsdata:d.FRS-Facility.110009668243
    example_subject_type: usfrs_Barge-Facility
- object:
    example_object: ILR000144659
    example_object_type: string
    example_predicate: usfrs:hasRCRAINFOId
    example_subject: usfrsdata:d.FRS-Facility.110020868881
    example_subject_type: usfrs_MonitoringStation-Facility
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:hasRCRAINFOId
alias: usfrs_hasRCRAINFOId
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
- usfrs_PotentiallyContaminatedSite-Facility
- usfrs_Stationary-Facility
range: string

```
</details>