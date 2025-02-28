

# Slot: No slot (predicate) name specified (usfrs_tscaIndustry)


_Toxic Substances Control Act Industry Code_






This slot occurs 536 times.


URI: [usfrs:tscaIndustry](http://sawgraph.spatialai.org/v1/us-frs#tscaIndustry)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [UsfrsPotentiallyContaminatedSite-Facility](../classes/UsfrsPotentiallyContaminatedSite-Facility.md) | No class (type) description specified |  no  |
| [B1](../classes/B1.md) | No class (type) description specified |  yes  |
| [UsfrsEPA-PFAS-Facility](../classes/UsfrsEPA-PFAS-Facility.md) | No class (type) description specified |  yes  |
| [FioFacility](../classes/FioFacility.md) | No class (type) description specified |  yes  |
| [UsfrsWaterfrontFacility-Facility](../classes/UsfrsWaterfrontFacility-Facility.md) | No class (type) description specified |  no  |
| [UsfrsBrownfieldsSite-Facility](../classes/UsfrsBrownfieldsSite-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsContaminationAddressed-Facility](../classes/UsfrsContaminationAddressed-Facility.md) | No class (type) description specified |  no  |
| [UsfrsStationary-Facility](../classes/UsfrsStationary-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsMonitoringStation-Facility](../classes/UsfrsMonitoringStation-Facility.md) | No class (type) description specified |  no  |
| [UsfrsFederal-Facility](../classes/UsfrsFederal-Facility.md) | No class (type) description specified |  no  |
| [UsfrsPortable-Facility](../classes/UsfrsPortable-Facility.md) | No class (type) description specified |  no  |
| [UsfrsBarge-Facility](../classes/UsfrsBarge-Facility.md) | No class (type) description specified |  no  |
| [UsfrsContaminatedSite-Facility](../classes/UsfrsContaminatedSite-Facility.md) | No class (type) description specified |  yes  |
| [UsfrsWaterSystem-Facility](../classes/UsfrsWaterSystem-Facility.md) | No class (type) description specified |  no  |
| [UsfrsFRS-Facility](../classes/UsfrsFRS-Facility.md) | No class (type) description specified |  yes  |







## Properties

* Range: [xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| usfrs_Stationary-Facility | uri | usfrsdata:d.FRS-Facility.110000314464 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3441 | 532 |
| usfrs_FRS-Facility | uri | usfrsdata:d.FRS-Facility.110000314464 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3441 | 536 |
| fio_Facility | uri | usfrsdata:d.FRS-Facility.110000314464 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3441 | 536 |
| __b1 | uri | usfrsdata:d.FRS-Facility.110000314464 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3441 | 536 |
| usfrs_EPA-PFAS-Facility | uri | usfrsdata:d.FRS-Facility.110000381934 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3499 | 129 |
| usfrs_ContaminatedSite-Facility | uri | usfrsdata:d.FRS-Facility.110000394635 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3585 | 1 |
| usfrs_BrownfieldsSite-Facility | uri | usfrsdata:d.FRS-Facility.110001347490 | http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3523 | 1 |




## LinkML Source

<details>

```yaml
name: usfrs_tscaIndustry
annotations:
  count:
    tag: count
    value: 536
description: Toxic Substances Control Act Industry Code
title: No slot (predicate) name specified
examples:
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3441
    example_object_type: uri
    example_predicate: usfrs:tscaIndustry
    example_subject: usfrsdata:d.FRS-Facility.110000314464
    example_subject_type: usfrs_Stationary-Facility
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3441
    example_object_type: uri
    example_predicate: usfrs:tscaIndustry
    example_subject: usfrsdata:d.FRS-Facility.110000314464
    example_subject_type: usfrs_FRS-Facility
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3441
    example_object_type: uri
    example_predicate: usfrs:tscaIndustry
    example_subject: usfrsdata:d.FRS-Facility.110000314464
    example_subject_type: fio_Facility
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3441
    example_object_type: uri
    example_predicate: usfrs:tscaIndustry
    example_subject: usfrsdata:d.FRS-Facility.110000314464
    example_subject_type: __b1
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3499
    example_object_type: uri
    example_predicate: usfrs:tscaIndustry
    example_subject: usfrsdata:d.FRS-Facility.110000381934
    example_subject_type: usfrs_EPA-PFAS-Facility
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3585
    example_object_type: uri
    example_predicate: usfrs:tscaIndustry
    example_subject: usfrsdata:d.FRS-Facility.110000394635
    example_subject_type: usfrs_ContaminatedSite-Facility
- object:
    example_object: http://sawgraph.spatialai.org/v1/fio/sic#SIC-IndustryCode-3523
    example_object_type: uri
    example_predicate: usfrs:tscaIndustry
    example_subject: usfrsdata:d.FRS-Facility.110001347490
    example_subject_type: usfrs_BrownfieldsSite-Facility
from_schema: fio-kg
rank: 1000
slot_uri: usfrs:tscaIndustry
alias: usfrs_tscaIndustry
domain_of:
- __b1
- fio_Facility
- usfrs_BrownfieldsSite-Facility
- usfrs_ContaminatedSite-Facility
- usfrs_EPA-PFAS-Facility
- usfrs_FRS-Facility
- usfrs_Stationary-Facility
range: uri

```
</details>