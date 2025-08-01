

# Slot: Identifier (dct_identifier)


_Recommended practice is to identify the resource by means of a string conforming to an identification system. Examples include International Standard Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name (URN).  Persistent identifiers should be provided as HTTP URIs._






This slot occurs 1755984 times.


URI: [dct:identifier](http://purl.org/dc/terms/identifier)



<!-- no inheritance hierarchy -->





## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
| [NaicsNAICS-IndustrySubsector](../classes/NaicsNAICS-IndustrySubsector.md) |  |  no  |
| [Fio-epa-frsFRS-Facility](../classes/Fio-epa-frsFRS-Facility.md) | Facility from EPA Facility Registry Service |  no  |
| [Node513](../classes/Node513.md) |  |  no  |
| [Node518](../classes/Node518.md) |  |  no  |
| [Fio-epa-frsRecord](../classes/Fio-epa-frsRecord.md) |  |  no  |
| [Node501](../classes/Node501.md) |  |  no  |
| [Fio-epa-frsEPA-PFAS-Facility](../classes/Fio-epa-frsEPA-PFAS-Facility.md) | Facility identified as potentially handling PFAS in EPA PFAS Analytic tools b... |  no  |
| [Node515](../classes/Node515.md) |  |  no  |
| [Node519](../classes/Node519.md) |  |  no  |
| [Node523](../classes/Node523.md) |  |  no  |
| [Node521](../classes/Node521.md) |  |  no  |
| [Fio-epa-frsSupplementalRecord](../classes/Fio-epa-frsSupplementalRecord.md) | Supplemental Record that relates to a facility but primarily identifies somet... |  no  |
| [Node359](../classes/Node359.md) |  |  no  |
| [Node508](../classes/Node508.md) |  |  no  |
| [Node507](../classes/Node507.md) |  |  no  |
| [Node499](../classes/Node499.md) |  |  no  |
| [Node517](../classes/Node517.md) |  |  no  |
| [NaicsNAICS-IndustryGroup](../classes/NaicsNAICS-IndustryGroup.md) |  |  no  |
| [NaicsNAICS-IndustrySector](../classes/NaicsNAICS-IndustrySector.md) |  |  no  |
| [Node506](../classes/Node506.md) |  |  no  |
| [Node510](../classes/Node510.md) |  |  no  |
| [Node502](../classes/Node502.md) |  |  no  |
| [Node512](../classes/Node512.md) |  |  no  |
| [NaicsNAICS-IndustryCode](../classes/NaicsNAICS-IndustryCode.md) |  |  no  |







## Properties

* Range: [RdfsLiteral](../classes/RdfsLiteral.md)





## Comments

* description: An unambiguous reference to the resource within a given context.
* No occurrences of this slot in the graph.



## LinkML Source

<details>

```yaml
name: dct_identifier
description: Recommended practice is to identify the resource by means of a string
  conforming to an identification system. Examples include International Standard
  Book Number (ISBN), Digital Object Identifier (DOI), and Uniform Resource Name (URN).  Persistent
  identifiers should be provided as HTTP URIs.
title: Identifier
comments:
- 'description: An unambiguous reference to the resource within a given context.'
- No occurrences of this slot in the graph.
from_schema: okns:dc
source: http://purl.org/dc/terms/
slot_uri: dct:identifier
domain_of:
- __node359
- __node499
- __node501
- __node502
- __node506
- __node507
- __node508
- __node510
- __node512
- __node513
- __node515
- __node517
- __node518
- __node519
- __node521
- __node523
- fio-epa-frs_EPA-PFAS-Facility
- fio-epa-frs_FRS-Facility
- fio-epa-frs_Record
- fio-epa-frs_SupplementalRecord
- naics_NAICS-IndustryCode
- naics_NAICS-IndustryGroup
- naics_NAICS-IndustrySector
- naics_NAICS-IndustrySubsector
subproperty_of: dc_identifier
range: rdfs_Literal

```
</details>