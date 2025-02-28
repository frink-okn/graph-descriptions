

# Slot: No slot (predicate) name specified (fio_subcodeOf)


_No slot (predicate) description specified_






This slot occurs 5815 times.


URI: [fio:subcodeOf](http://sawgraph.spatialai.org/v1/fio#subcodeOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md) | No class (type) description specified |  yes  |
| [OwlThing](../classes/OwlThing.md) | No class (type) description specified |  yes  |
| [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) | No class (type) description specified |  no  |
| [NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md) | No class (type) description specified |  yes  |
| [NaicsNAICS-Industry](../classes/NaicsNAICS-Industry.md) | No class (type) description specified |  yes  |
| [NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md) | No class (type) description specified |  yes  |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | No class (type) description specified |  yes  |
| [FioIndustry](../classes/FioIndustry.md) | No class (type) description specified |  yes  |
| [OwlNothing](../classes/OwlNothing.md) | No class (type) description specified |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md)&nbsp;or&nbsp;<br />[FioIndustry](../classes/FioIndustry.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md)&nbsp;or&nbsp;<br />[xsd:anyURI](http://www.w3.org/2001/XMLSchema#anyURI)&nbsp;or&nbsp;<br />[NaicsNAICS-Industry](../classes/NaicsNAICS-Industry.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)

## Usages

| used by | used in | type | used |
| ---  | --- | --- | --- |
| [FioIndustry](../classes/FioIndustry.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | domain | [fio_subcodeOf](../slots/fio_subcodeOf.md) |
| [NaicsNAICS-Industry](../classes/NaicsNAICS-Industry.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | domain | [fio_subcodeOf](../slots/fio_subcodeOf.md) |
| [NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | domain | [fio_subcodeOf](../slots/fio_subcodeOf.md) |
| [NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | domain | [fio_subcodeOf](../slots/fio_subcodeOf.md) |
| [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | domain | [fio_subcodeOf](../slots/fio_subcodeOf.md) |
| [NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | domain | [fio_subcodeOf](../slots/fio_subcodeOf.md) |
| [OwlNamedIndividual](../classes/OwlNamedIndividual.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | domain | [fio_subcodeOf](../slots/fio_subcodeOf.md) |
| [OwlNothing](../classes/OwlNothing.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | domain | [fio_subcodeOf](../slots/fio_subcodeOf.md) |
| [OwlThing](../classes/OwlThing.md) | [fio_subcodeOf](../slots/fio_subcodeOf.md) | domain | [fio_subcodeOf](../slots/fio_subcodeOf.md) |







## Examples

| Subject type | Object type | Example subject | Example object | Occurrences |
| --- | --- | --- | --- | --- |
| naics_NAICS-IndustryCode | naics_NAICS-IndustryGroup | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 1701 |
| naics_NAICS-IndustryCode | naics_NAICS-Industry | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5103 |
| naics_NAICS-IndustryCode | owl_Thing | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 4625 |
| naics_NAICS-IndustryCode | fio_Industry | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5103 |
| naics_NAICS-IndustryCode | owl_NamedIndividual | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 4625 |
| naics_NAICS-Industry | naics_NAICS-IndustryGroup | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 1701 |
| naics_NAICS-Industry | naics_NAICS-Industry | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5815 |
| naics_NAICS-Industry | owl_Thing | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5232 |
| naics_NAICS-Industry | fio_Industry | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5815 |
| naics_NAICS-Industry | owl_NamedIndividual | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5232 |
| owl_Thing | naics_NAICS-IndustryGroup | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 1701 |
| owl_Thing | naics_NAICS-Industry | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5815 |
| owl_Thing | owl_Thing | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5232 |
| owl_Thing | fio_Industry | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5815 |
| owl_Thing | owl_NamedIndividual | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5232 |
| fio_Industry | naics_NAICS-IndustryGroup | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 1701 |
| fio_Industry | naics_NAICS-Industry | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5815 |
| fio_Industry | owl_Thing | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5232 |
| fio_Industry | fio_Industry | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5815 |
| fio_Industry | owl_NamedIndividual | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5232 |
| owl_NamedIndividual | naics_NAICS-IndustryGroup | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 1701 |
| owl_NamedIndividual | naics_NAICS-Industry | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5815 |
| owl_NamedIndividual | owl_Thing | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5232 |
| owl_NamedIndividual | fio_Industry | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5815 |
| owl_NamedIndividual | owl_NamedIndividual | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustryGroup-1111 | 5232 |
| naics_NAICS-IndustryCode | naics_NAICS-IndustrySector | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustrySector-11 | 1701 |
| naics_NAICS-Industry | naics_NAICS-IndustrySector | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustrySector-11 | 2105 |
| owl_Thing | naics_NAICS-IndustrySector | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustrySector-11 | 2105 |
| fio_Industry | naics_NAICS-IndustrySector | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustrySector-11 | 2105 |
| owl_NamedIndividual | naics_NAICS-IndustrySector | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustrySector-11 | 2105 |
| naics_NAICS-IndustryCode | naics_NAICS-IndustrySubsector | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustrySubsector-111 | 1701 |
| naics_NAICS-Industry | naics_NAICS-IndustrySubsector | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustrySubsector-111 | 2009 |
| owl_Thing | naics_NAICS-IndustrySubsector | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustrySubsector-111 | 2009 |
| fio_Industry | naics_NAICS-IndustrySubsector | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustrySubsector-111 | 2009 |
| owl_NamedIndividual | naics_NAICS-IndustrySubsector | naics:NAICS-IndustryCode-11111 | naics:NAICS-IndustrySubsector-111 | 2009 |
| naics_NAICS-IndustryGroup | naics_NAICS-Industry | naics:NAICS-IndustryGroup-1111 | naics:NAICS-IndustrySector-11 | 616 |
| naics_NAICS-IndustryGroup | owl_Thing | naics:NAICS-IndustryGroup-1111 | naics:NAICS-IndustrySector-11 | 534 |
| naics_NAICS-IndustryGroup | naics_NAICS-IndustrySector | naics:NAICS-IndustryGroup-1111 | naics:NAICS-IndustrySector-11 | 308 |
| naics_NAICS-IndustryGroup | fio_Industry | naics:NAICS-IndustryGroup-1111 | naics:NAICS-IndustrySector-11 | 616 |
| naics_NAICS-IndustryGroup | owl_NamedIndividual | naics:NAICS-IndustryGroup-1111 | naics:NAICS-IndustrySector-11 | 534 |
| naics_NAICS-IndustryGroup | naics_NAICS-IndustrySubsector | naics:NAICS-IndustryGroup-1111 | naics:NAICS-IndustrySubsector-111 | 308 |
| naics_NAICS-IndustrySubsector | naics_NAICS-Industry | naics:NAICS-IndustrySubsector-111 | naics:NAICS-IndustrySector-11 | 96 |
| naics_NAICS-IndustrySubsector | owl_Thing | naics:NAICS-IndustrySubsector-111 | naics:NAICS-IndustrySector-11 | 73 |
| naics_NAICS-IndustrySubsector | naics_NAICS-IndustrySector | naics:NAICS-IndustrySubsector-111 | naics:NAICS-IndustrySector-11 | 96 |
| naics_NAICS-IndustrySubsector | fio_Industry | naics:NAICS-IndustrySubsector-111 | naics:NAICS-IndustrySector-11 | 96 |
| naics_NAICS-IndustrySubsector | owl_NamedIndividual | naics:NAICS-IndustrySubsector-111 | naics:NAICS-IndustrySector-11 | 73 |




## LinkML Source

<details>

```yaml
name: fio_subcodeOf
annotations:
  count:
    tag: count
    value: 5815
description: No slot (predicate) description specified
title: No slot (predicate) name specified
examples:
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: naics_NAICS-IndustryGroup
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-IndustryCode
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: naics_NAICS-Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-IndustryCode
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: owl_Thing
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-IndustryCode
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: fio_Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-IndustryCode
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: owl_NamedIndividual
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-IndustryCode
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: naics_NAICS-IndustryGroup
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-Industry
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: naics_NAICS-Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-Industry
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: owl_Thing
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-Industry
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: fio_Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-Industry
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: owl_NamedIndividual
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-Industry
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: naics_NAICS-IndustryGroup
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_Thing
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: naics_NAICS-Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_Thing
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: owl_Thing
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_Thing
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: fio_Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_Thing
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: owl_NamedIndividual
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_Thing
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: naics_NAICS-IndustryGroup
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: fio_Industry
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: naics_NAICS-Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: fio_Industry
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: owl_Thing
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: fio_Industry
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: fio_Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: fio_Industry
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: owl_NamedIndividual
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: fio_Industry
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: naics_NAICS-IndustryGroup
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_NamedIndividual
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: naics_NAICS-Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_NamedIndividual
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: owl_Thing
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_NamedIndividual
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: fio_Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_NamedIndividual
- object:
    example_object: naics:NAICS-IndustryGroup-1111
    example_object_type: owl_NamedIndividual
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_NamedIndividual
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: naics_NAICS-IndustrySector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-IndustryCode
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: naics_NAICS-IndustrySector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-Industry
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: naics_NAICS-IndustrySector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_Thing
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: naics_NAICS-IndustrySector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: fio_Industry
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: naics_NAICS-IndustrySector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_NamedIndividual
- object:
    example_object: naics:NAICS-IndustrySubsector-111
    example_object_type: naics_NAICS-IndustrySubsector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-IndustryCode
- object:
    example_object: naics:NAICS-IndustrySubsector-111
    example_object_type: naics_NAICS-IndustrySubsector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: naics_NAICS-Industry
- object:
    example_object: naics:NAICS-IndustrySubsector-111
    example_object_type: naics_NAICS-IndustrySubsector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_Thing
- object:
    example_object: naics:NAICS-IndustrySubsector-111
    example_object_type: naics_NAICS-IndustrySubsector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: fio_Industry
- object:
    example_object: naics:NAICS-IndustrySubsector-111
    example_object_type: naics_NAICS-IndustrySubsector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryCode-11111
    example_subject_type: owl_NamedIndividual
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: naics_NAICS-Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryGroup-1111
    example_subject_type: naics_NAICS-IndustryGroup
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: owl_Thing
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryGroup-1111
    example_subject_type: naics_NAICS-IndustryGroup
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: naics_NAICS-IndustrySector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryGroup-1111
    example_subject_type: naics_NAICS-IndustryGroup
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: fio_Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryGroup-1111
    example_subject_type: naics_NAICS-IndustryGroup
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: owl_NamedIndividual
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryGroup-1111
    example_subject_type: naics_NAICS-IndustryGroup
- object:
    example_object: naics:NAICS-IndustrySubsector-111
    example_object_type: naics_NAICS-IndustrySubsector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustryGroup-1111
    example_subject_type: naics_NAICS-IndustryGroup
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: naics_NAICS-Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustrySubsector-111
    example_subject_type: naics_NAICS-IndustrySubsector
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: owl_Thing
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustrySubsector-111
    example_subject_type: naics_NAICS-IndustrySubsector
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: naics_NAICS-IndustrySector
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustrySubsector-111
    example_subject_type: naics_NAICS-IndustrySubsector
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: fio_Industry
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustrySubsector-111
    example_subject_type: naics_NAICS-IndustrySubsector
- object:
    example_object: naics:NAICS-IndustrySector-11
    example_object_type: owl_NamedIndividual
    example_predicate: fio:subcodeOf
    example_subject: naics:NAICS-IndustrySubsector-111
    example_subject_type: naics_NAICS-IndustrySubsector
from_schema: fio-kg
rank: 1000
domain: fio_subcodeOf
slot_uri: fio:subcodeOf
alias: fio_subcodeOf
domain_of:
- fio_Industry
- naics_NAICS-Industry
- naics_NAICS-IndustryCode
- naics_NAICS-IndustryGroup
- naics_NAICS-IndustrySubsector
- owl_NamedIndividual
- owl_Thing
range: Any
any_of:
- range: naics_NAICS-IndustrySubsector
- range: fio_Industry
- range: owl_Thing
- range: naics_NAICS-IndustryGroup
- range: uri
- range: naics_NAICS-Industry
- range: naics_NAICS-IndustrySector
- range: owl_NamedIndividual

```
</details>