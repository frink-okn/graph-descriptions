

# Slot: No slot (predicate) name specified (usfrs_rblc-Industry)


_RACT/BACT/LAER CLEARINGHOUSE Industry Code_






This slot occurs 126 times.


URI: [usfrs:rblc-Industry](http://sawgraph.spatialai.org/v1/us-frs#rblc-Industry)



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

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| __b1 | uri | usfrsdata:d.FRS-Facility.110000314570 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2611 | 126 |
| usfrs_FRS-Facility | uri | usfrsdata:d.FRS-Facility.110000314570 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2611 | 126 |
| fio_Facility | uri | usfrsdata:d.FRS-Facility.110000314570 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2611 | 126 |
| usfrs_EPA-PFAS-Facility | uri | usfrsdata:d.FRS-Facility.110000314570 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2611 | 43 |
| usfrs_Stationary-Facility | uri | usfrsdata:d.FRS-Facility.110000314570 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2611 | 124 |




## LinkML Source

<details>

```yaml
name: usfrs_rblc-Industry
annotations:
  count:
    tag: count
    value: 126
description: RACT/BACT/LAER CLEARINGHOUSE Industry Code
title: No slot (predicate) name specified
examples:
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2611
    example_object_type: uri
    example_predicate: usfrs:rblc-Industry
    example_subject: usfrsdata:d.FRS-Facility.110000314570
    example_subject_type: __b1
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2611
    example_object_type: uri
    example_predicate: usfrs:rblc-Industry
    example_subject: usfrsdata:d.FRS-Facility.110000314570
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2611
    example_object_type: uri
    example_predicate: usfrs:rblc-Industry
    example_subject: usfrsdata:d.FRS-Facility.110000314570
    example_subject_type: fio_Facility
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2611
    example_object_type: uri
    example_predicate: usfrs:rblc-Industry
    example_subject: usfrsdata:d.FRS-Facility.110000314570
    example_subject_type: usfrs_EPA-PFAS-Facility
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-2611
    example_object_type: uri
    example_predicate: usfrs:rblc-Industry
    example_subject: usfrsdata:d.FRS-Facility.110000314570
    example_subject_type: usfrs_Stationary-Facility
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:rblc-Industry
alias: usfrs_rblc_Industry
domain_of:
- __b1
- fio_Facility
- usfrs_EPA-PFAS-Facility
- usfrs_FRS-Facility
- usfrs_Stationary-Facility
range: uri

```
</details>