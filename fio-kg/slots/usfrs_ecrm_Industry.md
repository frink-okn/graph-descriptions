

# Slot: No slot (predicate) name specified (usfrs_ecrm-Industry)


_No slot (predicate) description specified_






This slot occurs 1 times.


URI: [usfrs:ecrm-Industry](http://sawgraph.spatialai.org/v1/us-frs#ecrm-Industry)



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
| [UsfrsStationary-Facility](../classes/UsfrsStationary-Facility.md) | No class (type) description specified |  no  |
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
| usfrs_FRS-Facility | uri | usfrsdata:d.FRS-Facility.110028675958 | naics:NAICS-IndustryCode-421510 | 1 |
| fio_Facility | uri | usfrsdata:d.FRS-Facility.110028675958 | naics:NAICS-IndustryCode-421510 | 1 |
| __b1 | uri | usfrsdata:d.FRS-Facility.110028675958 | naics:NAICS-IndustryCode-421510 | 1 |




## LinkML Source

<details>

```yaml
name: usfrs_ecrm-Industry
annotations:
  count:
    tag: count
    value: 1
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: naics:NAICS-IndustryCode-421510
    example_object_type: uri
    example_predicate: usfrs:ecrm-Industry
    example_subject: usfrsdata:d.FRS-Facility.110028675958
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: naics:NAICS-IndustryCode-421510
    example_object_type: uri
    example_predicate: usfrs:ecrm-Industry
    example_subject: usfrsdata:d.FRS-Facility.110028675958
    example_subject_type: fio_Facility
- object:
    example_object: naics:NAICS-IndustryCode-421510
    example_object_type: uri
    example_predicate: usfrs:ecrm-Industry
    example_subject: usfrsdata:d.FRS-Facility.110028675958
    example_subject_type: __b1
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:ecrm-Industry
alias: usfrs_ecrm_Industry
domain_of:
- __b1
- fio_Facility
- usfrs_FRS-Facility
range: uri

```
</details>