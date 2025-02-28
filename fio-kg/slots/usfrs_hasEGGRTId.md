

# Slot: No slot (predicate) name specified (usfrs_hasEGGRTId)


_No slot (predicate) description specified_






This slot occurs 497 times.


URI: [usfrs:hasEGGRTId](http://sawgraph.spatialai.org/v1/us-frs#hasEGGRTId)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UsfrsPotentiallyContaminatedSite-Facility](../classes/UsfrsPotentiallyContaminatedSite-Facility.md) | No class (type) description specified |  no  |
| [B1](../classes/B1.md) | No class (type) description specified |  yes  |
| [UsfrsEPA-PFAS-Facility](../classes/UsfrsEPA-PFAS-Facility.md) | No class (type) description specified |  yes  |
| [FioFacility](../classes/FioFacility.md) | No class (type) description specified |  yes  |
| [UsfrsWaterfrontFacility-Facility](../classes/UsfrsWaterfrontFacility-Facility.md) | No class (type) description specified |  no  |
| [UsfrsBrownfieldsSite-Facility](../classes/UsfrsBrownfieldsSite-Facility.md) | No class (type) description specified |  no  |
| [UsfrsContaminationAddressed-Facility](../classes/UsfrsContaminationAddressed-Facility.md) | No class (type) description specified |  no  |
| [UsfrsStationary-Facility](../classes/UsfrsStationary-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsMonitoringStation-Facility](../classes/UsfrsMonitoringStation-Facility.md) | No class (type) description specified |  no  |
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
| __b1 | string | usfrsdata:d.FRS-Facility.110000314375 | 1009581 | 497 |
| usfrs_FRS-Facility | string | usfrsdata:d.FRS-Facility.110000314375 | 1009581 | 497 |
| fio_Facility | string | usfrsdata:d.FRS-Facility.110000314375 | 1009581 | 497 |
| usfrs_EPA-PFAS-Facility | string | usfrsdata:d.FRS-Facility.110000314375 | 1009581 | 182 |
| usfrs_Stationary-Facility | string | usfrsdata:d.FRS-Facility.110000314375 | 1009581 | 489 |
| usfrs_Federal-Facility | string | usfrsdata:d.FRS-Facility.110000395260 | 1003709 | 2 |




## LinkML Source

<details>

```yaml
name: usfrs_hasEGGRTId
annotations:
  count:
    tag: count
    value: 497
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '1009581'
    example_object_type: string
    example_predicate: usfrs:hasEGGRTId
    example_subject: usfrsdata:d.FRS-Facility.110000314375
    example_subject_type: __b1
- object:
    example_object: '1009581'
    example_object_type: string
    example_predicate: usfrs:hasEGGRTId
    example_subject: usfrsdata:d.FRS-Facility.110000314375
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: '1009581'
    example_object_type: string
    example_predicate: usfrs:hasEGGRTId
    example_subject: usfrsdata:d.FRS-Facility.110000314375
    example_subject_type: fio_Facility
- object:
    example_object: '1009581'
    example_object_type: string
    example_predicate: usfrs:hasEGGRTId
    example_subject: usfrsdata:d.FRS-Facility.110000314375
    example_subject_type: usfrs_EPA-PFAS-Facility
- object:
    example_object: '1009581'
    example_object_type: string
    example_predicate: usfrs:hasEGGRTId
    example_subject: usfrsdata:d.FRS-Facility.110000314375
    example_subject_type: usfrs_Stationary-Facility
- object:
    example_object: '1003709'
    example_object_type: string
    example_predicate: usfrs:hasEGGRTId
    example_subject: usfrsdata:d.FRS-Facility.110000395260
    example_subject_type: usfrs_Federal-Facility
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:hasEGGRTId
alias: usfrs_hasEGGRTId
domain_of:
- __b1
- fio_Facility
- usfrs_EPA-PFAS-Facility
- usfrs_FRS-Facility
- usfrs_Federal-Facility
- usfrs_Stationary-Facility
range: string

```
</details>