

# Slot: No slot (predicate) name specified (usfrs_hasOSHAOISId)


_No slot (predicate) description specified_






This slot occurs 10004 times.


URI: [usfrs:hasOSHAOISId](http://sawgraph.spatialai.org/v1/us-frs#hasOSHAOISId)



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
| [UsfrsMonitoringStation-Facility](../classes/UsfrsMonitoringStation-Facility.md) | No class (type) description specified |  no  |
| [UsfrsFederal-Facility](../classes/UsfrsFederal-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsPortable-Facility](../classes/UsfrsPortable-Facility.md) | No class (type) description specified |  no  |
| [UsfrsBarge-Facility](../classes/UsfrsBarge-Facility.md) | No class (type) description specified |  no  |
| [UsfrsContaminatedSite-Facility](../classes/UsfrsContaminatedSite-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsWaterSystem-Facility](../classes/UsfrsWaterSystem-Facility.md) | No class (type) description specified |  no  |
| [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| usfrs_Stationary-Facility | string | usfrsdata:d.FRS-Facility.110000314204 | 342133618 | 4284 |
| usfrs_FRS-Facility | string | usfrsdata:d.FRS-Facility.110000314204 | 342133618 | 10004 |
| fio_Facility | string | usfrsdata:d.FRS-Facility.110000314204 | 342133618 | 10004 |
| __b1 | string | usfrsdata:d.FRS-Facility.110000314204 | 342133618 | 10004 |
| usfrs_EPA-PFAS-Facility | string | usfrsdata:d.FRS-Facility.110000314437 | 341510410 | 1163 |
| usfrs_ContaminatedSite-Facility | string | usfrsdata:d.FRS-Facility.110000394635 | 341266484 | 1 |
| usfrs_BrownfieldsSite-Facility | string | usfrsdata:d.FRS-Facility.110001347490 | 339022170 | 1 |
| usfrs_Federal-Facility | string | usfrsdata:d.FRS-Facility.110040852459 | 340181114 | 113 |
| usfrs_PotentiallyContaminatedSite-Facility | string | usfrsdata:d.FRS-Facility.110070058189 | 338996515 | 10 |




## LinkML Source

<details>

```yaml
name: usfrs_hasOSHAOISId
annotations:
  count:
    tag: count
    value: 10004
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '342133618'
    example_object_type: string
    example_predicate: usfrs:hasOSHAOISId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: usfrs_Stationary-Facility
- object:
    example_object: '342133618'
    example_object_type: string
    example_predicate: usfrs:hasOSHAOISId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: '342133618'
    example_object_type: string
    example_predicate: usfrs:hasOSHAOISId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: fio_Facility
- object:
    example_object: '342133618'
    example_object_type: string
    example_predicate: usfrs:hasOSHAOISId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: __b1
- object:
    example_object: '341510410'
    example_object_type: string
    example_predicate: usfrs:hasOSHAOISId
    example_subject: usfrsdata:d.FRS-Facility.110000314437
    example_subject_type: usfrs_EPA-PFAS-Facility
- object:
    example_object: '341266484'
    example_object_type: string
    example_predicate: usfrs:hasOSHAOISId
    example_subject: usfrsdata:d.FRS-Facility.110000394635
    example_subject_type: usfrs_ContaminatedSite-Facility
- object:
    example_object: '339022170'
    example_object_type: string
    example_predicate: usfrs:hasOSHAOISId
    example_subject: usfrsdata:d.FRS-Facility.110001347490
    example_subject_type: usfrs_BrownfieldsSite-Facility
- object:
    example_object: '340181114'
    example_object_type: string
    example_predicate: usfrs:hasOSHAOISId
    example_subject: usfrsdata:d.FRS-Facility.110040852459
    example_subject_type: usfrs_Federal-Facility
- object:
    example_object: '338996515'
    example_object_type: string
    example_predicate: usfrs:hasOSHAOISId
    example_subject: usfrsdata:d.FRS-Facility.110070058189
    example_subject_type: usfrs_PotentiallyContaminatedSite-Facility
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:hasOSHAOISId
alias: usfrs_hasOSHAOISId
domain_of:
- __b1
- fio_Facility
- usfrs_BrownfieldsSite-Facility
- usfrs_ContaminatedSite-Facility
- usfrs_EPA-PFAS-Facility
- usfrs_FRS-Facility
- usfrs_Federal-Facility
- usfrs_PotentiallyContaminatedSite-Facility
- usfrs_Stationary-Facility
range: string

```
</details>