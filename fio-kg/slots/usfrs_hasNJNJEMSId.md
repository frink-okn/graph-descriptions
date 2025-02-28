

# Slot: No slot (predicate) name specified (usfrs_hasNJNJEMSId)


_No slot (predicate) description specified_






This slot occurs 4 times.


URI: [usfrs:hasNJNJEMSId](http://sawgraph.spatialai.org/v1/us-frs#hasNJNJEMSId)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UsfrsPotentiallyContaminatedSite-Facility](../classes/UsfrsPotentiallyContaminatedSite-Facility.md) | No class (type) description specified |  no  |
| [B1](../classes/B1.md) | No class (type) description specified |  yes  |
| [UsfrsEPA-PFAS-Facility](../classes/UsfrsEPA-PFAS-Facility.md) | No class (type) description specified |  no  |
| [FioFacility](../classes/FioFacility.md) | No class (type) description specified |  yes  |
| [UsfrsWaterfrontFacility-Facility](../classes/UsfrsWaterfrontFacility-Facility.md) | No class (type) description specified |  no  |
| [UsfrsBrownfieldsSite-Facility](../classes/UsfrsBrownfieldsSite-Facility.md) | No class (type) description specified |  no  |
| [UsfrsContaminationAddressed-Facility](../classes/UsfrsContaminationAddressed-Facility.md) | No class (type) description specified |  no  |
| [UsfrsStationary-Facility](../classes/UsfrsStationary-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsMonitoringStation-Facility](../classes/UsfrsMonitoringStation-Facility.md) | No class (type) description specified |  no  |
| [UsfrsFederal-Facility](../classes/UsfrsFederal-Facility.md) | No class (type) description specified |  no  |
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
| usfrs_Stationary-Facility | string | usfrsdata:d.FRS-Facility.110014836357 | 124450 | 3 |
| usfrs_FRS-Facility | string | usfrsdata:d.FRS-Facility.110014836357 | 124450 | 4 |
| fio_Facility | string | usfrsdata:d.FRS-Facility.110014836357 | 124450 | 4 |
| __b1 | string | usfrsdata:d.FRS-Facility.110014836357 | 124450 | 4 |




## LinkML Source

<details>

```yaml
name: usfrs_hasNJNJEMSId
annotations:
  count:
    tag: count
    value: 4
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '124450'
    example_object_type: string
    example_predicate: usfrs:hasNJNJEMSId
    example_subject: usfrsdata:d.FRS-Facility.110014836357
    example_subject_type: usfrs_Stationary-Facility
- object:
    example_object: '124450'
    example_object_type: string
    example_predicate: usfrs:hasNJNJEMSId
    example_subject: usfrsdata:d.FRS-Facility.110014836357
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: '124450'
    example_object_type: string
    example_predicate: usfrs:hasNJNJEMSId
    example_subject: usfrsdata:d.FRS-Facility.110014836357
    example_subject_type: fio_Facility
- object:
    example_object: '124450'
    example_object_type: string
    example_predicate: usfrs:hasNJNJEMSId
    example_subject: usfrsdata:d.FRS-Facility.110014836357
    example_subject_type: __b1
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:hasNJNJEMSId
alias: usfrs_hasNJNJEMSId
domain_of:
- __b1
- fio_Facility
- usfrs_FRS-Facility
- usfrs_Stationary-Facility
range: string

```
</details>