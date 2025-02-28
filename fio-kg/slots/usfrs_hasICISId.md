

# Slot: No slot (predicate) name specified (usfrs_hasICISId)


_No slot (predicate) description specified_






This slot occurs 1065 times.


URI: [usfrs:hasICISId](http://sawgraph.spatialai.org/v1/us-frs#hasICISId)



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
| usfrs_Stationary-Facility | string | usfrsdata:d.FRS-Facility.110000383166 | 6679785 | 1057 |
| usfrs_FRS-Facility | string | usfrsdata:d.FRS-Facility.110000383166 | 6679785 | 1065 |
| fio_Facility | string | usfrsdata:d.FRS-Facility.110000383166 | 6679785 | 1065 |
| __b1 | string | usfrsdata:d.FRS-Facility.110000383166 | 6679785 | 1065 |
| usfrs_EPA-PFAS-Facility | string | usfrsdata:d.FRS-Facility.110000383987 | 1400020735 | 196 |
| usfrs_Federal-Facility | string | usfrsdata:d.FRS-Facility.110000815351 | 2600014665 | 7 |
| usfrs_MonitoringStation-Facility | string | usfrsdata:d.FRS-Facility.110020881517 | 1800063593 | 1 |




## LinkML Source

<details>

```yaml
name: usfrs_hasICISId
annotations:
  count:
    tag: count
    value: 1065
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '6679785'
    example_object_type: string
    example_predicate: usfrs:hasICISId
    example_subject: usfrsdata:d.FRS-Facility.110000383166
    example_subject_type: usfrs_Stationary-Facility
- object:
    example_object: '6679785'
    example_object_type: string
    example_predicate: usfrs:hasICISId
    example_subject: usfrsdata:d.FRS-Facility.110000383166
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: '6679785'
    example_object_type: string
    example_predicate: usfrs:hasICISId
    example_subject: usfrsdata:d.FRS-Facility.110000383166
    example_subject_type: fio_Facility
- object:
    example_object: '6679785'
    example_object_type: string
    example_predicate: usfrs:hasICISId
    example_subject: usfrsdata:d.FRS-Facility.110000383166
    example_subject_type: __b1
- object:
    example_object: '1400020735'
    example_object_type: string
    example_predicate: usfrs:hasICISId
    example_subject: usfrsdata:d.FRS-Facility.110000383987
    example_subject_type: usfrs_EPA-PFAS-Facility
- object:
    example_object: '2600014665'
    example_object_type: string
    example_predicate: usfrs:hasICISId
    example_subject: usfrsdata:d.FRS-Facility.110000815351
    example_subject_type: usfrs_Federal-Facility
- object:
    example_object: '1800063593'
    example_object_type: string
    example_predicate: usfrs:hasICISId
    example_subject: usfrsdata:d.FRS-Facility.110020881517
    example_subject_type: usfrs_MonitoringStation-Facility
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:hasICISId
alias: usfrs_hasICISId
domain_of:
- __b1
- fio_Facility
- usfrs_EPA-PFAS-Facility
- usfrs_FRS-Facility
- usfrs_Federal-Facility
- usfrs_MonitoringStation-Facility
- usfrs_Stationary-Facility
range: string

```
</details>