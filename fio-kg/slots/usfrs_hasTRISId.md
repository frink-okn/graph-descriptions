

# Slot: No slot (predicate) name specified (usfrs_hasTRISId)


_No slot (predicate) description specified_






This slot occurs 6452 times.


URI: [usfrs:hasTRISId](http://sawgraph.spatialai.org/v1/us-frs#hasTRISId)



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
| [UsfrsBarge-Facility](../classes/UsfrsBarge-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsContaminatedSite-Facility](../classes/UsfrsContaminatedSite-Facility.md) | No class (type) description specified |  no  |
| [UsfrsWaterSystem-Facility](../classes/UsfrsWaterSystem-Facility.md) | No class (type) description specified |  no  |
| [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:string](http://www.w3.org/2001/XMLSchema#string)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| usfrs_Stationary-Facility | string | usfrsdata:d.FRS-Facility.110000314204 | 03906PRTTWROUTE | 6358 |
| usfrs_FRS-Facility | string | usfrsdata:d.FRS-Facility.110000314204 | 03906PRTTWROUTE | 6452 |
| fio_Facility | string | usfrsdata:d.FRS-Facility.110000314204 | 03906PRTTWROUTE | 6452 |
| __b1 | string | usfrsdata:d.FRS-Facility.110000314204 | 03906PRTTWROUTE | 6452 |
| usfrs_EPA-PFAS-Facility | string | usfrsdata:d.FRS-Facility.110000314222 | 04011RRWHR1CRES | 2759 |
| usfrs_Federal-Facility | string | usfrsdata:d.FRS-Facility.110000387714 | 44135NSLWS21000 | 42 |
| usfrs_PotentiallyContaminatedSite-Facility | string | usfrsdata:d.FRS-Facility.110000888585 | 60638NLCCH6216W | 5 |
| usfrs_BrownfieldsSite-Facility | string | usfrsdata:d.FRS-Facility.110002088400 | 04234KRYTNRTE2A | 5 |
| usfrs_Barge-Facility | string | usfrsdata:d.FRS-Facility.110009668243 | 43130TXCNC265QU | 1 |




## LinkML Source

<details>

```yaml
name: usfrs_hasTRISId
annotations:
  count:
    tag: count
    value: 6452
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: 03906PRTTWROUTE
    example_object_type: string
    example_predicate: usfrs:hasTRISId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: usfrs_Stationary-Facility
- object:
    example_object: 03906PRTTWROUTE
    example_object_type: string
    example_predicate: usfrs:hasTRISId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: 03906PRTTWROUTE
    example_object_type: string
    example_predicate: usfrs:hasTRISId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: fio_Facility
- object:
    example_object: 03906PRTTWROUTE
    example_object_type: string
    example_predicate: usfrs:hasTRISId
    example_subject: usfrsdata:d.FRS-Facility.110000314204
    example_subject_type: __b1
- object:
    example_object: 04011RRWHR1CRES
    example_object_type: string
    example_predicate: usfrs:hasTRISId
    example_subject: usfrsdata:d.FRS-Facility.110000314222
    example_subject_type: usfrs_EPA-PFAS-Facility
- object:
    example_object: 44135NSLWS21000
    example_object_type: string
    example_predicate: usfrs:hasTRISId
    example_subject: usfrsdata:d.FRS-Facility.110000387714
    example_subject_type: usfrs_Federal-Facility
- object:
    example_object: 60638NLCCH6216W
    example_object_type: string
    example_predicate: usfrs:hasTRISId
    example_subject: usfrsdata:d.FRS-Facility.110000888585
    example_subject_type: usfrs_PotentiallyContaminatedSite-Facility
- object:
    example_object: 04234KRYTNRTE2A
    example_object_type: string
    example_predicate: usfrs:hasTRISId
    example_subject: usfrsdata:d.FRS-Facility.110002088400
    example_subject_type: usfrs_BrownfieldsSite-Facility
- object:
    example_object: 43130TXCNC265QU
    example_object_type: string
    example_predicate: usfrs:hasTRISId
    example_subject: usfrsdata:d.FRS-Facility.110009668243
    example_subject_type: usfrs_Barge-Facility
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:hasTRISId
alias: usfrs_hasTRISId
domain_of:
- __b1
- fio_Facility
- usfrs_Barge-Facility
- usfrs_BrownfieldsSite-Facility
- usfrs_EPA-PFAS-Facility
- usfrs_FRS-Facility
- usfrs_Federal-Facility
- usfrs_PotentiallyContaminatedSite-Facility
- usfrs_Stationary-Facility
range: string

```
</details>