

# Slot: No slot (predicate) name specified (usfrs_hasRMPId)


_No slot (predicate) description specified_






This slot occurs 1951 times.


URI: [usfrs:hasRMPId](http://sawgraph.spatialai.org/v1/us-frs#hasRMPId)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UsfrsPotentiallyContaminatedSite-Facility](../classes/UsfrsPotentiallyContaminatedSite-Facility.md) | No class (type) description specified |  yes  |
| [B1](../classes/B1.md) | No class (type) description specified |  yes  |
| [UsfrsEPA-PFAS-Facility](../classes/UsfrsEPA-PFAS-Facility.md) | No class (type) description specified |  yes  |
| [FioFacility](../classes/FioFacility.md) | No class (type) description specified |  yes  |
| [UsfrsWaterfrontFacility-Facility](../classes/UsfrsWaterfrontFacility-Facility.md) | No class (type) description specified |  no  |
| [UsfrsBrownfieldsSite-Facility](../classes/UsfrsBrownfieldsSite-Facility.md) | No class (type) description specified |  no  |
| [UsfrsContaminationAddressed-Facility](../classes/UsfrsContaminationAddressed-Facility.md) | No class (type) description specified |  no  |
| [UsfrsStationary-Facility](../classes/UsfrsStationary-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsMonitoringStation-Facility](../classes/UsfrsMonitoringStation-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsFederal-Facility](../classes/UsfrsFederal-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsPortable-Facility](../classes/UsfrsPortable-Facility.md) | No class (type) description specified |  no  |
| [UsfrsBarge-Facility](../classes/UsfrsBarge-Facility.md) | No class (type) description specified |  no  |
| [UsfrsContaminatedSite-Facility](../classes/UsfrsContaminatedSite-Facility.md) | No class (type) description specified |  no  |
| [UsfrsWaterSystem-Facility](../classes/UsfrsWaterSystem-Facility.md) | No class (type) description specified |  no  |
| [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| __b1 | string | usfrsdata:d.FRS-Facility.110000314375 | 100000184392 | 1951 |
| usfrs_FRS-Facility | string | usfrsdata:d.FRS-Facility.110000314375 | 100000184392 | 1951 |
| fio_Facility | string | usfrsdata:d.FRS-Facility.110000314375 | 100000184392 | 1951 |
| usfrs_EPA-PFAS-Facility | string | usfrsdata:d.FRS-Facility.110000314375 | 100000184392 | 331 |
| usfrs_Stationary-Facility | string | usfrsdata:d.FRS-Facility.110000314375 | 100000184392 | 1937 |
| usfrs_Federal-Facility | string | usfrsdata:d.FRS-Facility.110000395260 | 100000212254 | 3 |
| usfrs_PotentiallyContaminatedSite-Facility | string | usfrsdata:d.FRS-Facility.110000888585 | 100000143702 | 1 |
| usfrs_MonitoringStation-Facility | string | usfrsdata:d.FRS-Facility.110020868943 | 100000045159 | 1 |




## LinkML Source

<details>

```yaml
name: usfrs_hasRMPId
annotations:
  count:
    tag: count
    value: 1951
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '100000184392'
    example_object_type: string
    example_predicate: usfrs:hasRMPId
    example_subject: usfrsdata:d.FRS-Facility.110000314375
    example_subject_type: __b1
- object:
    example_object: '100000184392'
    example_object_type: string
    example_predicate: usfrs:hasRMPId
    example_subject: usfrsdata:d.FRS-Facility.110000314375
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: '100000184392'
    example_object_type: string
    example_predicate: usfrs:hasRMPId
    example_subject: usfrsdata:d.FRS-Facility.110000314375
    example_subject_type: fio_Facility
- object:
    example_object: '100000184392'
    example_object_type: string
    example_predicate: usfrs:hasRMPId
    example_subject: usfrsdata:d.FRS-Facility.110000314375
    example_subject_type: usfrs_EPA-PFAS-Facility
- object:
    example_object: '100000184392'
    example_object_type: string
    example_predicate: usfrs:hasRMPId
    example_subject: usfrsdata:d.FRS-Facility.110000314375
    example_subject_type: usfrs_Stationary-Facility
- object:
    example_object: '100000212254'
    example_object_type: string
    example_predicate: usfrs:hasRMPId
    example_subject: usfrsdata:d.FRS-Facility.110000395260
    example_subject_type: usfrs_Federal-Facility
- object:
    example_object: '100000143702'
    example_object_type: string
    example_predicate: usfrs:hasRMPId
    example_subject: usfrsdata:d.FRS-Facility.110000888585
    example_subject_type: usfrs_PotentiallyContaminatedSite-Facility
- object:
    example_object: '100000045159'
    example_object_type: string
    example_predicate: usfrs:hasRMPId
    example_subject: usfrsdata:d.FRS-Facility.110020868943
    example_subject_type: usfrs_MonitoringStation-Facility
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:hasRMPId
alias: usfrs_hasRMPId
domain_of:
- __b1
- fio_Facility
- usfrs_EPA-PFAS-Facility
- usfrs_FRS-Facility
- usfrs_Federal-Facility
- usfrs_MonitoringStation-Facility
- usfrs_PotentiallyContaminatedSite-Facility
- usfrs_Stationary-Facility
range: string

```
</details>