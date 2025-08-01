

# Slot: of Year (fio_ofYear)


_A relation between an industry code and the schema year it belongs to._






This slot occurs 2129 times.


URI: [fio:ofYear](http://w3id.org/fio/v1/fio#ofYear)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md) |  |  no  |
| [NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md) |  |  no  |
| [NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md) |  |  no  |
| [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |  |  no  |







## Properties

* Range: [Any](../classes/Any.md)&nbsp;or&nbsp;<br />[xsd:date](http://www.w3.org/2001/XMLSchema#date)&nbsp;or&nbsp;<br />[XsdGYear](../classes/XsdGYear.md)







## LinkML Source

<details>

```yaml
name: fio_ofYear
description: A relation between an industry code and the schema year it belongs to.
title: of Year
from_schema: okns:fiokg
exact_mappings:
- http://w3id.org/fio/v1/fio#ofYear
rank: 1000
slot_uri: fio:ofYear
alias: fio_ofYear
domain_of:
- naics_NAICS-IndustryCode
- naics_NAICS-IndustryGroup
- naics_NAICS-IndustrySector
- naics_NAICS-IndustrySubsector
union_of:
- owl_Thing
- fio_Industry
range: Any
any_of:
- range: date
- range: xsd_gYear

```
</details>