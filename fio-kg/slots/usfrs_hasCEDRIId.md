

# Slot: No slot (predicate) name specified (usfrs_hasCEDRIId)


_No slot (predicate) description specified_






This slot occurs 38 times.


URI: [usfrs:hasCEDRIId](http://sawgraph.spatialai.org/v1/us-frs#hasCEDRIId)



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
| usfrs_Stationary-Facility | string | usfrsdata:d.FRS-Facility.110000382979 | CEDRI82641 | 37 |
| usfrs_FRS-Facility | string | usfrsdata:d.FRS-Facility.110000382979 | CEDRI82641 | 38 |
| fio_Facility | string | usfrsdata:d.FRS-Facility.110000382979 | CEDRI82641 | 38 |
| __b1 | string | usfrsdata:d.FRS-Facility.110000382979 | CEDRI82641 | 38 |
| usfrs_EPA-PFAS-Facility | string | usfrsdata:d.FRS-Facility.110000389963 | CEDRI10020242 | 5 |




## LinkML Source

<details>

```yaml
name: usfrs_hasCEDRIId
annotations:
  count:
    tag: count
    value: 38
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: CEDRI82641
    example_object_type: string
    example_predicate: usfrs:hasCEDRIId
    example_subject: usfrsdata:d.FRS-Facility.110000382979
    example_subject_type: usfrs_Stationary-Facility
- object:
    example_object: CEDRI82641
    example_object_type: string
    example_predicate: usfrs:hasCEDRIId
    example_subject: usfrsdata:d.FRS-Facility.110000382979
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: CEDRI82641
    example_object_type: string
    example_predicate: usfrs:hasCEDRIId
    example_subject: usfrsdata:d.FRS-Facility.110000382979
    example_subject_type: fio_Facility
- object:
    example_object: CEDRI82641
    example_object_type: string
    example_predicate: usfrs:hasCEDRIId
    example_subject: usfrsdata:d.FRS-Facility.110000382979
    example_subject_type: __b1
- object:
    example_object: CEDRI10020242
    example_object_type: string
    example_predicate: usfrs:hasCEDRIId
    example_subject: usfrsdata:d.FRS-Facility.110000389963
    example_subject_type: usfrs_EPA-PFAS-Facility
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:hasCEDRIId
alias: usfrs_hasCEDRIId
domain_of:
- __b1
- fio_Facility
- usfrs_EPA-PFAS-Facility
- usfrs_FRS-Facility
- usfrs_Stationary-Facility
range: string

```
</details>