

# Slot: subcode of (fio_subcodeOf)


_A hierarchical relation between an industry and its parent industry_






This slot occurs 7847 times.


URI: [fio:subcodeOf](http://w3id.org/fio/v1/fio#subcodeOf)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md) |  |  no  |
| [NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md) |  |  no  |
| [NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md)&nbsp;or&nbsp;<br />[OwlThing](../classes/OwlThing.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md)&nbsp;or&nbsp;<br />[NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md)&nbsp;or&nbsp;<br />[FioIndustry](../classes/FioIndustry.md)&nbsp;or&nbsp;<br />[OwlNamedIndividual](../classes/OwlNamedIndividual.md)







## LinkML Source

<details>

```yaml
name: fio_subcodeOf
description: A hierarchical relation between an industry and its parent industry
title: subcode of
from_schema: okns:fio-kg
exact_mappings:
- http://w3id.org/fio/v1/fio#subcodeOf
rank: 1000
slot_uri: fio:subcodeOf
alias: fio_subcodeOf
domain_of:
- naics_NAICS-IndustryCode
- naics_NAICS-IndustryGroup
- naics_NAICS-IndustrySubsector
union_of:
- fio_Industry
- owl_Thing
range: Any
any_of:
- range: naics_NAICS-IndustryGroup
- range: owl_Thing
- range: naics_NAICS-IndustrySubsector
- range: naics_NAICS-IndustrySector
- range: naics_NAICS-IndustryCode
- range: fio_Industry
- range: owl_NamedIndividual

```
</details>