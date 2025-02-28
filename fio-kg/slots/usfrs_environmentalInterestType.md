

# Slot: No slot (predicate) name specified (usfrs_environmentalInterestType)


_No slot (predicate) description specified_






This slot occurs 100661 times.


URI: [usfrs:environmentalInterestType](http://sawgraph.spatialai.org/v1/us-frs#environmentalInterestType)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UsfrsPotentiallyContaminatedSite-Facility](../classes/UsfrsPotentiallyContaminatedSite-Facility.md) | No class (type) description specified |  yes  |
| [B1](../classes/B1.md) | No class (type) description specified |  yes  |
| [UsfrsEPA-PFAS-Facility](../classes/UsfrsEPA-PFAS-Facility.md) | No class (type) description specified |  yes  |
| [FioFacility](../classes/FioFacility.md) | No class (type) description specified |  yes  |
| [UsfrsWaterfrontFacility-Facility](../classes/UsfrsWaterfrontFacility-Facility.md) | No class (type) description specified |  yes  |
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
| usfrs_Stationary-Facility | string | usfrsdata:d.FRS-Facility.110000314204 | AIR SYNTHETIC MINOR | 95553 |
| usfrs_FRS-Facility | string | usfrsdata:d.FRS-Facility.110000314204 | AIR SYNTHETIC MINOR | 100661 |
| fio_Facility | string | usfrsdata:d.FRS-Facility.110000314204 | AIR SYNTHETIC MINOR | 100661 |
| __b1 | string | usfrsdata:d.FRS-Facility.110000314204 | AIR SYNTHETIC MINOR | 100661 |
| usfrs_EPA-PFAS-Facility | string | usfrsdata:d.FRS-Facility.110000314222 | AIR MINOR | 17250 |
| usfrs_Federal-Facility | string | usfrsdata:d.FRS-Facility.110000387714 | AIR EMISSIONS CLASSIFICATION UNKNOWN | 685 |
| usfrs_ContaminatedSite-Facility | string | usfrsdata:d.FRS-Facility.110000394635 | AIR SYNTHETIC MINOR | 6 |
| usfrs_PotentiallyContaminatedSite-Facility | string | usfrsdata:d.FRS-Facility.110000888585 | AIR EMISSIONS CLASSIFICATION UNKNOWN | 53 |
| usfrs_BrownfieldsSite-Facility | string | usfrsdata:d.FRS-Facility.110001347490 | AIR MINOR | 31 |
| usfrs_Barge-Facility | string | usfrsdata:d.FRS-Facility.110009668243 | AIR MINOR | 6 |
| usfrs_MonitoringStation-Facility | string | usfrsdata:d.FRS-Facility.110020787022 | AIR MINOR | 25 |
| usfrs_Portable-Facility | string | usfrsdata:d.FRS-Facility.110046118330 | STATE MASTER | 202 |
| usfrs_WaterfrontFacility-Facility | string | usfrsdata:d.FRS-Facility.110063004323 | AIR EMISSIONS CLASSIFICATION UNKNOWN | 1 |




## LinkML Source

<details>

```yaml
name: usfrs_environmentalInterestType
annotations:
  count:
    tag: count
    value: 100661
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: AIR SYNTHETIC MINOR
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: usfrs_Stationary-Facility
- object:
    example_object: AIR SYNTHETIC MINOR
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: AIR SYNTHETIC MINOR
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: fio_Facility
- object:
    example_object: AIR SYNTHETIC MINOR
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: __b1
- object:
    example_object: AIR MINOR
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110000314222
    example_subject_type: usfrs_EPA-PFAS-Facility
- object:
    example_object: AIR EMISSIONS CLASSIFICATION UNKNOWN
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110000387714
    example_subject_type: usfrs_Federal-Facility
- object:
    example_object: AIR SYNTHETIC MINOR
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110000394635
    example_subject_type: usfrs_ContaminatedSite-Facility
- object:
    example_object: AIR EMISSIONS CLASSIFICATION UNKNOWN
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110000888585
    example_subject_type: usfrs_PotentiallyContaminatedSite-Facility
- object:
    example_object: AIR MINOR
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110001347490
    example_subject_type: usfrs_BrownfieldsSite-Facility
- object:
    example_object: AIR MINOR
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110009668243
    example_subject_type: usfrs_Barge-Facility
- object:
    example_object: AIR MINOR
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110020787022
    example_subject_type: usfrs_MonitoringStation-Facility
- object:
    example_object: STATE MASTER
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110046118330
    example_subject_type: usfrs_Portable-Facility
- object:
    example_object: AIR EMISSIONS CLASSIFICATION UNKNOWN
    example_object_type: string
    example_predicate: usfrs:environmentalInterestType
    example_subject: usfrsdata:d.FRS-Facility.110063004323
    example_subject_type: usfrs_WaterfrontFacility-Facility
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:environmentalInterestType
alias: usfrs_environmentalInterestType
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
- usfrs_WaterfrontFacility-Facility
range: string

```
</details>