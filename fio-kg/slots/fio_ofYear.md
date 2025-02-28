

# Slot: No slot (predicate) name specified (fio_ofYear)


_No slot (predicate) description specified_






This slot occurs 2125 times.


URI: [fio:ofYear](http://sawgraph.spatialai.org/v1/fio#ofYear)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) | No class (type) description specified |  yes  |
| [NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md) | No class (type) description specified |  yes  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md) | No class (type) description specified |  yes  |
| [NaicsNAICS-Industry](../classes/NaicsNAICS-Industry.md) | No class (type) description specified |  yes  |
| [NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |
| [FioIndustry](../classes/FioIndustry.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |







## Properties

* Range: [XsdGYear](../classes/XsdGYear.md)






## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| naics_NAICS-IndustryCode | xsd_gYear | naics:NAICS-IndustryCode-11111 | 2022 | 1701 |
| naics_NAICS-Industry | xsd_gYear | naics:NAICS-IndustryCode-11111 | 2022 | 2125 |
| owl_Thing | xsd_gYear | naics:NAICS-IndustryCode-11111 | 2022 | 2125 |
| fio_Industry | xsd_gYear | naics:NAICS-IndustryCode-11111 | 2022 | 2125 |
| owl_NamedIndividual | xsd_gYear | naics:NAICS-IndustryCode-11111 | 2022 | 2125 |
| naics_NAICS-IndustryGroup | xsd_gYear | naics:NAICS-IndustryGroup-1111 | 2022 | 308 |
| naics_NAICS-IndustrySector | xsd_gYear | naics:NAICS-IndustrySector-11 | 2022 | 20 |
| naics_NAICS-IndustrySubsector | xsd_gYear | naics:NAICS-IndustrySubsector-111 | 2022 | 96 |




## LinkML Source

<details>

```yaml
name: fio_ofYear
annotations:
  count:
    tag: count
    value: 2125
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: '2022'
    example_object_type: xsd_gYear
    example_predicate: fio:ofYear
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-IndustryCode
- object:
    example_object: '2022'
    example_object_type: xsd_gYear
    example_predicate: fio:ofYear
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-Industry
- object:
    example_object: '2022'
    example_object_type: xsd_gYear
    example_predicate: fio:ofYear
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_Thing
- object:
    example_object: '2022'
    example_object_type: xsd_gYear
    example_predicate: fio:ofYear
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: fio_Industry
- object:
    example_object: '2022'
    example_object_type: xsd_gYear
    example_predicate: fio:ofYear
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_NamedIndividual
- object:
    example_object: '2022'
    example_object_type: xsd_gYear
    example_predicate: fio:ofYear
    example_subject: naics:NAICS-IndustryGroup-1111
    example_subject_type: naics_NAICS-IndustryGroup
- object:
    example_object: '2022'
    example_object_type: xsd_gYear
    example_predicate: fio:ofYear
    example_subject: naics:NAICS-IndustrySector-11
    example_subject_type: naics_NAICS-IndustrySector
- object:
    example_object: '2022'
    example_object_type: xsd_gYear
    example_predicate: fio:ofYear
    example_subject: naics:NAICS-IndustrySubsector-111
    example_subject_type: naics_NAICS-IndustrySubsector
from_schema: fio-kg
rank: 1000
slot_uri: fio:ofYear
alias: fio_ofYear
domain_of:
- fio_Industry
- naics_NAICS-Industry
- naics_NAICS-IndustryCode
- naics_NAICS-IndustryGroup
- naics_NAICS-IndustrySector
- naics_NAICS-IndustrySubsector
- owl_NamedIndividual
- owl_Thing
range: xsd_gYear

```
</details>